# alis

![Arch Linux](https://raw.githubusercontent.com/picodotdev/alis/master/images/archlinux-badge.svg)
![Bash](https://raw.githubusercontent.com/picodotdev/alis/master/images/sh-bash-badge.svg)

Arch Linux Install Script (or alis, also known as _the Arch Linux executable installation guide and wiki_) installs unattended, automated and customized Arch Linux system. Customised by optevo.

## To customise this yourself

- Update GITHUB_USER in download.sh
- Update alis.conf
- Modify any of the scripts as desired

## System installation

Download and boot from the latest <a href="https://www.archlinux.org/download/">original Arch Linux installation media</a>. After boot use the commands below to start the installation.

Follow the <a href="https://wiki.archlinux.org/title/Arch_Linux">Arch Way</a> of doing things and learn what this script does. This will allow you to know what is happening.

The original script has been customised to install a development environment.

WARNING - executing the script alis.sh will immediatelly reformat the disk and install Arch Linux according to the script and configuration.


```
#                         # Start the system with latest Arch Linux installation media
# loadkeys [keymap]       # Load keyboard keymap, eg. loadkeys us, loadkeys es, loadkeys de
# curl -sL https://raw.githubusercontent.com/optevo/alis/master/download.sh | bash     # Download alis scripts
# vim alis.conf           # Edit configuration and change variables values with your preferences (system configuration)
# ./alis.sh               # Start installation
```
