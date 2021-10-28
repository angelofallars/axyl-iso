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
    - [Xmonad Keybinds](#xmonadkeys)
- [How To Install ⁉️](#install)


<a id="gal"></a>
## Gallery 📷
BSPWM|DWM
--|--
![gif](https://raw.githubusercontent.com/axyl-os/axyl-os.github.io/master/src/img/axyl-bspwm.gif)|![gif](https://raw.githubusercontent.com/axyl-os/axyl-os.github.io/master/src/img/axyl-dwm.gif)

Qtile|Xmonad
--|--
![gif](https://raw.githubusercontent.com/axyl-os/axyl-os.github.io/master/src/img/axyl-qtile.gif)|![gif](https://raw.githubusercontent.com/axyl-os/axyl-os.github.io/master/src/img/axyl-xmonad.gif)


<a id="keybinds"></a>
## Global Keybinds ✍️

|        Keybind         |                 Function                 |
| ---------------------- | ---------------------------------------- |
| `Ctrl + Shft + Q`      | Log Out Session                          |
| `Ctrl + Shft + R`      | Reload Current Session                   |
| `Super + [1..7]`           | Switches to Workspace 1 to 7             |
| `Super + Shft + [1..7]`    | Move Apps/Windows to Workspace 1 to 7    |
| `Ctrl + X`             | Launch Powermenu                         |
| `Super + Enter`            | Launch Terminal (Alacritty)              |
| `Super + C`                | Close/Kill Window                        |
| `Super`                    | Launch j4-dmenu-desktop                  |
| `Super + D`                | Launch dmenu                             |
| `Super + N`                | Launch NetworkManager dmenu              |
| `Alt + E`              | Launch Edit Configs dmenu                |
| `Alt + L`              | Launch Quick Links dmenu                 |
| `Ctrl + Alt + L`       | Lock Screen                              |
| `Super + Shft + W`         | Launch Firefox                           |
| `Super + Shft + F`         | Launch Thunar                            |
| `Super + Shft + R`         | Ranger Quick Launch                      |
| `PrtSc`                | Screenshot                               |
| `Ctrl + PtrSc`         | Screenshot Active Window                 |
| `Ctrl + Alt + PrtSc`   | Screenshot Selected Area                 |


<a id="dwmkeys"></a>
## dwm Keybindings

|        Keybind         |                 Function                 |
| ---------------------- | ---------------------------------------- |
| `Super + B`                | Toggle Bar                               |
| `Super + [J,K]`            | Focus Next/Previous Client               |
| `Super + [H,L]`            | Set Stack Size                           |
| `Super + [T,F,M]`          | Set Client Layout to [Tiled,Floating,Monocle]|
| `Super + Ctrl + comma`     | Cycle Layouts                            |
| `Super + Shft + Space`     | Toggle Floating                          |
| `Super + Shft [J,K]`       | Move Stack/Window [Previous,Next]        |
| `Super + Ctrl + I`         | Increase Overall Gaps                    |
| `Super + Ctrl + Shft + U`  | Decrease Overall Gaps                    |
| `Super + Shft + I`         | Increase Inner Gaps                      |
| `Super + Ctrl + Shft + I`  | Decrease Inner Gaps                      |
| `Super + Ctrl + O`         | Increase Outer Gaps                      |
| `Super + Ctrl + Shft + O`  | Decrease Outer Gaps                      |
| `Super + Ctrl + 6`         | Increase Inner Horizontal Gaps           |
| `Super + Ctrl + Shft + 6`  | Decrease Inner Horizontal Gaps           |
| `Super + Ctrl + 7`         | Increase Inner Vertical Gaps             |
| `Super + Ctrl + Shft + 7`  | Decrease Inner Vertical Gaps             |
| `Super + Ctrl + 8`         | Increase Outer Horizontal Gaps           |
| `Super + Ctrl + Shft + 8`  | Decrease Outer Horizontal Gaps           |
| `Super + Ctrl + 9`         | Increase Outer Vertical Gaps             |
| `Super + Ctrl + Shft + 9`  | Decrease Outer Vertical Gaps             |
| `Super + Ctrl + T`         | Toggle Gaps                              |
| `Super + Ctrl + Shft + D`  | Default Gaps                             |
| `Super + E`                | Hide Window                              |
| `Super + Shft + E`         | Restore Hidden Window                    |


<a id="qtilekeys"></a>
## Qtile Keybindings

|        Keybind         |                 Function                 |
| ---------------------- | ---------------------------------------- |
| `Super + [H,L,J,K]`        | Switch Focus to [Left,Down,Right,Up]     |
| `Super + Shft + [H,L,J,K]` | Move Windows to [Left,Down,Right,Up]     |
| `Super + Ctrl + [H,L,J,K]` | Grow Apps/Windows                        |
| `Super + Ctrl + Enter`     | Toggle Split & Unsplit Sides of Stack    |
| `Super + Tab`              | Toggle Between Layouts                   |


<a id="bspwmkeys"></a>
## BSPWM Keybindings

|        Keybind         |                 Function                 |
| ---------------------- | ---------------------------------------- |
| `Super + Esc`              | Reloads SXHKD Configuration              |
| `Super + Space`            | Alternate Between Tiled & Monocle Layout |
| `Super + Y`                | Send Newest Marked Node To The Newest Preselected Node |
| `Super + G`                | Swap The Current Node And The Biggest Window |
| `Super + Ctrl + [T,S,F]`   | Sets the window state                    |
| `Super + Shft + [Left,Down,Up,Right]` | Send The Window To Another Edge Of The Screen |
| `Alt + Tab`            | Change Focus To Next Window, Including Floating Window |
| `Super + [Left,Down,Up,Right]` | Change Focus To Next Window, Only Tiled Windows|
| `Super + [H,J,K,L]`        | Focus The Node in The Given Direction [West,South,North,East] |


<a id="xmonadkeys"></a>
## Xmonad Keybindings

|        Keybind         |                 Function                 |
| ---------------------- | ---------------------------------------- |
| `Super + Ctrl + O`         | Increase Left Side Gaps                  |
| `Super + Shft + O`         | Decrease Left Side Gaps                  |
| `Super + Ctrl + Y`         | Increase Upper Gaps                      |
| `Super + Shft + Y`         | Decrease Upper Gaps                      |
| `Super + Ctrl + U`         | Increase Bottom Gaps                     |
| `Super + Shft + U`         | Decrease Bottom Gaps                     |
| `Super + Ctrl + I`         | Increase Right Side Gaps                 |
| `Super + Shft + I`         | Decrease Right Side Gaps                 |
| `Super + R`                | Resize viewed windows to the correct size|
| `Super + M`                | Move focus to the Master Window          |
| `Super + S`                | Swap the focused window and the Master Window |
| `Super + T`                | Push Window Back into Tiling             |
| `Super + Space`            | Cycle Layouts                            |
| `Super + Shft + Space`     | Reset layouts on the current workspace to default |
| `Super + Tab`              | Move Focus to the next Window            |
| `Super + [J,K]`            | Move Focus to the [Next,Previous] Window |
| `S + Shft + [J,K]`         | Swap the focused window with the [Next,Previous] Window |
| `Super + [H,L]`            | [Shrink,Expand] The Master Area          |
| `Super + [comma,period]`   | [Increment,Deincrement] the number of windows in the Master Area |


<a id="install"></a>
## Installation
Once you boot up Axyl and entered dwm desktop, you can start the 
Calamares installer by launching `dmenu` by hitting: `Superkey + D` 
on your keyboard and type in: `calinstall`
