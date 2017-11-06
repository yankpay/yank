
Debian
====================
This directory contains files used to package yankd/yank-qt
for Debian-based Linux systems. If you compile yankd/yank-qt yourself, there are some useful files here.

## yank: URI support ##


yank-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install yank-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your yank-qt binary to `/usr/bin`
and the `../../share/pixmaps/yank128.png` to `/usr/share/pixmaps`

yank-qt.protocol (KDE)

