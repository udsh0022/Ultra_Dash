
Debian
====================
This directory contains files used to package ultradashcoind/ultradashcoin-qt
for Debian-based Linux systems. If you compile ultradashcoind/ultradashcoin-qt yourself, there are some useful files here.

## ultradashcoin: URI support ##


ultradashcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ultradashcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ultradashcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/ultradashcoin128.png` to `/usr/share/pixmaps`

ultradashcoin-qt.protocol (KDE)

