
Debian
====================
This directory contains files used to package ventured/venture-qt
for Debian-based Linux systems. If you compile ventured/venture-qt yourself, there are some useful files here.

## venture: URI support ##


venture-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install venture-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ventureqt binary to `/usr/bin`
and the `../../share/pixmaps/venture128.png` to `/usr/share/pixmaps`

venture-qt.protocol (KDE)

