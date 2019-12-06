## LDOCE5Viewer (PyQt5)

This project is ported to PyQt5 which supports retina (HiDPI) display.  

The LDOCE5 Viewer is an alternative dictionary viewer for the Longman Dictionary of Contemporary English 5th Edition (LDOCE 5).

Website: http://hakidame.net/ldoce5viewer/

It runs on Linux, Mac OS X and Microsoft Windows.

This software is free and open source software licensed under the terms of GPLv3.

## Linux Python 2
default python is python2:

install dependencies:
```bash
sudo apt install -y pyqt5-dev-tools python-pyqt5.qtmultimedia libqt5multimedia5-plugins python-pyqt5.qtwebkit
sudo apt install -y gstreamer1.0-plugins-good gstreamer1.0-plugins-ugly
sudo apt install -y python-whoosh python-lxml python-distutils
```
compile & install
```bash
$ make build
$ sudo make install
```

## Linux Python 3
change default python to python3:
```bash
cd /usr/bin/
sudo rm python
sudo ln -s python3 python
```
install dependencies:
```bash
sudo apt install -y pyqt5-dev-tools python3-pyqt5.qtmultimedia libqt5multimedia5-plugins python3-pyqt5.qtwebkit
sudo apt install -y gstreamer1.0-plugins-good gstreamer1.0-plugins-ugly
sudo apt install -y python3-whoosh python3-lxml python3-distutils
```
compile & install
```bash
$ make build
$ sudo make install
```
