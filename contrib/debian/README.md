
Debian
====================
This directory contains files used to package globalgamecoind/globalgamecoin-qt
for Debian-based Linux systems. If you compile globalgamecoind/globalgamecoin-qt yourself, there are some useful files here.

## globalgamecoin: URI support ##


globalgamecoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install globalgamecoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your globalgamecoinqt binary to `/usr/bin`
and the `../../share/pixmaps/globalgamecoin128.png` to `/usr/share/pixmaps`

globalgamecoin-qt.protocol (KDE)

