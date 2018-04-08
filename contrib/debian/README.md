
Debian
====================
This directory contains files used to package zixcashd/zixcash-qt
for Debian-based Linux systems. If you compile zixcashd/zixcash-qt yourself, there are some useful files here.

## zixcash: URI support ##


zixcash-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install zixcash-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your zixcashqt binary to `/usr/bin`
and the `../../share/pixmaps/zixcash128.png` to `/usr/share/pixmaps`

zixcash-qt.protocol (KDE)

