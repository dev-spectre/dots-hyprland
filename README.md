# dots-hyprland

Hyprland window manager configuration and dotfiles.

## Overview

Personal Hyprland configuration with custom keybinds, window rules, animations, and helper scripts. Designed for a productive tiling window manager experience on Wayland.

## Features

- Custom keybinds for window management, apps, and workspaces
- Window rules for floating/snapping
- Animation configurations
- Color theme
- Helper scripts for workspace actions and zoom

## Installation

Copy or symlink the `hypr/` directory to `~/.config/hypr/`:

```bash
cp -r hypr ~/.config/hypr
```

## Project Structure

```
└── hypr/
    ├── hyprland.conf          # Main Hyprland config
    ├── rules.conf             # Window rules
    ├── env.conf               # Environment variables
    ├── colors.conf            # Color theme
    ├── keybinds.conf          # Key bindings
    ├── execs.conf              # Autostart programs
    ├── general.conf            # General settings
    └── scripts/
        ├── launch_first_available.sh
        ├── workspace_action.sh
        └── zoom.sh
```

## License

MIT
