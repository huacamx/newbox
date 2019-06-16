# Setup

## VIM


ln -s ~/newbox/.vim/vimrc .vimrc
git clone https://github.com/VundleVim/Vundle.vim.git ~/newbox/.vim/bundle/Vundle.vim
vim +PluginInstall +qall

## Powerline
pip install --user powerline-status