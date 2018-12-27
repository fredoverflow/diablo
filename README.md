## Rip ISO

```
$ isoinfo -d -i /dev/cdrom

Logical block size is: 2048
       Volume size is: 292735

$ dd if=/dev/cdrom bs=2048 count=292735 of=diablo.iso
```

## Install

Windows 7 and below have no built-in ISO mounting mechanism, so install [Virtual CloneDrive](https://www.elby.ch/download/SetupVCD.exe) first!

* double-click `diablo.iso`
* double-click `AUTORUN.EXE`
* Install & Play Diablo
* change `C:\Diablo` to `C:\Users\fred\Diablo`
* skip intro
* Exit Diablo

## Patch 1.09

* double-click `drtl109.exe`
* skip intro
* Exit Diablo

## Color palette

* double-click `d109_x64.reg`

## UDP network

* double-click `UDP_Diablo_v1.09.zip`
* double-click `UDPFiles`
* copy `sndi.nx` and `Storm.dll` to `C:\Users\fred\Diablo`

## Start

* double-click `diablo.iso`
* double-click `AUTORUN.EXE`
* Play Diablo
