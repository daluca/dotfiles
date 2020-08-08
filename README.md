# dotfiles

## Install dotfiles
``` bash
git clone https://github.com/daluca/dotfiles.git ~/.dotfiles
rsync -a --exclude=.git/ --exclude=README.md ~/.dotfiles/* ~/.dotfiles/.* ~/
```

## Dependencies
### Install oh-my-zsh
``` bash
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

### Install zsh-syntax-highlighting
``` bash
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
```

### Install zsh-autosuggestions
``` bash
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
```

### Install powerlevel9k-theme
``` bash
git clone https://github.com/bhilburn/powerlevel9k.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/themes/powerlevel9k
```