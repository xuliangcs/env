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





