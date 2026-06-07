# Tmux Configuration

This repository contains my personal [tmux](https://github.com/tmux/tmux) configuration.

## Features

### Customized Keybindings

- **Prefix key**: Changed from `Ctrl-b` to `Ctrl-a` (more ergonomic for daily use)
- **Reload config**: Press `Prefix + r` to reload the configuration on the fly
- **Vim-style pane navigation**: Use `h`, `j`, `k`, `l` (with or without `Alt`) to navigate between panes
- **New windows** open in the current working directory
- **Vim-style copy/paste** with Windows clipboard integration via `clip.exe`
- **Fast escape time** for smooth Vim/Neovim experience

### Session Management

- **Tmux Sessionizer** integration via `~/.local/bin/tmux-sessionizer` for quick project switching
- **Window numbering** starts at 1 (instead of 0) for easier keyboard reach
- **Automatic renumbering** of windows when one is closed

### Theme & Status Bar

- **Tokyonight Moon** color scheme with custom accents
- **Status bar positioned at the top** with a clean, minimal layout
- **Active window** shows current path (last 2 directories) and a checkmark indicator
- **Right status** shows current window name, session name, and a visual prefix indicator
- **Pane borders** styled with active/inactive colors

## Installation

```bash
# Clone the repository
git clone https://github.com/rpezzotti/tmux-config.git ~/.config/tmux

# Or create a symlink if you prefer
ln -s ~/.config/tmux/tmux.conf ~/.tmux.conf
```

## Prerequisites

- [tmux](https://github.com/tmux/tmux) (version 3.5+ recommended)
- Optional: [tmux-sessionizer](https://github.com/jrmoulton/tmux-sessionizer) for session management keybindings

## Credits

This configuration was heavily inspired by the work of **Tony Banters** and his project [**tmux-btw**](https://github.com/tonybanters/tmux-btw). Check out his YouTube content for more tmux tips and tricks!

## License

This configuration is provided as-is for personal use.
