
Debian
====================
This directory contains files used to package gocoind/gocoin-qt
for Debian-based Linux systems. If you compile gocoind/gocoin-qt yourself, there are some useful files here.

## gocoin: URI support ##


gocoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install gocoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your gocoinqt binary to `/usr/bin`
and the `../../share/pixmaps/gocoin128.png` to `/usr/share/pixmaps`

gocoin-qt.protocol (KDE)

