
Debian
====================
This directory contains files used to package eved/eve-qt
for Debian-based Linux systems. If you compile eved/eve-qt yourself, there are some useful files here.

## eve: URI support ##


eve-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install eve-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your eve-qt binary to `/usr/bin`
and the `../../share/pixmaps/eve128.png` to `/usr/share/pixmaps`

eve-qt.protocol (KDE)

