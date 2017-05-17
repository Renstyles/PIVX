
Debian
====================
This directory contains files used to package zidd/zid-qt
for Debian-based Linux systems. If you compile zidd/zid-qt yourself, there are some useful files here.

## zid: URI support ##


zid-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install zid-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your zidqt binary to `/usr/bin`
and the `../../share/pixmaps/zid128.png` to `/usr/share/pixmaps`

zid-qt.protocol (KDE)

