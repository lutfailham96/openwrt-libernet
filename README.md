# OpenWRT Libernet
OpenWRT with pre-installed Libernet for Amlogic S905X devices such as HG680P, B860H, etc.

## Basic Information
- Router IP : 192.168.1.1
- WiFi SSID : Libernet

## Features
- Pre-installed Libernet v1.5.3

## Burning to MicroSD Card (Linux)
- Download latest release image
- Extract image
```sh
tar -xJvpf image_name.img.tar.xz
```
- Burn to MicroSD Card, replace sdX to MicroSD device path
```sh
dd if=image_name.img of=/dev/sdX bs=4M status=progress
```

## Burning to MicroSD Card (Windows)
- Download latest release image
- Burn to MicroSD Card using Rufus or Balena Etcher

## Resize Root File System
- On Linux, you can use gparted
- Windows, you can use AOMEI Partition Assistant or MiniTool Partition Wizard
