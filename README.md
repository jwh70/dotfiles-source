## Dotfiles
```
cd ~/

# Clone the Repo
git clone git@github.com:jwh70/dotfiles-source.git
mv dotfiles-source/* dotfiles-source/.* .

# Vim (make sure to run :PlugInstall)
ln -s ~/.vim/vimrc ~/.vimrcln -s ~/.vim/vimrc

# Zsh
sudo apt-get install zsh -y OR brew install zsh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
rm ~/.zshrc
ln -s ~/.zsh/.zshrc ~/.zshrc

# Zsh
sudo apt-get install tmux
ln -s ~/.tmux/.tmux.conf .tmux.conf

rm -rf dotfiles-source/
```
