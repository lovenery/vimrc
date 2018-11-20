# My dotfiles

## Install

```bash
cd ~
git clone https://github.com/lovenery/dotfile.git
cp dotfile/.vimrc .
cp dotfile/.git-prompt-colors.sh .
rm -rf dotfile

git clone https://github.com/magicmonty/bash-git-prompt.git .bash-git-prompt
echo 'source ~/.bash-git-prompt/gitprompt.sh' >> ~/.bash_profile
```

## Uninstall

```bash
rm -rf ~/.git-prompt-colors.sh ~/.bash-git-prompt/
```
