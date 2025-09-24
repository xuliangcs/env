[TOC]


# Version Selection Strategy

[PyTorch version](https://pytorch.org/get-started/previous-versions/) -> [CUDA version](https://developer.nvidia.com/cuda-toolkit-archive) -> [cuDNN version](https://developer.nvidia.com/cudnn-downloads)


# CUDA, cuDNN, GPU Driver
- The **GPU Driver** can be installed [separately](https://www.nvidia.cn/Download/index.aspx?lang=en) or installed by CUDA. 👇
- Download **CUDA**: https://developer.nvidia.com/cuda-downloads
- Install CUDA according to the download webpage. For Windows, double click the `.exe`; for Ubuntu: 
    ```bash
    # eg:
    wget https://developer.download.nvidia.com/compute/cuda/12.4.1/local_installers/cuda_xx.x.x_yyy.yy.yy_linux.run
    sudo sh cuda_xx.x.x_yyy.yy.yy_linux.run 
    # x denotes the cuda version and y denotes the Driver version
    ```
- CUDA installation path: `/usr/local/cuda-11.8` (Ubuntu) or `C:\\Program Files\\NVIDlA GPU Computing Toolkit\\CUDAlv11.8` (Windows)
- For Windows, CUDA's path has been configured to the system `PATH`. ([see](./res/img_logs.md))
- For Ubuntu, configure CUDA's `bin` and `lib` paths to `.bashrc`.
    ```bash
    vim ~/.bashrc
    #append cuda path:
    export PATH=$PATH:/usr/local/cuda-10.1/bin
    export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:/usr/local/cuda-10.1/lib64
    ```
- A `soft-connection` could be used to support multi-version switching, e.g., `conda`->`conda-10.1` and `CUDA_PATH`->`CUDA_PATH_V11_8`
- **cuDNN** Download from a browser: https://developer.nvidia.com/cudnn-downloads or a shell terminal: `wget https://developer.download.nvidia.com/compute/cudnn/redist/cudnn/windows-x86_64/cudnn-windows-x86_64-9.0.0.312_cuda11-archive.zip`
- Copy `include`, `bin`, and `lib` to the same locations under the CUDA's installation paths.



# Anaconda 
## Installation
- Download from: https://www.anaconda.com/download/success
- You can install it to `path/to/home/local/`
- For Ubuntu, configure conda's path to `.bashrc` (the conda base environment is embedded into the default shell)
- For Windows, use `Anaconda PowerShell` or `Anaconda Prompt` as the default shell
- If you use `vscode` as the IDE, after opening a `.py` file, there is a `python version selection` button in the `lower right corner` of the software window. Click to choose the correct `python path`. Then, click the `RUN` `triangle` in the `upper right corner` to launch the `terminal` of this python environment.
- `Python Path`. You can try the `which python` and `where python` commands in Linux and Windows shells, respectively. e.g.:
    - `ubuntu`: /home/username/local/anaconda3/envs/xxx/bin/python
    - `windows`: C:/Users/username/anaconda3/envs/xxx/python


## Create codna virtual environment
For instance:
```bash
# create the env
conda create -n demo_name python=3.8
# enter the env:
conda activate demo_name
```
> Delete a conda envirnment: `conda env remove -n xxx`

## Speed issues
Add conda mirror source, if necessary:
```bash
conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free/
conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/main/
conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/pytorch/
conda config --add channels https://mirrors.ustc.edu.cn/anaconda/cloud/conda-forge
conda config --set show_channel_urls yes
```
Delete the added sources:
```bash
conda config --remove-key channels
```

# PyTorch
## Installation
```bash
# enter the env:
conda activate demo_name
# install pytorch
conda install pytorch==1.7.0 torchvision==0.8.0 torchaudio==0.7.0 cudatoolkit=11.0 -c pytorch

pip install -r requirements.txt
```
`requirements.txt` is as folows:
```bash
h5py==3.8.0
matplotlib==3.5.3
opencv-python==4.8.1.78
pillow==10.2.0
scikit-learn==1.0.2
```
> Note: the lib packages and versions depends on your code's requirements!

- for PyTorch 1.7 with other CUDA versions, please refer to the official [pytorch installation commands](https://pytorch.org/get-started/previous-versions/#v170)
- PyTorch API Documents: https://pytorch.org/docs/stable/index.html
- the speed of different network servers and conda sources varies a lot when install the above packages.


## Test

```bash
# open a terminal
conda activate demo_name

python 

>>> import cv2
>>> import torch
>>> import torchvision
>>> print(cv2.__version__)
>>> print(torch.__version__)
>>> print(torchvision.__version__)
```
