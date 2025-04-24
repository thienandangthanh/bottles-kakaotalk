# KaKaoTalk on linux

## Dependencies
- flatpak
- Bottles

## Guide

### Install Flatpak

```sh
sudo pacman -S flatpak
```

### Install Bottles

```sh
flatpak install com.usebottles.bottles
```

### Create KakaoTalk Bottle

#### Use configuration file

Import the configuration file `kakao.yml` in this repo.

For more detail, read this official instruction [Bottles - Backups & Duplicate](https://docs.usebottles.com/bottles/backups)

#### Start fresh

Runner: `soda-9.0-1`
DXVK: `dxvk-2.6.1`
VKD3D: `vkd3d-proton-2.14.1`
DXVK NVAPI: `dxvk-nvapi-v0.8.0`
LatencyFleX: `latencyflex-v0.1.1`
Windows version: `Windows 10`

Install dependencies:
- mono
- gecko
- d3dx11
- gdiplus
- cjkfonts
- allfonts

## References
- [Arch Wiki - Flatpak](https://wiki.archlinux.org/title/Flatpak)
- [Flathub - Bottles](https://flathub.org/apps/com.usebottles.bottles)
- [Bottles - Installation](https://docs.usebottles.com/getting-started/installation)

## Similar projects
- https://github.com/jeonghanlee/kakaotalk-env
- https://github.com/kimlulz/Katalk_linux
