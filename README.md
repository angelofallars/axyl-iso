<p align="center">
<a href="https://axyl-os.github.io" target="_blank"><img src="archiso/airootfs/usr/share/axyl.png" width="250px" height="auto"/></a>
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
    - [BSPWM Keybinds](#bspwmkeys)
- [How To Install ⁉️](#install)


<a id="gal"></a>
## Gallery 📷
DWM|Qtile|BSPWM
--|--|--
![gif](https://raw.githubusercontent.com/axyl-os/axyl-os.github.io/master/src/img/axyl-dwm.gif)|![gif](https://raw.githubusercontent.com/axyl-os/axyl-os.github.io/master/src/img/axyl-qtile.gif)|![gif](https://raw.githubusercontent.com/axyl-os/axyl-os.github.io/master/src/img/axyl-bspwm.gif)


<a id="keybinds"></a>
## Global Keybinds ✍️

|        Keybind         |                 Function                 |
| ---------------------- | ---------------------------------------- |
| `Ctrl + Shft + Q`      | Log Out Session                          |
| `Ctrl + Shft + R`      | Reload Current Session                   |
| `S + [1..7]`           | Switches to Workspace 1 to 7             |
| `S + Shft + [1..7]`    | Move Apps/Windows to Workspace 1 to 7    |
| `Ctrl + X`             | Launch Powermenu                         |
| `S + Enter`            | Launch Terminal (Alacritty)              |
| `S + C`                | Close/Kill Window                        |
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
| `S + B`                | Toggle Bar                               |
| `S + [J,K]`            | Focus Next/Previous Client               |
| `S + [H,L]`            | Set Stack Size                           |
| `S + [T,F,M]`          | Set Client Layout to [Tiled,Floating,Monocle]|
| `S + Ctrl + comma`     | Cycle Layouts                            |
| `S + Shft + Space`     | Toggle Floating                          |
| `S + Shft [J,K]`       | Move Stack/Window [Previous,Next]        |
| `S + Ctrl + I`         | Increase Overall Gaps                    |
| `S + Ctrl + Shft + U`  | Decrease Overall Gaps                    |
| `S + Shft + I`         | Increase Inner Gaps                      |
| `S + Ctrl + Shft + I`  | Decrease Inner Gaps                      |
| `S + Ctrl + O`         | Increase Outer Gaps                      |
| `S + Ctrl + Shft + O`  | Decrease Outer Gaps                      |
| `S + Ctrl + 6`         | Increase Inner Horizontal Gaps           |
| `S + Ctrl + Shft + 6`  | Decrease Inner Horizontal Gaps           |
| `S + Ctrl + 7`         | Increase Inner Vertical Gaps             |
| `S + Ctrl + Shft + 7`  | Decrease Inner Vertical Gaps             |
| `S + Ctrl + 8`         | Increase Outer Horizontal Gaps           |
| `S + Ctrl + Shft + 8`  | Decrease Outer Horizontal Gaps           |
| `S + Ctrl + 9`         | Increase Outer Vertical Gaps             |
| `S + Ctrl + Shft + 9`  | Decrease Outer Vertical Gaps             |
| `S + Ctrl + T`         | Toggle Gaps                              |
| `S + Ctrl + Shft + D`  | Default Gaps                             |
| `S + E`                | Hide Window                              |
| `S + Shft + E`         | Restore Hidden Window                    |




<a id="qtilekeys"></a>
## Qtile Keybindings

|        Keybind         |                 Function                 |
| ---------------------- | ---------------------------------------- |
| `S + [H,L,J,K]`        | Switch Focus to [Left,Down,Right,Up]     |
| `S + Shft + [H,L,J,K]` | Move Windows to [Left,Down,Right,Up]     |
| `S + Ctrl + [H,L,J,K]` | Grow Apps/Windows                        |
| `S + Shft + Enter`     | Toggle Split & Unsplit Sides of Stack    |
| `S + Tab`              | Toggle Between Layouts                   |


<a id="bspwmkeys"></a>
## BSPWM Keybindings

|        Keybind         |                 Function                 |
| ---------------------- | ---------------------------------------- |
| `S + Esc`              | Reloads SXHKD Configuration              |
| `S + Space`            | Alternate Between Tiled & Monocle Layout |
| `S + Y`                | Send Newest Marked Node To The Newest Preselected Node |
| `S + G`                | Swap The Current Node And The Biggest Window |
| `S + Ctrl + [T,S,F]`   | Sets the window state                    |
| `S + Shft + [Left,Down,Up,Right]` | Send The Window To Another Edge Of The Screen |
| `Alt + Tab`            | Change Focus To Next Window, Including Floating Window |
| `S + [Left,Down,Up,Right]` | Change Focus To Next Window, Only Tiled Windows|
| `S + [H,J,K,L]`        | Focus The Node in The Given Direction [West,South,North,East] |


<a id="install"></a>
## Installation
Once you boot up Axyl and entered dwm desktop, you can start the 
Calamares installer by launching `dmenu` by hitting: `Superkey + D` 
on your keyboard and type in: `calinstall`
