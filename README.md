# KDE Linux Bootc, verry horrible

```
git clone https://invent.kde.org/renneroe/kde-linux

git switch no-pacman-fuckery

sudo ./build_docker.sh

mkdir -p rootfs
fsck.erofs --extract=rootfs kde-linux_202601012212_root-x86-64.erofs

just build-containerfile

just generate-bootable-image
```
