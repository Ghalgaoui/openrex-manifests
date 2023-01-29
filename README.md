$ mkdir openrex_workspace
$ cd openrex_workspace

$ repo init -u  https://github.com/Ghalgaoui/openrex-manifests.git -b kirkstone -m openrex.xml
$ repo sync
$ MACHINE=openrex-imx6quad DISTRO=openrex-distro source ./setup-environment build
