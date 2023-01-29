$ mkdir openrex_workspace__
$ cd openrex_workspace__

$ repo init -u  https://github.com/Ghalgaoui/openrex-manifests.git -b kirkstone -m openrex.xml __
$ repo sync __
$ MACHINE=openrex-imx6quad DISTRO=openrex-distro source ./setup-environment build__
