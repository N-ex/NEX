
Debian
====================
This directory contains files used to package nexd/nex-qt
for Debian-based Linux systems. If you compile nexd/nex-qt yourself, there are some useful files here.

## nex: URI support ##


nex-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install nex-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your nexqt binary to `/usr/bin`
and the `../../share/pixmaps/nex128.png` to `/usr/share/pixmaps`

nex-qt.protocol (KDE)

