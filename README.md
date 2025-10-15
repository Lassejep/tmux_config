# Tmux configuration

## Dependencies
- [tmux](https://github.com/tmux/tmux/wiki)
- [tpm](https://github.com/tmux-plugins/tpm)
- [git](https://git-scm.com/)

## Installation
### Install Tmux Plugin Manager
```bash
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```

### Clone and install the tmux configuration
```bash
mkdir -p ~/git
git clone https://github.com/lassejep/tmux_config.git ~/git/
ln -s ~/git/tmux_config ~/.config/tmux
```

### Install tmux plugins
Open tmux and press `ctrl + space` and then `I` to install the tmux plugins.
