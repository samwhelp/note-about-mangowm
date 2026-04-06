---
title: 鍵盤按鍵綁定一覽表
nav_order: 9010
has_children: false
parent: 一覽表
---


# 鍵盤按鍵綁定一覽表


## Mango / Keybind




## Subject

* [Config File](#config-file)
* [System](#system)
* [Overview](#overview)
* [Application](#application)
* [Window](#window)
* [Layout](#layout)
* [Tag](#tag)
* [Screenshot](#screenshot)
* [Brightness](#brightness)
* [Volume](#volume)




## Config File

| Config File |
| ----------- |
| [~/.config/mango/config.conf](https://github.com/samwhelp/mango-config/blob/mykeybind/config.conf) |
| [~/.config/mango/env.conf](https://github.com/samwhelp/mango-config/blob/mykeybind/env.conf) |
| [~/.config/mango/bind.conf](https://github.com/samwhelp/mango-config/blob/mykeybind/bind.conf) |
| [~/.config/mango/rule.conf](https://github.com/samwhelp/mango-config/blob/mykeybind/rule.conf) |
| [~/.config/mango/monitor.conf](https://github.com/samwhelp/mango-config/blob/mykeybind/monitor.conf) |
| [~/.config/mango/tag.conf](https://github.com/samwhelp/mango-config/blob/mykeybind/tag.conf) |
| [~/.config/mango/autostart.sh](https://github.com/samwhelp/mango-config/blob/mykeybind/autostart.sh) |




## System

| Keybind                    | Action                      | Command                               |
| -------------------------- | --------------------------- | ------------------------------------- |
| `Alt + Shift + x`          | Exit                        | spawn `wlogout`                       |
| `Alt + Ctrl + x`           | Logout                      | `quit`                                |
| `Alt + Ctrl + Delete`      | Logout                      | `quit`                                |

> run `yay -Sy --needed wlogout` to install `wlogout`


| Keybind                    | Action                      | Command                               |
| -------------------------- | --------------------------- | ------------------------------------- |
| `Alt + Shift + z`          | Lock                        | spawn `swaylock`                      |


| Keybind                    | Action                      | Command                               |
| -------------------------- | --------------------------- | ------------------------------------- |
| `Alt + Ctrl + l`           | Lock                        | spawn `swaylock`                      |

> run `yay -Sy --needed swaylock` to install `swaylock`




## Overview

| Keybind                    | Action                      | Command                               |
| -------------------------- | --------------------------- | ------------------------------------- |
| `Super + v`                | Overview                    | `toggleoverview`                      |
| `Alt + Tab`                | Overview                    | `toggleoverview`                      |




## Application


### Application / Launcher

| Keybind                    | Action                      | Command                               |
| -------------------------- | --------------------------- | ------------------------------------- |
| `Alt + Shift + d`          | Launcher drun               | spawn `rofi -show drun`               |
| `Alt + Shift + r`          | Launcher run                | spawn `rofi -show run`                |


### Application / Terminal

| Keybind                    | Action                      | Command                               |
| -------------------------- | --------------------------- | ------------------------------------- |
| `Alt + Enter`              | Terminal                    | spawn `xfce4-terminal`                |
| `Alt + Shift + a`          | Terminal                    | spawn `xfce4-terminal`                |
| `Alt + Ctrl + a`           | Terminal                    | spawn `foot`                          |
| `Alt + Shift + t`          | Terminal                    | spawn `sakura`                        |
| `Alt + Ctrl + t`           | Terminal                    | spawn `kitty`                         |


### Application / Favorite

| Keybind                    | Action                      | Command                               |
| -------------------------- | --------------------------- | ------------------------------------- |
| `Alt + Shift + f`          | File Manager                | spawn `thunar`                        |
| `Alt + Shift + g`          | File Manager                | spawn `pcmanfm`                       |
| `Alt + Shift + e`          | Text Editor                 | spawn `mousepad`                      |
| `Alt + Shift + b`          | Web Browser                 | spawn `firefox --new-tab about:blank` |
| `Alt + Shift + v`          | Volume Control              | spawn `pavucontrol`                   |
| `Alt + Shift + n`          | Network Connection          | spawn `kitty --class 'nmtui' --title 'Network Settings' nmtui`  |




## Window


### Window / Close

| Keybind                    | Action                      | Command                               |
| -------------------------- | --------------------------- | ------------------------------------- |
| `Super + q`                | Window Close                | `killclient`                          |
| `Alt + F4`                 | Window Close                | `killclient`                          |


### Window / Fullscreen

| Keybind                    | Action                      | Command                               |
| -------------------------- | --------------------------- | ------------------------------------- |
| `Super + f`                | Window Toggle Fullscreen    | `togglefullscreen`                    |


### Window / Move

> Switch to floating, and move.

| Keybind                    | Action                      | Command                               |
| -------------------------- | --------------------------- | ------------------------------------- |
| `Super + Shift + Up`       | Window Move                 | `movewin,+0,-50`                      |
| `Super + Shift + Down`     | Window Move                 | `movewin,+0,+50`                      |
| `Super + Shift + Left`     | Window Move                 | `movewin,-50,+0`                      |
| `Super + Shift + Right`    | Window Move                 | `movewin,+50,+0`                      |


### Window / Resize

> Switch to floating, and resize.

| Keybind                    | Action                      | Command                               |
| -------------------------- | --------------------------- | ------------------------------------- |
| `Super + Ctrl + Up`        | Window Resize               | `resizewin,+0,-50`                    |
| `Super + Ctrl + Down`      | Window Resize               | `resizewin,+0,+50`                    |
| `Super + Ctrl + Left`      | Window Resize               | `resizewin,-50,+0`                    |
| `Super + Ctrl + Right`     | Window Resize               | `resizewin,+50,+0"`                   |


### Window / Floating or Tiling

| Keybind                    | Action                      | Command                               |
| -------------------------- | --------------------------- | ------------------------------------- |
| `Super + Escape`           | Window Toggle Floating      | `togglefloating                       |
| `Alt + backslash`          | Window Toggle Floating      | `togglefloating                       |

| Mousebind                  | Action                      | Command                               |
| -------------------------- | --------------------------- | ------------------------------------- |
| `Super + MiddleClick`      | Window Toggle Floating      | `togglefloating                       |


### Window / Focus

| Keybind                    | Action                      | Command                               |
| -------------------------- | --------------------------- | ------------------------------------- |
| `Super + a`                | Window Focus Prev           | `focusstack,prev`                     |
| `Super + s`                | Window Focus Next           | `focusstack,next`                     |
| `Super + z`                | Window Focus Next           | `focuslast`                           |


| Keybind                    | Action                      | Command                               |
| -------------------------- | --------------------------- | ------------------------------------- |
| `Super + Up`               | Window Focus Prev           | `focusdir,up`                         |
| `Super + Down`             | Window Focus Next           | `focusdir,down`                       |
| `Super + Left`             | Window Focus Prev           | `focusdir,left`                       |
| `Super + Right`            | Window Focus Next           | `focusdir,right`                      |


| Keybind                    | Action                      | Command                               |
| -------------------------- | --------------------------- | ------------------------------------- |
| `Super + k`                | Window Focus Prev           | `focusdir,up`                         |
| `Super + j`                | Window Focus Next           | `focusdir,down`                       |
| `Super + h`                | Window Focus Prev           | `focusdir,left`                       |
| `Super + l`                | Window Focus Next           | `focusdir,right`                      |


### Window / Swap

| Keybind                    | Action                      | Command                               |
| -------------------------- | --------------------------- | ------------------------------------- |
| `Super + grave`            | Window Swap Prev           | `exchange_stack_client,prev`           |
| `Super + Tab`              | Window Swap Next           | `exchange_stack_client,next`           |

> grave means `

| Keybind                    | Action                      | Command                               |
| -------------------------- | --------------------------- | ------------------------------------- |
| `Super + Shift + k`        | Window Swap Prev            | `exchange_client,up`                  |
| `Super + Shift + j`        | Window Swap Next            | `exchange_client,down`                |
| `Super + Shift + h`        | Window Swap Prev            | `exchange_client,left`                |
| `Super + Shift + l`        | Window Swap Next            | `exchange_client,right`               |




## Layout

### Layout / Switch / Cycle

| Keybind                    | Action                      | Command                               |
| -------------------------- | --------------------------- | ------------------------------------- |
| `Super + Shift + c`        | Layout Switch Prev          | `switch_layout,prev`                  |
| `Super + c`                | Layout Switch Next          | `switch_layout,next`                  |


### Layout / Switch / Specific

| Keybind                    | Action                      | Command                               |
| -------------------------- | --------------------------- | ------------------------------------- |
| `Super + Alt + t`          | Layout Switch To Tile       | `setlayout,tile`                      |
| `Super + Alt + s`          | Layout Switch To Scroller   | `setlayout,scroller`                  |
| `Super + Alt + m`          | Layout Switch To Monocle    | `setlayout,monocle`                   |
| `Super + Alt + g`          | Layout Switch To Grid       | `setlayout,grid`                      |
| `Super + Alt + c`          | Layout Switch To Grid       | `setlayout,center_tile`               |
| `Super + Alt + r`          | Layout Switch To Grid       | `setlayout,right_tile`                |


### Layout / On Tile

| Keybind                    | Action                      | Command                               |
| -------------------------- | --------------------------- | ------------------------------------- |
| `Super + d`                | Swap To Mastar              | `zoom`                                |
| `Super + i`                | Increase Mastar Number      | `incnmaster,1`                        |
| `Super + u`                | Decrease Mastar Number      | `incnmaster,-1`                       |


### Layout / On Scroller

| Keybind                    | Action                      | Command                               |
| -------------------------- | --------------------------- | ------------------------------------- |
| `Super + m`                | Column Scale                | `switch_proportion_preset`            |
| `Super + Shift + m`        | Column Scale                | `set_proportion,1.0`                  |


## Screenshot

| Keybind                    | Action                      | Command                               |
| -------------------------- | --------------------------- | ------------------------------------- |
| `Print`                    | Screenshot Fullscreen       | `xfce4-screenshooter --fullscreen`    |
| `Super + Print`            | Screenshot Window           | `xfce4-screenshooter --window`        |
| `Ctrl + Print`             | Screenshot Region           | `xfce4-screenshooter --region`        |
| `Alt + Print`              | Screenshot Alternative      | `xfce4-screenshooter`                 |

> `xfce4-screenshooter --window` is not supported in Wayland.

> run `sudo pacman -Sy --needed xfce4-screenshooter` to install `xfce4-screenshooter`




## Brightness

| Keybind                    | Action                      | Command                               |
| -------------------------- | --------------------------- | ------------------------------------- |
| `XF86MonBrightnessDown`    | Brightness Up               | spawn `brightnessctl set +5%`         |
| `XF86MonBrightnessUp`      | Brightness Down             | spawn `brightnessctl set 5%-`         |

> run `sudo pacman -Sy --needed brightnessctl` to install `brightnessctl`




## Volume

| Keybind                    | Action                      | Command                               |
| -------------------------- | --------------------------- | ------------------------------------- |
| `XF86AudioMute`            | Volume Mute                 | spawn `pamixer --toggle-mute`         |
| `XF86AudioRaiseVolume`     | Volume Up                   | spawn `pamixer -i 5`                  |
| `XF86AudioLowerVolume`     | Volume Down                 | spawn `pamixer -d 5`                  |

> run `sudo pacman -Sy --needed pamixer` to install `pamixer`
