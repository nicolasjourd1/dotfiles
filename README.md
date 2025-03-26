# dotfiles
Dotfiles repository, using [GNU stow](https://www.gnu.org/software/stow/).

## Installation
Clone this repository in your home directory. Each module (e.g. hypr, kitty) can be "installed" with 
```{sh}
~/dotfiles $ stow <module>
```

## Modules

| name  | description              | depends on |
| ----- | ------------------------ | ---------- |
| dwm   | files required using dwm |
| kitty | kitty terminal config    |
| hypr  | hyprland config          | kitty      |