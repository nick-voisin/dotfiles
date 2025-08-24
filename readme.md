# dotfiles

Personal dotfiles for my Ubuntu desktop.

## Installation

### Pull config to new machine
```chezmoi init --apply nick-voisin```

### Update config and upload
```chezmoi re-add && chezmoi cd && git add . && git commit -m "update dotfiles" && git push```

### Add new file 'new-config-file' to config
```
chezmoi add new-config-file
chezmoi cd
git add .
git commit -m "Update dotfiles"
git push
```

## TODO
- Add installation scripts for packages like:
  - chezmoi
  - uv
  - fd
  - eza
  - bat
  - fzf
  - tmux
  - yazi
  - ...