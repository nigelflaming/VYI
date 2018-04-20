
Debian
====================
This directory contains files used to package vyigratd/vyigrat-qt
for Debian-based Linux systems. If you compile vyigratd/vyigrat-qt yourself, there are some useful files here.

## vyigrat: URI support ##


vyigrat-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install vyigrat-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your vyigratqt binary to `/usr/bin`
and the `../../share/pixmaps/vyigrat128.png` to `/usr/share/pixmaps`

vyigrat-qt.protocol (KDE)

