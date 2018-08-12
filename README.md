## To Start
```
cd ~/

# Clone the Repo
git clone git@github.com:jwh70/dotfiles-source.git
mv dotfiles-source/* dotfiles-source/.* .

# Vim (make sure to run :PlugInstall)
ln -s ~/.vim/vimrc ~/.vimrcln -s ~/.vim/vimrc

# Zsh
sudo apt-get install zsh -y
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
rm ~/.zshrc
ln -s ~/.zsh/.zshrc ~/.zshrc

rm -rf dotfiles-source/
```
