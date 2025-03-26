# dotfiles
Dotfiles repository, using [GNU stow](https://www.gnu.org/software/stow/).

## Installation
Clone this repository in your home directory. Each module (e.g. hypr, kitty, ...) can be "installed" with 
```shell
~/dotfiles $ stow <module>
```

## Modules

| name  | description              | depends on |
| ----- | ------------------------ | ---------- |
| base | general purpose files |
| hypr  | hyprland config          | kitty, base      |
| dwm   | files required when using dwm | base
| kitty | kitty terminal config    | base