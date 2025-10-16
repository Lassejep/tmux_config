# Tmux configuration

## Dependencies
- [tmux](https://github.com/tmux/tmux/wiki)
- [tpm](https://github.com/tmux-plugins/tpm)
- [git](https://git-scm.com/)
- [stow](https://www.gnu.org/software/stow/)

## Installation
### Install Tmux Plugin Manager
```bash
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

### Clone and install the tmux configuration
```bash
mkdir -p ~/configs
git clone https://github.com/lassejep/tmux_config.git ~/configs
cd ~/configs/tmux_config/
stow -t XDG_CONFIG_HOME .
```

### Install tmux plugins
Open tmux and press `ctrl + space` and then `I` to install the tmux plugins.
