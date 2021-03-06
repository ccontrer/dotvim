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
* [Ctrl-P](https://github.com/ctrlpvim/ctrlp.vim)
* [Airline](https://github.com/vim-airline/vim-airline) with [Themes](https://github.com/vim-airline/vim-airline-themes)
* [todo](https://github.com/Dimercel/todo-vim) `F5`
* [Minimap](https://github.com/severin-lemaignan/vim-minimap) `<\mm>` `<\mc>` `<\mt>` (requires `vim-nox`)
* [Incsearch](https://github.com/haya14busa/incsearch.vim)
* [obsession](https://github.com/tpope/vim-obsession)
* [Syntastic](https://github.com/scrooloose/syntastic)
* [Julia-vim](https://github.com/JuliaEditorSupport/julia-vim)
* [Python-mode](https://github.com/python-mode/python-mode)
* [Latex-suite](https://github.com/vim-latex/vim-latex)
* [tagbar](https://github.com/majutsushi/tagbar) `F8` (requires `exuberant-ctags`)
* [Fugitive](https://github.com/tpope/vim-fugitive)
* [FastFold](https://github.com/Konfekt/FastFold) (solves folding lagging)
* [Vim Tmux Navigator](https://github.com/christoomey/vim-tmux-navigator) `<C-h>` `<C-j>` `<C-k>` `<C-l>` for combined Vim-Tmux navigation 

Previously included packages
----------------------------

* [L9](http://www.vim.org/scripts/script.php?script_id=3252)
* [Vundle](https://github.com/VundleVim/Vundle.vim)
* [sparkup](https://github.com/rstacruz/sparkup)

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
* Use solarized dark theme for the terminal for better compatibility
* Paste node `F2`
* Cursor movement continues to next/previous line
* Four (4) tab spaces
* Arrow keys move as normal on wrap mode, and `j` and `k` on visual mode only

Other
-----

### Links

* [Astrails dotvim](https://github.com/astrails/dotvim)
* [Bling dotvim](https://github.com/bling/dotvim)

#### Markdown

* [Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
* [Grip](https://github.com/joeyespo/grip) viewer

#### Vim cheat sheets

* [rtorr](http://vim.rtorr.com/)
* [theicfire](http://vimsheet.com/)
* [Graphical Viemu](http://www.viemu.com/a_vi_vim_graphical_cheat_sheet_tutorial.html)
* [Graphical Viemu PDF](http://www.glump.net/files/2012/08/vi-vim-cheat-sheet-and-tutorial.pdf)

#### dotvim tutorial

* [Dotvim, submodules and pathogen](http://vimcasts.org/episodes/synchronizing-plugins-with-git-submodules-and-pathogen/)
