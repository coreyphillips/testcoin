
Debian
====================
This directory contains files used to package bitcoind/testcoin-qt
for Debian-based Linux systems. If you compile bitcoind/testcoin-qt yourself, there are some useful files here.

## testcoin: URI support ##


testcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install testcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your testcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

testcoin-qt.protocol (KDE)

