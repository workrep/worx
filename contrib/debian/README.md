
Debian
====================
This directory contains files used to package charityd/charity-qt
for Debian-based Linux systems. If you compile charityd/charity-qt yourself, there are some useful files here.

## charity: URI support ##


charity-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install charity-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your charityqt binary to `/usr/bin`
and the `../../share/pixmaps/charity128.png` to `/usr/share/pixmaps`

charity-qt.protocol (KDE)

