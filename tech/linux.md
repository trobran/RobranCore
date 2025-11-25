# Linux links



## 
- [22 Best Free and Open Source Linux System Monitoring Tools - LinuxLinks](https://www.linuxlinks.com/best-free-open-source-linux-system-monitoring-tools/)
- [kunai-project/kunai: Threat-hunting tool for Linux](https://github.com/kunai-project/kunai)



## Howtos, tutorials, etc.
- [Recover Data In Linux After Accidentally Deleting Your OS - OSTechNix](https://ostechnix.com/recover-data-in-linux-after-accidentally-deleting-your-os/)


## Installation
[9 Things to Do After Installing Fedora 42 (Post Setup Guide) - Tunnell Vision - TuxDigital](https://tuxdigital.com/videos/9-things-to-do-after-installing-fedora-42-post-setup-guide/)
``` Bash
# update
sudo dnf upgrade

# enable Flathub
flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrepo

# RPM Fusion
sudo dnf install https://download1.rpmfusion.org/free/fedora/rpmfusion-free-release-$(rpm -E %fedora).noarch.rpm https://download1.rpmfusion.org/nonfree/fedora/rpmfusion-nonfree-release-$(rpm -E %fedora).noarch.rpm

# multimedia codecs
sudo dnf install libavcodec-freeworld

```