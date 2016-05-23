# CCID free software driver installer [![Build Status](https://travis-ci.org/martinpaljak/osx-ccid-installer.svg?branch=master)](https://travis-ci.org/martinpaljak/osx-ccid-installer) 

Because of [OSX bugs](http://ludovicrousseau.blogspot.com/2016/04/os-x-el-capitan-and-ccid-driver-upgrades.html) and [features](https://en.wikipedia.org/wiki/System_Integrity_Protection); built from the excellent [CCID free software driver](http://pcsclite.alioth.debian.org/ccid.html) [sources](https://github.com/LudovicRousseau/CCID), the ["official unofficial"](https://github.com/LudovicRousseau/CCID/issues/17#issuecomment-216467582):

#### Easy-to-use (graphical) installer for OSX 10.11
* To download a pre-built installer, see [releases](https://github.com/martinpaljak/osx-ccid-installer/releases)
* To get help: [file an issue](https://github.com/martinpaljak/osx-ccid-installer/issues/new)
* To build yourself (requires XCode plus `libtool`, `autoconf` and `automake` from Homebrew/MacPorts/Fink)
```
  git clone --recursive https://github.com/martinpaljak/osx-ccid-installer
  make -C osx-ccid-installer
```
