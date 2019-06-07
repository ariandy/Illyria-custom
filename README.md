# Illyria-custom
My Manjaro i3 18.04 custom log on ASUS e202S (UEFI)

## Installation : Partition settings
- Totally Erased Harddisk
- Switched from MBR to GPT
- Auto-partition installation

## Post-Installation
- Disable `Launch at start` Manjaro Hello
- `sudo pacman -Syu`
- Change wallpaper via `nitrogen`
- Change login-background via `lightdm-settings`

## Enable AUR
- morc_menu > Settings > Add/remove software > ... > Preferences > AUR > Enable AUR support

## Install Snap Store app
- [Install snapd](https://docs.snapcraft.io/installing-snap-on-manjaro-linux)
- [Install Snap Store](https://docs.snapcraft.io/installing-snap-store-app)

## Installed via Snap Store
- github-desktop
- sublime

## Timeshift
- morc_menu > Settings > Add/remove software > Search > Timeshift

## Redshift
- `sudo pacman -S redshift`

## Neofetch
- `sudo pacman -S neofetch`

## Rust
- [Using rustup](https://www.rust-lang.org/tools/install)

## Oh-My-Zsh + PowerLevel9K

## CUPS
- `sudo pacman -S trizen base-devel --needed`
- Install ALL
- `trizen -S cnijfilter-ip2700series --noconfirm`
- Configuration page : http://localhost:631/
