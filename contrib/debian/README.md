
Debian
====================
This directory contains files used to package digitaldenard/digitaldenar-qt
for Debian-based Linux systems. If you compile digitaldenard/digitaldenar-qt yourself, there are some useful files here.

## digitaldenar: URI support ##


digitaldenar-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install digitaldenar-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your digitaldenarqt binary to `/usr/bin`
and the `../../share/pixmaps/digitaldenar128.png` to `/usr/share/pixmaps`

digitaldenar-qt.protocol (KDE)

