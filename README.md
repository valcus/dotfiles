# Dotfiles

A place for files with dots.

## Required Software

`apt get stow`
`apt get git`

## Software cofigurations managed in this repo

- .bashrc
- neovim

## Installing

Clone repo to `~/dotfiles`

### Bash

Run `stow --dotfiles bash`

Changes to `bash` can now be applied with `stowbash` from the `dotfiles` directory.

### Git

If the git prompt is giving you any issues:

Make a symlink called `.git-prompt` to wherever your git-sh-prompt or git-prompt.sh script is.

`ln -s /usr/lib/git-core/git-sh-prompt .git-prompt`

### Neovim

https://github.com/nvim-lua/kickstart.nvim

You want the unstable ppa.

`stow nvim`
