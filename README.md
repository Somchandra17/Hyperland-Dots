# Hyprland Dotfiles

This repository contains my personal dotfiles for Hyprland on Ubuntu 24.04.

## Included Configurations

### Window Manager & Compositor
- **hypr/** - Hyprland configuration files
- **kanshi/** - Display management configuration
- **waybar/** - Status bar configuration with CSS styling
- **rofi/** - Application launcher configuration
- **wlogout/** - Logout menu configuration
- **swaync/** - Notification center configuration
- **nwg-displays/** - Display configuration tool
- **tiling-assistant/** - GNOME tiling extension

### Terminal Emulators & Shell
- **.zshrc** - Zsh shell configuration
- **.p10k.zsh** - Powerlevel10k theme configuration
- **oh-my-posh/** - Oh My Posh theme configuration
- **.bashrc** - Bash shell configuration
- **.profile** - Shell profile configuration
- **kitty/** - Kitty terminal emulator configuration
- **ghostty/** - Ghostty terminal configuration
- **warp-terminal/** - Warp terminal configuration
- **terminator/** - Terminator terminal configuration

### System Monitoring & Utilities
- **btop/** - System monitor configuration
- **cava/** - Audio visualizer configuration
- **fastfetch/** - System information tool configuration
- **neofetch/** - System info display configuration
- **nvtop/** - GPU monitoring tool configuration
- **swappy/** - Screenshot annotation tool configuration
- **wireshark/** - Network analyzer configuration

### Theming & Appearance
- **.themes/** - GTK themes
- **.icons/** - Icon themes
- **.fonts/** - Custom fonts
- **wallust/** - Wallpaper color scheme generator
- **ags/** - Aylur's Gtk Shell configuration
- **gtk-3.0/** - GTK 3 theming configuration
- **gtk-4.0/** - GTK 4 theming configuration
- **qt5ct/** - Qt5 configuration tool settings
- **qt6ct/** - Qt6 configuration tool settings
- **Kvantum/** - Qt application theming engine

### File Management & Desktop
- **Thunar/** - XFCE file manager configuration
- **xfce4/** - XFCE desktop environment settings
- **mimeapps.list** - Default application associations
- **monitors.xml** - Display configuration
- **background** - Wallpaper/background image
- **pavucontrol.ini** - Audio control settings
- **yad.conf** - Yet Another Dialog configuration

## Installation

1. Clone this repository
2. Copy the configuration files to their respective locations in your home directory
3. Make sure to backup your existing configurations before replacing them
4. Install the required dependencies for each application

## Dependencies

Core Hyprland setup:
- hyprland, waybar, rofi, kanshi, swaync, wlogout, ags
- kitty, ghostty, warp-terminal, terminator
- zsh, oh-my-posh, powerlevel10k

System tools:
- btop, cava, fastfetch, neofetch, nvtop, swappy, wireshark
- thunar, qt5ct, qt6ct, kvantum
- nwg-displays, tiling-assistant

See `INSTALLED_APPS.md` for complete application list.

## Files Structure

```
Dots/
├── README.md                 # This file
├── INSTALLED_APPS.md        # Complete applications list
├── hypr/                    # Hyprland configs
├── waybar/                  # Status bar with CSS
├── rofi/                    # App launcher
├── kanshi/                  # Display management
├── kitty/                   # Terminal configs
├── .zshrc                   # Zsh configuration
├── .p10k.zsh               # Powerlevel10k theme
├── oh-my-posh/             # Oh My Posh themes
├── .themes/                # GTK themes
├── .icons/                 # Icon themes
├── .fonts/                 # Custom fonts
└── [other configs...]      # Additional configurations
```

## Notes

- Configurations are tailored for Ubuntu 24.04 with Hyprland
- Monitor configurations may need adjustment for your setup
- See INSTALLED_APPS.md for complete software inventory
- Created on: Sunday, 2025-09-21
