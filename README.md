# This setup uses [GNU Stow](https://www.gnu.org/software/stow/) to create symlinks into your config directory and it requires the folder structure inside the root folder to be the same as how it would be in your user folder. 
# For example if you want something to link to `~/.config/hypr` you need to make changes in the folder `dotfiles/.config/hypr`



## Requirements

Ensure you have the following installed on your system

```
git
stow
hyprland
hyprlock
kitty
python
pywal
pipewire
pipewire-pulse
libpulse
waybar
```

```
$ pacman -S git stow hyprland hyprlock kitty pipewire pipwire-pulse libpulse python waybar
$ sudo pip3 install pywal
```


## Installation

First, check out the dotfiles repo in your $HOME directory using git

```
$ git clone git@github.com/san-nyan/dotfiles.git
$ cd dotfiles
```

then use GNU stow to create symlinks

```
$ stow .
```
