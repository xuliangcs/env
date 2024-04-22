[TOC]

# Shell Commands

## mount

```shell
$ ls /dev

sdx,sdx1,sdx2,...

$ sudo mkdir /meida/pi/u
$ sudo mount /dev/sdx1 /media/pi/u

```

tips：

- mount partitions instead of the whole disk
- wrong partitions, e.g., `swap` and `boot`
  - unknown filesystem type 'swap'.
  - the device doesn't seem to have a valid NTFS.

## umount

```shell
$ sudo umount /media/pi/u
```





## git

```shell
git config --global --list

git config --local --list
git config --system --list


git config --global user.name "xxx"
git config --global user.email "xxx@xxx.com"
```



## netstat
```shell
sudo netstat -anp | grep xxxx
```
> tcp 0   0 0.0.0.0:1234    0.0.0.0:*   LISTEN  2891/pvrSdk-Demo-qu



