# dotvim

## Installation:

    git clone git://github.com/tding1/dotvim.git ~/.vim

## Create symlinks:

    ln -s ~/.vim/vimrc ~/.vimrc
    ln -s ~/.vim/gvimrc ~/.gvimrc

## Switch to the `~/.vim` directory, and fetch submodules:

    cd ~/.vim
    git submodule update --init
    
## Upgrading a plugin bundle:

    cd ~/.vim/bundle/<plugin>
    git pull origin master
    
## Upgrading all bundled plugins:

    git submodule foreach git pull origin master
