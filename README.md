<p align="center">
<a href="https://axyl-os.github.io" target="_blank"><img src="archiso/airootfs/usr/share/axyl.png" width="200px" height="auto"/></a>
</p>

<p align="center">
<a href="https://www.paypal.com/donate?hosted_button_id=GTLF6LZ5LRSE4"><img width="32px" src="https://raw.githubusercontent.com/Kungger-git/files/master/imgs/ppal.png" alt="Support my work via Paypal"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Maintained%3F-Yes-Green?style=flat-square">
  <img src="https://img.shields.io/github/downloads/axyl-os/axyl-iso/total?label=downloads&logo=github&color=blue&style=flat-square">
  <img src="https://img.shields.io/github/stars/axyl-os/axyl-iso?style=flat-square">
  <img src="https://img.shields.io/github/issues/axyl-os/axyl-iso?color=violet&style=flat-square">
</p>

<p align="center">
Introducing a new minimal Arch-based GNU/Linux Distribution
</p>

## Table of Contents

- [Gallery 📷](#gal)
- [Global Keybinds ✍️](#keybinds)
    - [dwm Keybinds](#dwmkeys)
    - [Qtile Keybinds](#qtilekeys)
- [How To Install ⁉️](#install)


<a id="gal"></a>
## Gallery 📷
DWM|Qtile
--|--
![gif](https://raw.githubusercontent.com/axyl-os/axyl-os.github.io/master/src/img/axyl-dwm.gif)|![gif](https://raw.githubusercontent.com/axyl-os/axyl-os.github.io/master/src/img/axyl-qtile.gif)

<a id="keybinds"></a>
## Global Keybinds ✍️

|        Keybind         |                 Function                 |
| ---------------------- | ---------------------------------------- |
| `S + [1..7]`           | Switches to Workspace 1 to 7             |
| `S + Shft + [1..7]`    | Move Apps/Windows to Workspace 1 to 7    |
| `Ctrl + X`             | Launch Powermenu                         |
| `S + Enter`            | Launch Terminal (Alacritty)              |
| `S + C`                | Close window                             |
| `S`                    | Launch j4-dmenu-desktop                  |
| `S + D`                | Launch dmenu                             |
| `S + N`                | Launch NetworkManager dmenu              |
| `Alt + E`              | Launch Edit Configs dmenu                |
| `Alt + L`              | Launch Quick Links dmenu                 |
| `Ctrl + Alt + L`       | Lock Screen                              |
| `S + Shft + W`         | Launch Firefox                           |
| `S + Shft + F`         | Launch Thunar                            |
| `S + Shft + R`         | Ranger Quick Launch                      |
| `PrtSc`                | Screenshot                               |
| `Ctrl + PtrSc`         | Screenshot Active Window                 |
| `Ctrl + Alt + PrtSc`   | Screenshot Selected Area                 |


<a id="dwmkeys"></a>
## dwm Keybindings

|        Keybind         |                 Function                 |
| ---------------------- | ---------------------------------------- |
| `Ctrl + Shft + Q`      | Log Out Session                          |
| `S + B`                | Toggle Bar                               |
| `S + [J,K]`            | Focus Next/Previous Client               |
| `S + [H,L]`            | Set Stack Size                           |
| `S + [T,F,M]`          | Set Client Layout to [Tiled,Floating,Monocle]|
| `S + Space`            | Cycle Layouts                            |
| `S + Shft + Space`     | Toggle Floating                          |


<a id="qtilekeys"></a>
## Qtile Keybindings

|        Keybind         |                 Function                 |
| ---------------------- | ---------------------------------------- |
| `Ctrl + Shft + R`      | Reload Qtile                             |
| `Ctrl + Shft + Q`      | Log Out Session                          |
| `S + [H,L,J,K]`        | Switch Focus to [Left,Down,Right,Up]     |
| `S + Shft + [H,L,J,K]` | Move Windows to [Left,Down,Right,Up]     |
| `S + Ctrl + [H,L,J,K]` | Grow Apps/Windows                        |
| `S + Shft + Enter`     | Toggle Split & Unsplit Sides of Stack    |
| `S + Tab`              | Toggle Between Layouts                   |


<a id="install"></a>
## Installation
Once you boot up Axyl and entered dwm desktop, you can start the 
Calamares installer by launching `dmenu` by hitting: `Superkey + D` 
on your keyboard and type in: `calinstall`
