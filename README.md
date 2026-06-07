<div align="center">

<img src="https://i.ibb.co/k4PbLjv/dotfiles.png" alt="Catppuccin Mocha i3 Dotfiles" width="900">

# Catppuccin Mocha i3 Dotfiles

A clean and lightweight i3 configuration built around the Catppuccin Mocha color palette.

Designed for everyday use with an emphasis on consistency, performance, and simplicity.

<img src="https://img.shields.io/github/stars/user7210unix/dotfiles?style=for-the-badge">
<img src="https://img.shields.io/github/forks/user7210unix/dotfiles?style=for-the-badge">

</div>

---

## Overview

This repository contains my personal i3wm configuration and related desktop customizations.

The setup aims to provide:

- A consistent Catppuccin Mocha theme
- A clean and minimal desktop environment
- Fast startup and low resource usage
- Practical defaults for daily use

---

## Screenshot

<p align="center">
  <img src="https://github.com/lashchilin-andrii/i3wm-dotfiles/raw/screenshots/screenshots/fastfetch.png?raw=true" width="900">
</p>

---

## Dependencies

All required packages and dependencies are listed in:

**[packages.md](packages.md)**

---

### Neovim

```bash
git clone https://github.com/tonybanters/nvim ~/.config/nvim
```
---

### Font

```bash
mkdir ~/.fonts && cd ~/.fonts && wget https://github.com/ryanoasis/nerd-fonts/releases/download/v3.4.0/JetBrainsMono.zip && unzip JetBrainsMono.zip && rm -rf JetBrainsMono.zip && fc-cache -vf
```

---

## Components

| Component   | Description      |
| ----------- | ---------------- |
| WM          | i3               |
| Bar         | Polybar          |
| Launcher    | Rofi             |
| Compositor  | Picom            |
| Terminal    | Kitty            |
| Shell       | Zsh              |
| System Info | Fastfetch        |
| Theme       | Catppuccin Mocha |

---

## Repository Structure

```text
.
├── i3/
├── polybar/
├── rofi/
├── packages.md
└── README.md
```

---

## Contributing

Issues and pull requests are welcome.

```
```
