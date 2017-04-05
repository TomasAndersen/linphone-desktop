Lit info om pakker instalert på nuc6 for å få til å bygge..


git one https://github.com/raymondsvendsen/linphone-desktop.git
LAG EGEN FORK fra denne
cd linphone-desktop
git submodule sync && git submodule update --init --recursive

sudo apt-get install cmake
sudo apt-get install g++
sudo apt-get install pkg-config
sudo apt-get install intltool
sudo apt-get install yasm

autoconf:
possibly undefined macro: AC_PROG_LIBTOO
unrecognized options: --disable-static, --enable-shared
løsning:
sudo apt-get install libtool


sudo apt-get install libx11-dev

Could NOT find Xv
apt-get install libxv-dev

 Could NOT find GLX (missing:  GLX_INCLUDE_DIRS HAVE_GL_GL_H HAVE_GL_GLX_H GLX_LIBRARIES)


 sudo apt-get install libasound2-dev


 sudo apt-get install libnotify-dev

 sudo apt-get install libgtk2.0-dev
