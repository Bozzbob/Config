# Dotfiles & Configurations

This repository contains my personal configuration files ("dotfiles") for various Linux programs. It's intended for backup purposes and to quickly set up a new system with my preferred environment.

## 📁 Contents

| Program           | Description                              |
|-------------------|------------------------------------------|
| `bash` / `zsh`     | Shell configuration files               |
| `nvim`            | Neovim setup and plugins                 |
| `git`             | Git configuration (`.gitconfig`)         |
| `i3` / `sway`     | Tiling window manager configs            |
| `alacritty`       | Terminal emulator settings               |
| `rofi`            | App launcher themes and configs          |
| `picom`           | Compositor settings                      |
| `polybar`         | Status bar configuration                 |

> Note: These configs are tailored for **Arch Linux**, but can be adapted for other distros with minor changes.

## 🔧 Usage

Clone the repo and symlink the configs to your home directory:

```bash
git clone git@github.com:Grip9418/dotfiles.git ~/dotfiles
ln -s ~/dotfiles/.bashrc ~/.bashrc
