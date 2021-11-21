[TOC]
# Install OpenCV

## 1. Python3 Version

```shell
# check python version:
which python
ls /usr/bin/python*
ls /usr/bin/python
# 
python3 xxx
```



### 1.1 Install 3rd-Party Libraries

1. Install 3rd-party libraries for: compilation, image processing, video processing,  optimization, and computation:

    ```bash
    sudo apt-get install build-essential cmake git pkg-config libjpeg8-dev libtiff5-dev libjasper-dev libpng12-dev libavcodec-dev libavformat-dev libswscale-dev libv4l-dev libgtk2.0-dev libatlas-base-dev gfortran libopenblas-dev libatlas3-base -y
    ```

2. Then, install additional libraries depending on the error info.



### 1.2 Install opencv-python

```shell
pip3 install opencv-python

pip3 list
```

versions:

- python3.7, numpy1.16.2

- opencv-python-4.5.3.56





## 2. C++ Version 

(install from source code)

### 2.1 Downloads

```shell
cd ~/Downloads
wget https://codeload.github.com/opencv/opencv/zip/3.4.0
```
or：
```shell
cd ~/Downloads
wget https://github.com/opencv/opencv/archive/3.4.0.zip
```

or:

https://opencv.org/releases/ 

### 2.2 Unzip the package

`3.4.0.zip` -> extract here -> `opencv-3.4.0`

or:

```shell
cd ~/Downloads
unzip 3.4.0.zip
```



### 2.3 Compile and Install OpenCV to /home/pi/local/opencv-3.4.0

```shell
$ cd /home/pi/Downloads/opencv-3.4.0

$ mkdir build

$ cd build

$ cmake -D CMAKE_BUILD_TYPE=RELEASE -D CMAKE_INSTALL_PREFIX=/home/pi/local/opencv-3.4.0 -D BUILD_opencv_python2=OFF -D BUILD_opencv_python3=OFF -D WITH_LIBV4L=ON -D OPENCV_GENERATE_PKGCONFIG=ON ..

$ make -j4
$ make install
```

[:elephant: Click to see compile logs](./res/logs_rpi4_opencv.md)



Tips:

- `/home/pi/local/opencv-3.4.0 `, NOT`/home/pi/local/opencv-3.4.0/`
- Some errors occurred due to the failures of downloading needed files; try to `cmake` again to fix the errors.
- `opencv.pc` file is stored in`/home/pi/local/opencv-3.4.0/lib/pkgconfig/`



`opencv.pc`:

> \#Package Information for pkg-config
>
> prefix=/home/pi/local/opencv-3.4.0/
>
> exec_prefix=${prefix}
>
> libdir=${exec_prefix}/lib
>
> includedir_old=${prefix}/include/opencv
>
> includedir_new=${prefix}/includeName: OpenCV
>
> Description: Open Source Computer Vision Library
>
> Version: 3.4.0
>
> Libs: -L${exec_prefix}/lib -lopencv_dnn -lopencv_ml -lopencv_objdetect -lopencv_shape -lopencv_stitching -lopencv_superres -lopencv_videostab -lopencv_calib3d -lopencv_features2d -lopencv_highgui -lopencv_videoio -lopencv_imgcodecs -lopencv_video -lopencv_photo -lopencv_imgproc -lopencv_flann -lopencv_core
>
> Libs.private: -ldl -lm -lpthread -lrt
>
> Cflags: -I\${includedir_old} -I\${includedir_new}




### 2.4 Configure OpenCV Libraries (*.so)

Tips：

- Different compilers have their own protocols, e.g., g++, make, cmake, qmake, etc., but the principle is to configure the paths of `header` and `library` files.

- The following configurations are based on `pkg-config` and `g++`.

#### 2.4.1 `pkgconfig` Configuration

  - Add `pkgconfig/openv.pc` to the system's `pkgconfig` searching directories：

    ```shell
    $ vim /home/pi/.bashrc  
    
    at the end of this file, add the following config:  
    
    export PKG_CONFIG_PATH=$PKG_CONFIG_PATH:/home/pi/local/opencv-3.4.0/lib/pkgconfig 
    ```
  - Test pkg-config with OpenCV (Open a new terminal)：
    ```shell
    $  pkg-config --help
    $  pkg-config --list-all
    $  pkg-config --modversion  opencv
    3.4.0
    
    $  pkg-config --cflags opencv
    -I/home/pi/local/opencv-3.4.0/include/opencv -I/home/pi/local/opencv-3.4.0/include
    
    $  pkg-config --libs opencv
    -L/home/pi/local/opencv-3.4.0/lib -lopencv_dnn -lopencv_ml -lopencv_objdetect -lopencv_shape -lopencv_stitching -lopencv_superres -lopencv_videostab -lopencv_calib3d -lopencv_features2d -lopencv_highgui -lopencv_videoio -lopencv_imgcodecs -lopencv_video -lopencv_photo -lopencv_imgproc -lopencv_flann -lopencv_core
    ```



 



#### 2.4.2 Compile the demo

**C++ demo: **

`main.cpp`

```c++
#include<opencv2/opencv.hpp>
#include<iostream>

using namespace std;
using namespace cv;

int main(){

    IplImage* img = cvCreateImage(cvSize(200,200), 8, 3);	
    Mat src = cvarrToMat(img);
    imshow("input image", src);
    waitKey(0);
    
    cvReleaseImage(&img);
    return 0;
}
```
**Compile:**

```shell
g++ -o a.out main.cpp `pkg-config --cflags --libs opencv`
```



#### 2.4.3  Runtime configurations

Add the OpenCV's `lib` path to the system's searching directories：

**Global-based:**

```shell
$ sudo vim /etc/ld.so.conf.d/opencv.conf

/home/pi/local/opencv-3.4.0/lib

$ sudo ldconfig
```

or

**Shell-based:**

```shell
vim /home/pi/.bashrc

at the end of this file, add the following:

export LD_LIBRARY_PATH=$LD_LIBRARY_PATH:/home/pi/local/opencv-3.4.0/lib
```



#### 2.4.4 Execution
```shell
./a.out
```
