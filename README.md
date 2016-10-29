Note: THIS IS NOT AN OFFICIAL REPO! No official development is done here.

= Customizations in this repo =
![Whitespace Padding](/customizations/tab_title_padding.png?raw=true "Tab title whitespace padding")

== About Yakuake ==

Yakuake is a drop-down terminal emulator based on KDE Konsole technology.

It's a KDE Extragear application released under GPL v2, GPL v3 or any later
version accepted by the membership of KDE e.V.

The current maintainer of Yakuake is Eike Hein <hein@kde.org>.

The Yakuake website is located at: http://yakuake.kde.org/

Report bugs and wishes at: http://bugs.kde.org/

You can browse the latest and older sources at:
http://projects.kde.org/projects/extragear/utils/yakuake/repository


Yakuake requires kdelibs and Konsole from KDE Software Compilation 4.4.0 or
higher.


Basic build and installation instructions:

1. tar xfvj yakuake-<version>.tar.bz2
2. cd yakuake-<version>
3. mkdir build
4. cd build
5. cmake -DCMAKE_INSTALL_PREFIX=<path to install to> ../
6. make
7. sudo make install

For more, please see the KDE Techbase wiki (http://techbase.kde.org/) and
the CMake documentation (at http://www.cmake.org/).


Prerequisites for building Yakuake, as of version 3.0.2, on Ubuntu/Debian:

cmake, debhelper (>= 9), extra-cmake-modules, kio-dev, libkf5archive-dev,
libkf5config-dev, libkf5coreaddons-dev, libkf5crash-dev, libkf5dbusaddons-dev,
libkf5globalaccel-dev, libkf5i18n-dev, libkf5iconthemes-dev, libkf5newstuff-dev,
libkf5notifications-dev, libkf5notifyconfig-dev, libkf5parts-dev, libkf5widgetsaddons-dev,
libkf5windowsystem-dev, libqt5x11extras5-dev, pkg-kde-tools (>= 0.4.2), qtbase5-dev

Based on https://anonscm.debian.org/cgit/pkg-kde/kde-extras/yakuake.git/tree/debian/control
