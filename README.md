Local manifests to build PacMan ROM for [HTC Desire C]

How to build:
-------------

Initialize repo:

    repo init -u git://github.com/PAC-man/pacman.git -b pac-4.4
    curl --create-dirs -L -o .repo/local_manifests/local_manifest.xml -O -L https://raw.githubusercontent.com/Creeplays/android_local_manifest/cm-11.0/local_manifest.xml
    repo sync

Compile:

    ./build-pac.sh golfu
