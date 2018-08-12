## Help From
- https://github.com/robbyrussell/oh-my-zsh/wiki/Installing-ZSH
- https://github.com/tpope/vim-pathogen
- https://github.com/tyrocca/dotfiles

## To Start
```
cd ~/ 
git clone git@github.com:jwh70/dotfiles-source.git
mv dotfiles-source/* dotfiles-source/.* .
# Vim
ln -s ~/.vim/vimrc ~/.vimrcln -s ~/.vim/vimrc
# Zsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

rm -rf dotfiles-source/
```
