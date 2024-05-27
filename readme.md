# Dotfiles

This repository contains my configuration files (dotfiles) for various tools and applications. These configurations are managed using GNU Stow to simplify the process of maintaining and symlinking the dotfiles.

## Tools and Applications

- **GNU Stow**: Manages symlinks for the configuration files.
- **tmux**: Terminal multiplexer for managing multiple terminal sessions.
- **neovim (nvim)**: A modernized version of the vim text editor.
- **alacritty**: A fast, cross-platform terminal emulator.
- **zsh**: Z shell, an extended version of the Bourne shell with many improvements.

## Installation

### Prerequisites

- Ensure you have the following installed on your system:
  - GNU Stow
  - tmux
  - neovim
  - alacritty
  - zsh

### Setup

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/yourusername/dotfiles.git ~/.dotfiles
    cd ~/.dotfiles
    ```

2. **Symlink the Configuration Files**:
    ```sh
    stow .
    ```

    This will create symlinks in your home directory pointing to the configuration files in the `.dotfiles` directory.

## Configuration Details

### tmux

- Configuration File: `.config/tmux/.tmux.conf`
- Customizations include key bindings, theme settings, and plugins.

### neovim

- Configuration Directory: `.config/nvim`
- Includes plugins, key mappings, and theme settings.

### alacritty

- Configuration File: `.config/alacritty/alacritty.toml`
- Settings for fonts, colors, and other terminal preferences.

### zsh

- Configuration File: `.zshrc`
- Includes prompt settings, aliases, and plugins managed with `oh-my-zsh`.

## Customizing

Feel free to customize these configuration files to suit your preferences. After making changes, you can update the symlinks by re-running the `stow` command.

## Contributing

If you have any improvements or suggestions, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

