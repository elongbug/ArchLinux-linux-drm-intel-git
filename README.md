### Archlinux Linux Intel DRM Kernels
These are Archlinux custom kernels built from upstream DRM Intel kernel patches.

1. referenced based repository for PKGBUILD: 
   https://aur.archlinux.org/linux-mainline.git

2. drm intel linux kernel repository
   https://cgit.freedesktop.org/drm-intel

### Branches

* drm-intel-fixes
* drm-intel-next
* drm-intel-next-fixes
* drm-intel-next-queued
* drm-intel-testing
* for-linux-next 
* for-linux-next-fixes 
* maintainer-tools
* topic/core-for-CI

### Recommended Install

    git clone https://github.com/elongbug/ArchLinux-linux-drm-intel-git
    git checkout <BRANCH>
    makepkg -s
    sudo pacman -U 'built-package' 
