# Setup

## VIM

```sh
ln -s ~/newbox/.vim/vimrc .vimrc
ln -s ~/newbox/.zshrc .
ln -s ~/newbox/.tmux.conf .


git clone https://github.com/VundleVim/Vundle.vim.git ~/newbox/.vim/bundle/Vundle.vim
vim +PluginInstall +qall
```
## Powerline
```sh
# fonts for zsh
sudo apt-get install fonts-powerline

# power line status for vim
sudo apt install python3-pip
pip3 install --user powerline-status
```


