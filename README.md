# Murali's Dotfiles

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![Platforms: Linux](https://img.shields.io/badge/Platform-Linux-orange.svg)

Personal configuration files for various tools and applications, organized for easy management with [GNU Stow](https://www.gnu.org/software/stow/).

---

## Quick Install

Clone the repository and stow the configs you want:

```bash
git clone git@github.com:Murali2602/dotfiles.git ~/dotfiles
cd ~/dotfiles

# Example: symlink all configs you use
stow btop
stow fish
stow fastfetch
stow foot
stow hypr
stow uwsm
stow starship
```
Configs will be symlinked into your `~/.config` or relevant directories. Only stow the apps you actively use to avoid conflicts.

## Included Configurations

| Application | Description                             |
| ----------- | --------------------------------------- |
| btop        | Terminal resource monitor configuration and themes |
| fish        | Fish shell configuration, functions, and completions |
| fastfetch   | Fastfetch system info display config    |
| foot        | Foot terminal emulator settings         |
| hypr        | Hyprland window manager configs, scripts, and variables |
| uwsm        | Universal Workspace Manager settings    |
| starship    | Starship prompt configuration           |

Other symlinked configs exist for apps I use daily. Unused apps are excluded to prevent conflicts.

## Notes

*   Intended for Linux (Arch Linux tested).
*   Hidden files in app folders are included where necessary.
*   `.git` folders inside configs are ignored by Git.
*   Only symlink actively used configs.

## Contributing

This is a personal repository, but pull requests are welcome for improvements or fixes.
