$ mkdir openrex_workspace<br>
$ cd openrex_workspace<br>

$ repo init -u  https://github.com/Ghalgaoui/openrex-manifests.git -b kirkstone -m openrex.xml<br>
$ repo sync<br>
$ MACHINE=openrex-imx6quad DISTRO=openrex-distro source ./setup-environment build<br>
