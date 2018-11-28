
Debian
====================
This directory contains files used to package cmtd/cmt-qt
for Debian-based Linux systems. If you compile cmtd/cmt-qt yourself, there are some useful files here.

## cmt: URI support ##


cmt-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cmt-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cmtqt binary to `/usr/bin`
and the `../../share/pixmaps/cmt128.png` to `/usr/share/pixmaps`

cmt-qt.protocol (KDE)

