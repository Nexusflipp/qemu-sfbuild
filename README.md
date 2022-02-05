# seabios-spf


<br>

<p align="center"> 
    <a href="#" target="_blank"> <img src="https://img.shields.io/tokei/lines/github/nexusflipp/seabios-sp"/> </a>
    <a href="#" target="_blank"> <img src="https://img.shields.io/github/issues/nexusflipp/seabios-sp"/> </a>
    <a href="#" target="_blank"> <img src="https://img.shields.io/github/languages/top/nexusflipp/seabios-sp"/> </a> 
    <a href="#" target="_blank"> <img src="https://img.shields.io/github/languages/count/nexusflipp/seabios-sp"/> </a> 
    <a href="#" target="_blank"> <img src="https://img.shields.io/github/last-commit/nexusflipp/seabios-sp"/> </a> 
    <a href="#" target="_blank"> <img src="https://img.shields.io/github/repo-size/nexusflipp/seabios-sp"/> </a> 
    <a href="#" target="_blank"> <img src="https://img.shields.io/github/languages/code-size/nexusflipp/seabios-sp"/> </a> 
</p>

<br>

Custom/Spoofed seabios source.
Please see build and developer information at: http://seabios.org/Developer_Documentation
SeaBIOS is built for QEMU and tested on QEMU.

<br>

## Build Instructions

First cd into the project directory, then run the following commands:

```shell
make menuconfig 
```

```shell
make
```

```shell
qemu -bios out/bios.bin
```

Or you could use my PKGBUILD file.
