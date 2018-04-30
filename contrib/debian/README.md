
Debian
====================
This directory contains files used to package fuckingd/fucking-qt
for Debian-based Linux systems. If you compile fuckingd/fucking-qt yourself, there are some useful files here.

## fucking: URI support ##


fucking-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install fucking-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your fucking-qt binary to `/usr/bin`
and the `../../share/pixmaps/fucking128.png` to `/usr/share/pixmaps`

fucking-qt.protocol (KDE)

