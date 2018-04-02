
Debian
====================
This directory contains files used to package nibexd/nibex-qt
for Debian-based Linux systems. If you compile nibexd/nibex-qt yourself, there are some useful files here.

## nibex: URI support ##


nibex-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install nibex-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your nibexqt binary to `/usr/bin`
and the `../../share/pixmaps/nibex128.png` to `/usr/share/pixmaps`

nibex-qt.protocol (KDE)

