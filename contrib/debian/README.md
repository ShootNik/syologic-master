
Debian
====================
This directory contains files used to package syologicd/syologic-qt
for Debian-based Linux systems. If you compile syologicd/syologic-qt yourself, there are some useful files here.

## syologic: URI support ##


syologic-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install syologic-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your syologicqt binary to `/usr/bin`
and the `../../share/pixmaps/syologic128.png` to `/usr/share/pixmaps`

syologic-qt.protocol (KDE)

