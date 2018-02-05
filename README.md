# My dotfiles

```
cd ~
git clone git@github.com:lovenery/dotfile.git
cp dotfile/.vimrc .
cp dotfile/.git-prompt-colors.sh .
rm -rf dotfile

git clone https://github.com/magicmonty/bash-git-prompt.git .bash-git-prompt
source ~/.bash-git-prompt/gitprompt.sh # in .bashrc or .bash_profile
```
