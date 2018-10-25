
Debian
====================
This directory contains files used to package beatcoind/beatcoin-qt
for Debian-based Linux systems. If you compile beatcoind/beatcoin-qt yourself, there are some useful files here.

## beatcoin: URI support ##


beatcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install beatcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your beatcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/beatcoin128.png` to `/usr/share/pixmaps`

beatcoin-qt.protocol (KDE)

