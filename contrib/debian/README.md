
Debian
====================
This directory contains files used to package taurusnetworkd/taurusnetwork-qt
for Debian-based Linux systems. If you compile taurusnetworkd/taurusnetwork-qt yourself, there are some useful files here.

## taurusnetwork: URI support ##


taurusnetwork-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install taurusnetwork-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your taurusnetworkqt binary to `/usr/bin`
and the `../../share/pixmaps/taurusnetwork128.png` to `/usr/share/pixmaps`

taurusnetwork-qt.protocol (KDE)

