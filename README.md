# My dotfiles

This directory contains the dotfiles for my system
## Requirements

Ensure you have the following installed on your system
### Git

```sh
pacman -S git
```

### Stow

```sh
pacman -S stow
```

## Installation

First, check out the dotfiles repo in your $HOME directory using git

```sh
git clone https://github.com/aura-zero/dotfiles.git
cd dotfiles
```

then use GNU stow to create symlinks

```sh
stow .
```
**if incounter some error in `stow .` then run**
```sh
stow --adopt .
```

## System Setup with usefull packages
Installation of packages for development and general purpose use
```sh
cd dotfiles/scripts
bash install.sh
```

