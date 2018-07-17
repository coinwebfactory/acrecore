
Debian
====================
This directory contains files used to package acred/acre-qt
for Debian-based Linux systems. If you compile acred/acre-qt yourself, there are some useful files here.

## acre: URI support ##


acre-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install acre-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your acreqt binary to `/usr/bin`
and the `../../share/pixmaps/acre128.png` to `/usr/share/pixmaps`

acre-qt.protocol (KDE)

