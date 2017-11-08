### Compile Qt 5.6.3 in Ubuntu 17.10 x64
#### 0. Prepare
```
sudo apt install build-essential
```
#### 1. Download Qt 5.6.3 open source
Go to [download.qt.io](https://download.qt.io/official_releases/qt/5.6/5.6.3/single/), download "qt-everywhere-opensource-src-5.6.3.tar.xz".
#### 2. Unzip
```
xz -d qt-everywhere-opensource-src-5.6.3.tar.xz
tar -xvf qt-everywhere-opensource-src-5.6.3.tar
```
#### 3. Configure
```
cd qt-everywhere-opensource-src-5.6.3
./configure
```
See results in terminal carefully
#### 4. Make
```
make
```
Following commands might be executed
```
sudo apt install python
```
#### 5. Install
```
sudo make install
```
#### 6. Environment
```
gedit ~/.profile
```
Add the following texts at the bottom and then log out
```
PATH=/usr/local/Qt-5.6.3/bin:$PATH
export PATH
```
Log in and run the following command to check
```
qmake -v
```
