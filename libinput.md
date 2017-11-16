[building_libinput](https://wayland.freedesktop.org/libinput/doc/latest/building_libinput.html)  
[meson](https://github.com/mesonbuild/meson)
```
sudo apt install python3-pip
pip3 install meson
wget http://ftp.acc.umu.se/pub/gnome/sources/gtk+/3.20/gtk+-3.20.10.tar.xz

git clone git://anongit.freedesktop.org/wayland/libinput
cd libinput
mkdir builddir
meson --prefix=$WLD builddir/
```
