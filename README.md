&copy; Carlos Contreras
carloscontrerasc@gmail.com

Vim configuration folders
=========================

Installation
------------

    git clone https://github.com/carlosshigoto/dotvim.git ~/.vim
    git submodule init
    git submodule update


Create symbolic link
--------------------

    ln -s ~/.vim/dotvimrc ~/.vimrc

Packages
--------

* [Pathogen](https://github.com/tpope/vim-pathogen)
* [Solarized](https://github.com/altercation/vim-colors-solarized)
* [NERDTree](https://github.com/scrooloose/nerdtree) `<C-n>`
* [NERDCommenter](https://github.com/scrooloose/nerdcommenter) `<\cc>` `<\cu>`
* [Airline](https://github.com/vim-airline/vim-airline) with [Themes](https://github.com/vim-airline/vim-airline-themes)
* [todo](https://github.com/Dimercel/todo-vim) `F5`
* [Incsearch](https://github.com/haya14busa/incsearch.vim)
* [obsession](https://github.com/tpope/vim-obsession)
* [Julia-vim](https://github.com/JuliaEditorSupport/julia-vim)

Not included
------------

* [L9](http://www.vim.org/scripts/script.php?script_id=3252)
* [Ctrl-P](https://github.com/kien/ctrlp.vim)
* [Syntastic](https://github.com/scrooloose/syntastic)
* [Fugitive](https://github.com/tpope/vim-fugitive)
* [Vundle](https://github.com/VundleVim/Vundle.vim)
* [Latex-suite](https://github.com/vim-latex/vim-latex)
* [tagbar](https://github.com/majutsushi/tagbar)
* [sparkup](https://github.com/rstacruz/sparkup)
* [Minimap](https://github.com/severin-lemaignan/vim-minimap)

Features
--------

* Use Pathogen and submodules to install plugins

    ```
    cd ~/.vim/bundle
    git submodule add repo-url
    ```
    or 
    ```
    git submodule add repo-url bundle/pkg-name
    ```

* Solarized toggle background with `F6`
* Use solarized dark theme for the termnal for better compatibility
* Paste node `F2`
* Cursor movement continues to next/previous line
* Four (4) tab spaces

### Links

#### Markdown

* [Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* [Grip](https://github.com/joeyespo/grip) viewer

#### Vim cheat sheets

* [rtorr](http://vim.rtorr.com/)
* [theicfire](http://vimsheet.com/)
* [Graphical Viemu](http://www.viemu.com/a_vi_vim_graphical_cheat_sheet_tutorial.html)
* [Graphical Viemu PDF](http://www.glump.net/files/2012/08/vi-vim-cheat-sheet-and-tutorial.pdf)

#### dotvim tutorial
