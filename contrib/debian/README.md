
Debian
====================
This directory contains files used to package masterbitd/masterbit-qt
for Debian-based Linux systems. If you compile masterbitd/masterbit-qt yourself, there are some useful files here.

## masterbit: URI support ##


masterbit-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install masterbit-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your masterbit-qt binary to `/usr/bin`
and the `../../share/pixmaps/masterbit128.png` to `/usr/share/pixmaps`

masterbit-qt.protocol (KDE)

