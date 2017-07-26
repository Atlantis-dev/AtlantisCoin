
Debian
====================
This directory contains files used to package atld/atl-qt
for Debian-based Linux systems. If you compile atld/atl-qt yourself, there are some useful files here.

## atl: URI support ##


atl-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install atl-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your atl-qt binary to `/usr/bin`
and the `../../share/pixmaps/atl128.png` to `/usr/share/pixmaps`

atl-qt.protocol (KDE)

