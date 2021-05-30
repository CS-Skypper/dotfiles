# My ~

![Screenshot](https://i.imgur.com/HhjEfA3.png)

## Table of contents

<!-- vim-markdown-toc GFM -->

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
    - [Linux](#linux)
    - [macOS](#macos)
  - [Quick usage instruction](#quick-usage-instruction)
- [Features](#features)
  - [Version control](#version-control)
  - [Wallpapers](#wallpapers)
- [Acknowledgements](#acknowledgements)

<!-- vim-markdown-toc -->

## Getting Started

### Prerequisites

You can skip this step if you're using Arch Linux, use the install script below to install these packages automatically.

Install the following packages:

- `git`
- `xorg-server`
- `xorg-xinit`
- [`dmenu`](https://github.com/khuedoan/dmenu)
- [`dwm`](https://github.com/khuedoan/dwm)
- [`st`](https://github.com/khuedoan/st)
- [`slock`](https://github.com/khuedoan/slock)
- [`picom-git`](https://aur.archlinux.org/packages/picom-git/)
- [`nerd-fonts-fira-mono`](https://aur.archlinux.org/packages/nerd-fonts-fira-mono/)

### Installation

#### Linux

If you just want the dotfiles:

```
git clone https://github.com/khuedoan/linux-setup
cd linux-setup
make init dotfiles
```

#### macOS

I also have some limited macOS support:

```
git clone https://github.com/khuedoan/macos-setup
cd macos-setup
make init dotfiles
```

### Quick usage instruction

Some key mapping are changed, you can change this in `.xinitrc`:

- Left Alt and Left Super is swapped

Some basic key bindings:

- `super + /`         for key bindings help
- `super + enter`     for terminal
- `super + space`     for app launcher
- `super + shift + q` to quit app

## Features

### Version control

Make change to the config files to suit your needs, then use the `git` for version control like normal. For example:

```sh
cd ~
git add .config/foo
git commit
git push
git pull
```

### Wallpapers

| Original | Blured|
| :-- | :-- |
| ![Original](https://i.imgur.com/ZlvUiIZ.jpg) | ![Blured](https://i.imgur.com/C3tCYsp.jpg) |
