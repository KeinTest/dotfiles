# 🛠️ dotfiles

> ⚙️ My personal, portable developer environment.  
> Consistency across machines, powered by good defaults & automation.

## ✨ Features

- 🧠 Thoughtfully organized and modular
- 🚀 Fast bootstrapping with minimal effort
- 🎨 Theme and UI customizations for productivity & aesthetics
- 🧰 Preconfigured tools for development, terminal, and system workflows
- 🔐 Safe to version control with secrets excluded

## 🧩 Included Configs

| Tool            | Description                              |
|-----------------|------------------------------------------|
| `zsh` / `oh-my-zsh` | Custom prompt, aliases, plugins      |
| `tmux`          | Clean statusline, session management     |
| `nvim` / `lazy.nvim` | Modern Neovim IDE setup             |
| `git`           | Useful aliases, sensible diffs & ignores |
| `alacritty` / `kitty` | Terminal theme & font setup        |
| `starship`      | Cross-shell prompt with minimal flair    |
| `scripts/`      | Handy scripts to automate common tasks   |

## 🚀 Installation

Clone and run the bootstrap script:

```bash
git clone https://github.com/YOUR-USERNAME/dotfiles ~/.dotfiles
cd ~/.dotfiles
./install.sh
