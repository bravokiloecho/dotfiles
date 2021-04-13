# Dotfiles

These are my dotfiles. So far they include a config for ZSH and GitHub and that is all.

## Setup

First clone the repo into your home directory:

```
cd ~ && git clone git@github.com:bravokiloecho/dotfiles.git
```

Then create a symlink to the ZSH config that lives in this repo:

```
ln -s ~/dotfiles/.zshrc ~/.zshrc
ln -s ~/dotfiles/.gitconfig ~/.gitconfig
```

If these files already exist, I reccommend deleting the originals and creating a backup:

```
mv ~/.zshrc ~/.zshrc_backup
mv ~/.gitconfig ~/.gitconfig_backup
```