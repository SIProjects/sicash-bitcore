
Debian
====================
This directory contains files used to package sicashd/sicash-qt
for Debian-based Linux systems. If you compile sicashd/sicash-qt yourself, there are some useful files here.

## sicash: URI support ##


sicash-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install sicash-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your sicash-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

sicash-qt.protocol (KDE)

