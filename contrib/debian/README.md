
Debian
====================
This directory contains files used to package eazypayzad/eazypayza-qt
for Debian-based Linux systems. If you compile eazypayzad/eazypayza-qt yourself, there are some useful files here.

## eazypayza: URI support ##


eazypayza-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install eazypayza-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your eazypayzaqt binary to `/usr/bin`
and the `../../share/pixmaps/eazypayza128.png` to `/usr/share/pixmaps`

eazypayza-qt.protocol (KDE)

