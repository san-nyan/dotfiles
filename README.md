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
waybar
```

```
$ pacman -S git stow hyprland hyprlock kitty python waybar
$ sudo pip3 install pywal
```


## Installation

First, check out the dotfiles repo in your $HOME directory using git

```
$ git clone git@github.com/san-nyan/dotfiles.git
$ cd pawdotfiles
```

then use GNU stow to create symlinks

```
$ stow .
```
