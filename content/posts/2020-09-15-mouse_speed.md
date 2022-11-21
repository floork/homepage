---
title: "Linux Mouse speed"
date: 2020-09-15T11:30:03+00:00
tags: ["linux", "mouse speed"]
author: "Me"
---

This is just a simple script to change the scrolling wheel speed<br	>
To use it you just have to run:
## for Arch
```sh
sudo pacman -S --noconfirm --needed imwheel zenity && curl -s -L https://raw.githubusercontent.com/floork/mouse-speed/main/speed.sh | bash
```
## for Fedora
```sh
sudo dnf -y imwheel zenity && curl -s -L https://raw.githubusercontent.com/floork/mouse-speed/main/speed.sh | bash
```
## for Debian / Ubuntu
```sh
sudo apt -y install imwheel zenity && curl -s -L https://raw.githubusercontent.com/floork/mouse-speed/main/speed.sh | bash
```
