# .tmux

A modern, feature-rich tmux configuration focused on usability and aesthetics.

## Features

- 256 color support with true color (RGB) capability
- Custom key bindings for improved workflow
- Mouse mode enabled
- Vi mode for efficient navigation
- Modern copy mode with vim-like bindings
- Intuitive pane splitting and navigation
- Enhanced status bar design
- Automatic window renumbering
- Activity monitoring
- Zero escape time for responsive usage

## Installation

1. Clone this repository:

```bash
git clone https://github.com/Programmer-RD-AI/.tmux.git ~/.tmux
```

2. Create a symbolic link to the tmux configuration:

```bash
ln -s ~/.tmux/tmux.conf ~/.tmux.conf
```

3. Optional: Use the provided shell script for custom config path:

```bash
ln -s ~/.tmux/tmux.sh /usr/local/bin/tmux-custom
```

## Key Bindings

- Prefix: Ctrl + a (changed from default Ctrl + b)
- Split window horizontally: Prefix + |
- Split window vertically: Prefix + -
- Navigate panes: Alt + Arrow Keys
- Copy mode: Prefix + [ then:
  - Start selection: v
  - Copy selection: y
- Reload configuration: Prefix + r

## Configuration Details

- Window numbering starts at 1
- Scrollback buffer size: 50,000 lines
- Status bar positioned at top
- Modern status bar design with session name, hostname, and time
- Automatic window renumbering when closing windows
- Zero escape time for immediate key recognition

## License

This project is licensed under the MIT License - see the LICENSE file for details.
