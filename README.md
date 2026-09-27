## What Is This Repo?

This is essentially my arch s-up dotfiles. Its just my config. I guess I'm the only one who cares about this. Anyways. Here it is:

## What Is Backed Up?

 - bspwm
 - sxhkd
 - kitty
 - Neovim
 - Polybar
 - Rofi
 - Picom
 - .bashrc
 - .bash_profile
 - .bash_logout
 - .xinitrc

## What Is Not Backed Up?

Some files are intentionally excluded because they contain temporary, private, or machin-specific data. Examples includ:

 - SSH private keys
 - .bash_history
 - .Xauthority
 - browser profiles
 - Tailscale credentials
 - personal Git credentials
 - temporary session files

## Package List

The repository contains two package lists:

- package-officials.txt - explicitly installed packages from the official Arch repositories
- package-foreign.txt - packages not provided by the cnfigured official repositories, such as AUR packages (WARNING ;))

## How To Restore 

On a fresh Arch installation:

1. Clone the repository
2. Reinstall the packages from the package list
3. Copy or link the configuration files back to their expected locations
4. Rstore .xinitrc and shell configuration files to the home directory
5. Start or enable the required services and grapical components

This repository is not a complete system backup. It is intended to reproduce the configuration and software setup of the machine

;GLHF! 
