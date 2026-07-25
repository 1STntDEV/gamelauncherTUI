# GameLauncher

A minimal TUI game launcher for Linux.

## Features

- Steam games detection
- Dolphin GameCube/Wii support
- Keyboard focused
- Built with Bash and fzf
- Lightweight

## Requirements

- Bash
- fzf
- Steam
- Dolphin (optional)

## Installation

### Dependencies

GameLauncher requires:

- bash
- fzf
- git

On Arch Linux:

```bash
sudo pacman -S git fzf

## optional

sudo pacman -S dolphin-emu ppsspp pcsx2

## Installation

### Dependencies

GameLauncher requires:

- bash
- fzf
- git

On Arch Linux:

sudo pacman -S git fzf

### Optional emulators

sudo pacman -S dolphin-emu ppsspp pcsx2

### Install

Clone the repository:

git clone https://github.com/1STntDEV/gamelauncherTUI.git

Go into the folder:

cd gamelauncherTUI

Install GameLauncher:

mkdir -p ~/.local/bin
cp gamelauncher ~/.local/bin/
chmod +x ~/.local/bin/gamelauncher

### Run

gamelauncher

### Supported games

- Steam games (automatic detection)
- Nintendo GameCube / Wii (Dolphin)
- More emulators coming later

### Configuration

Default ROM folders:

~/rom/gamecube
~/rom/wii

Steam games are detected automatically from your Steam library.
