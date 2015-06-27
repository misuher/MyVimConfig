# MyVimConfig

This Repository is intended to keep my vim configuration save and to share it with everyone who wants it.

I found that sharing this with dropbox and making symbolic links in every machine is really helpfull in order to work with the same Vim config in all my machines and to make config changes only once also.

I manage the plugins with pathogen. To install them clone the repo in ~/.vim folder and type the following:

    ln -s .vimrc ~/.vimrc
    git submodule init
    git submodule update

If someday you want to update all the plugins at once type:

    git submodule foreach git pull origin master


