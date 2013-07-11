Installation:
  
    git clone git://github.com/wokumura/dotvim.git ~/.vim
  
Create symlinks:
  
    ln -s ~/dotfiles/vimrc ~/.vimrc

Add submodule:

    git submodule add https://github.com/tpope/vim-fugitive.git bundle/fugitive
    git submodule init && git submodule update
