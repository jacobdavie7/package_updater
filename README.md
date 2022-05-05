# EOL Update
This project has been rolled into my helper project and is not longer being maintained.
<br>
All new updates can be found in the updater module of my helper project: https://github.com/jacobdavie7/helper
# package_updater
-Bash shell script to check for updates from the package managers apt, flatpak and snap.\
-This will not update any software, only the lists.\
-Script can be found under package-builder:_updater0.1-1/usr/bin/updater\
-Can download the script and run as normal, or download package-builder:_updater0.1-1 directory and build package, or download .deb package from releases\
-To build package yourself: dbkg-deb --build updater0.1-1\
-To install .deb package: apt install ./updater0.1-1  ensure the ./ is used - needed for local package.\
