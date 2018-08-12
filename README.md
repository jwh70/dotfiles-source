## To Start
```
cd ~/

# Clone the Repo
git clone git@github.com:jwh70/dotfiles-source.git
mv dotfiles-source/* dotfiles-source/.* .

# Vim
ln -s ~/.vim/vimrc ~/.vimrcln -s ~/.vim/vimrc

# Zsh
sudo apt-get install zsh -y
sudo sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"

rm -rf dotfiles-source/
```
