### QNX SDP 6.6 Installation 
#### 1. In order to run the installer and the IDE on Ubuntu 64-bit
command
```
sudo apt-get install libXtst6:i386
E: Unable to locate package libXtst6:i386
```
solution
```
sudo apt autoremove
sudo apt-get install libxtst6:i386
```
#### 2. In order to run the installer on Ubuntu 13.10, you need to install the following:
#### • libXtst-dev
#### • libXtst-dev:i386
#### • libdbus-glib-1-2:i386
#### • libcanberra-gtk-module:i386
#### • gtk2-engines-murrine:i386
solution
```
sudo apt-get install libxtst-dev
sudo apt-get install libxtst-dev:i386
sudo apt-get install libdbus-glib-1-2:i386
sudo apt-get install libcanberra-gtk-module:i386
sudo apt-get install gtk2-engines-murrine:i386
```
