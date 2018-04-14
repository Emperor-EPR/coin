
Debian
====================
This directory contains files used to package eprd/epr-qt
for Debian-based Linux systems. If you compile eprd/epr-qt yourself, there are some useful files here.

## epr: URI support ##


epr-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install epr-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your epr-qt binary to `/usr/bin`
and the `../../share/pixmaps/epr128.png` to `/usr/share/pixmaps`

epr-qt.protocol (KDE)

