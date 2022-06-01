# alis

![Arch Linux](https://raw.githubusercontent.com/picodotdev/alis/master/images/archlinux-badge.svg)
![Bash](https://raw.githubusercontent.com/picodotdev/alis/master/images/sh-bash-badge.svg)

Arch Linux Install Script (or alis, also known as _the Arch Linux executable installation guide and wiki_) installs unattended, automated and customized Arch Linux system.

Customised by optevo.

## To modify

Update GITHUB_USER in download.sh
Update alis.conf

## System installation

Download and boot from the latest <a href="https://www.archlinux.org/download/">original Arch Linux installation media</a>. After boot use the following commands to start the installation.

Follow the <a href="https://wiki.archlinux.org/title/Arch_Linux">Arch Way</a> of doing things and learn what this script does. This will allow you to know what is happening.

Internet connection is required, with wireless WIFI connection see <a href="https://wiki.archlinux.org/title/Wireless_network_configuration#Wi-Fi_Protected_Access">Wireless_network_configuration</a> to bring up WIFI connection before start the installation.

Minimum usage

```
#                         # Start the system with latest Arch Linux installation media
# loadkeys [keymap]       # Load keyboard keymap, eg. loadkeys us, loadkeys es, loadkeys de
# curl -sL https://raw.githubusercontent.com/optevo/alis/master/download.sh | bash     # Download alis scripts
# vim alis.conf           # Edit configuration and change variables values with your preferences (system configuration)
# ./alis.sh               # Start installation
```
