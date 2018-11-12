
Debian
====================
This directory contains files used to package asocoind/asocoin-qt
for Debian-based Linux systems. If you compile asocoind/asocoin-qt yourself, there are some useful files here.

## asocoin: URI support ##


asocoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install asocoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your asocoinqt binary to `/usr/bin`
and the `../../share/pixmaps/asocoin128.png` to `/usr/share/pixmaps`

asocoin-qt.protocol (KDE)

