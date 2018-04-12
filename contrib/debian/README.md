
Debian
====================
This directory contains files used to package almexd/almex-qt
for Debian-based Linux systems. If you compile almexd/almex-qt yourself, there are some useful files here.

## almex: URI support ##


almex-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install almex-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your almexqt binary to `/usr/bin`
and the `../../share/pixmaps/almex128.png` to `/usr/share/pixmaps`

almex-qt.protocol (KDE)

