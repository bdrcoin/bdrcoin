
Debian
====================
This directory contains files used to package bdrcoin/bdrcoin-qt
for Debian-based Linux systems. If you compile bdrcoind/bdrcoin-qt yourself, there are some useful files here.

## bdrcoin: URI support ##


bdrcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bdrcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bdrcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/bdrcoin128.png` to `/usr/share/pixmaps`

bdrcoin-qt.protocol (KDE)

