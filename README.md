<p align="center">
<a href="https://axyl-os.github.io" target="_blank"><img src="https://raw.githubusercontent.com/axyl-os/axyl-os.github.io/master/assets/img/axyl-logo.svg" width="250px" height="auto"/></a>
</p>

<p align="center">
<a href="https://www.paypal.com/donate?hosted_button_id=GTLF6LZ5LRSE4"><img width="32px" src="https://raw.githubusercontent.com/Kungger-git/files/master/imgs/ppal.png" alt="Support my work via Paypal"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Maintained%3F-Yes-CD8335?style=flat-square">
  <img src="https://img.shields.io/github/downloads/axyl-os/axyl-iso/total?label=Downloads&logo=github&color=6EA340&style=flat-square">
  <img src="https://img.shields.io/github/stars/axyl-os/axyl-iso?label=Stars&color=4C87C1&style=flat-square">
  <img src="https://img.shields.io/github/issues/axyl-os/axyl-iso?color=87599A&style=flat-square">
</p>

<h1 align="center">
  Welcome to Axyl.
</h1>

<p align="center">
Introducing a new minimal Arch Linux-based distro.<br>
Axyl focuses fully on tiling WMs. Level up your productivity with i3, bspwm, dwm and more.
</p>

<p align="center">
  <a href="https://github.com/axyl-os/axyl-iso/releases">
    <img src="https://raw.githubusercontent.com/angelofallars/axyl-assets/main/download-now.svg" height=60px>
  </a>
</p>

<p align="center">
  <a href="https://axyl-os.github.io/">
    <img src="https://img.shields.io/badge/Learn_More-h?color=1B5488&style=for-the-badge">
  </a>
  <a href="https://discord.gg/qAXMkQdwjj">
    <img src="https://img.shields.io/badge/JOIN_THE_AXYL_SERVER-%23586AA8.svg?style=for-the-badge&logo=discord&logoColor=white">
  </a>
</p>

<br><br>

<p align="center">
  <img src="https://raw.githubusercontent.com/angelofallars/axyl-assets/main/i3-shadows.svg" alt="i3" width=90px>
  <img src="https://axyl-os.github.io/assets/img/window-managers/bspwm.svg" alt="bspwm" width=90px>
  <img src="https://raw.githubusercontent.com/angelofallars/axyl-assets/main/dwm-shadows.svg" alt="dwm" width=90px>
</p>

## Contents

- [📷 At First Glance](#gal)
- [🎁 Installation](#install)
- [❓ Getting Help](#techsupport)
- [✍️ Global Keybinds](#keybinds)
    - [BSPWM Keybinds](#bspwmkeys)
    - [dwm Keybinds](#dwmkeys)
    - [Xmonad Keybinds](#xmonadkeys)
    - [Qtile Keybinds](#qtilekeys)

<a id="gal"></a>
## 📷 At First Glance

<div align=center>
  <h3>i3 <em>(the default desktop)</em></h3>
  <img src="https://raw.githubusercontent.com/angelofallars/axyl-assets/main/i3-shadows.svg" alt="i3" width=70px>
</div>

![image](https://user-images.githubusercontent.com/39676098/141485970-bc75299d-4e08-43d6-83c0-1472b4306a90.png)

BSPWM <br><img src="https://axyl-os.github.io/assets/img/window-managers/bspwm.svg" alt="bspwm" width=50px>|DWM <br><img src="https://raw.githubusercontent.com/angelofallars/axyl-assets/main/dwm-shadows.svg" alt="dwm" width=50px>
--|--
![gif](https://raw.githubusercontent.com/axyl-os/axyl-os.github.io/master/assets/img/axyl-bspwm.gif)|![gif](https://raw.githubusercontent.com/axyl-os/axyl-os.github.io/master/assets/img/axyl-dwm.gif)

Qtile|XMonad <br><img src="https://axyl-os.github.io/assets/img/window-managers/xmonad.svg" alt="XMonad" width=50px>
--|--
![gif](https://raw.githubusercontent.com/axyl-os/axyl-os.github.io/master/assets/img/axyl-qtile.gif)|![gif](https://raw.githubusercontent.com/axyl-os/axyl-os.github.io/master/assets/img/axyl-xmonad.gif)

<p align=center><a href="https://axyl-os.github.io">Learn More About Axyl</a></p>

<a id="install"></a>
## 🎁 Installation
<img src="https://user-images.githubusercontent.com/39676098/141447471-75b2f8ee-43dd-4c0b-ac59-a3964ed618d8.png" align=right width=400px>

[Download](https://github.com/axyl-os/axyl-iso/releases) the latest Axyl release from the Releases section.

Once you've downloaded the `.iso` file, flash the `.iso` into a portable drive, like a flash drive. We recommend using [balenaEtcher](https://www.balena.io/etcher/) for this task, available on Windows, Linux and macOS.

Then, boot from the flash drive from the BIOS/UEFI.

When you boot up Axyl, you will be greeted by a welcome screen to install the OS. You can install right away, or just try out Axyl in the live boot.

Axyl's default window manager is i3. You can install up to seven window managers from the ISO.

Axyl offers several window managers:
- i3
- bspwm
- dwm
- XMonad
- Qtile
- leftwm
- spectrwm

<a id="techsupport"></a>
## ❓ Getting Help

Axyl is built on top of Arch Linux. For documentation on [pacman](https://wiki.archlinux.org/title/Pacman), how to install packages, and other tasks refer to the [Arch Linux Wiki](https://wiki.archlinux.org/).

If you need help or tech support for your Axyl installation, feel free to file an issue in our [issue tracker](https://github.com/axyl-os/axyl-iso/issues) so we can assist you.

You may also join Axyl's [Discord server](https://discord.gg/qAXMkQdwjj) to ask for tech support and general inquiries.

<a id="keybinds"></a>
## ✍️ Global Keybinds

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


<a id="bspwmkeys"></a>
## bspwm Keybindings

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


<a id="xmonadkeys"></a>
## XMonad Keybindings

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


<a id="qtilekeys"></a>
## Qtile Keybindings

|        Keybind         |                 Function                 |
| ---------------------- | ---------------------------------------- |
| `Super + [H,L,J,K]`        | Switch Focus to [Left,Down,Right,Up]     |
| `Super + Shft + [H,L,J,K]` | Move Windows to [Left,Down,Right,Up]     |
| `Super + Ctrl + [H,L,J,K]` | Grow Apps/Windows                        |
| `Super + Ctrl + Enter`     | Toggle Split & Unsplit Sides of Stack    |
| `Super + Tab`              | Toggle Between Layouts                   |
