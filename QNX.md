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
