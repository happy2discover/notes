[building_libinput](https://wayland.freedesktop.org/libinput/doc/latest/building_libinput.html)  
[meson](https://github.com/mesonbuild/meson)
```
sudo apt install python3-pip
pip3 install meson
sudo apt install gtk-doc-tools
sudo apt install libgirepository1.0-dev
wget http://ftp.acc.umu.se/pub/gnome/sources/gtk+/3.20/gtk+-3.20.10.tar.xz
tar -xvf gtk+-3.20.10.tar.xz
cd gtk+-3.20.10
./autogen.sh
make && make install
git clone git://anongit.freedesktop.org/wayland/libinput
cd libinput
mkdir builddir
meson --prefix=$WLD builddir/
```
