
Debian
====================
This directory contains files used to package expid/expi-qt
for Debian-based Linux systems. If you compile expid/expi-qt yourself, there are some useful files here.

## expi: URI support ##


expi-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install expi-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your expiqt binary to `/usr/bin`
and the `../../share/pixmaps/expi128.png` to `/usr/share/pixmaps`

expi-qt.protocol (KDE)

