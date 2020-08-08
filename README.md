# dotfiles

## Install dotfiles
``` bash
git clone https://github.com/daluca/dotfiles.git ~/.dotfiles
rsync -a --exclude=.git/ --exclude=README.md ~/.dotfiles/* ~/.dotfiles/.* ~/
```
