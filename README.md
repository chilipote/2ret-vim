# 2ret-vim : Ben Thouret's Vim Distribution

     #######  ########  ######## ########         ##     ## #### ##     ##
    ##     ## ##     ## ##          ##            ##     ##  ##  ###   ###
           ## ##     ## ##          ##            ##     ##  ##  #### ####
     #######  ########  ######      ##    ####### ##     ##  ##  ## ### ##
    ##        ##   ##   ##          ##             ##   ##   ##  ##     ##
    ##        ##    ##  ##          ##              ## ##    ##  ##     ##
    ######### ##     ## ########    ##               ###    #### ##     ##


2ret-vim is a distribution of vim plugins and resources for Vim, Gvim and [MacVim].

The distribution is completely customisable using a `~/.vimrc.local`
and `~/.vimrc.bundles.local` Vim RC files.

# INSTALLATION (Linux, *nix, Mac OSX Installation)

The easiest way to install 2ret-vim is to use our [automatic installer](http://2ret.com/vim)
by simply copying and pasting the following line into a terminal.
This will install 2ret-vim and backup your existing vim configuration.

```bash

    curl http://2ret.com/vim -L -o - | sh

```

## Updating to the latest version

```bash
    cd $HOME/to/2ret-vim/
    git pull
    vim +BundleInstall! +BundleClean +q
```

# OPTIMIZED .vimrc CONFIG FILE

## Customization

# PLUGINS

## Adding new plugins

Create `~/.vimrc.bundles.local` for any additional bundles.

To add a new bundle

```bash
    echo Bundle \'2ret-vim/vim-colors\' >> ~/.vimrc.bundles.local
```

Here are a few of the plugins:

## [Surround]

## [NERDCommenter]

## [Neocomplcache]

## [Fugitive]

## [Ack.vim]

## [Tagbar]

## [ZoomWin]

## [Ctrlp.vim]

## [Gundo]

# Intro to VIM

Here's some tips if you've never used VIM before:

## Tutorials

* Type `vimtutor` into a shell to go through a brief interactive
  tutorial inside VIM.
* Read the slides at [VIM: Walking Without Crutches](http://walking-without-crutches.heroku.com/#1).
* [Learn Vim Progressively](http://yannesposito.com/Scratch/en/blog/Learn-Vim-Progressively/)

## Modes

* VIM has two (common) modes:
  * insert mode- stuff you type is added to the buffer
  * normal mode- keys you hit are interpreted as commands
* To enter insert mode, hit `i`
* To exit insert mode, hit `<ESC>`

## Useful commands

* Use `:q` to exit vim
* Certain commands are prefixed with a `<Leader>` key, which by default maps to `\`.
  2ret-vim uses `let mapleader = ","` to change this to `,` which is in a consistent and
  convenient location.

### Keyboard cheat sheet

[source cheat sheet](http://walking-without-crutches.heroku.com/image/images/vi-vim-cheat-sheet.png)

![vim cheat sheet image][vim-key-mapping-img]

# CREDITS

Strongly inspired by [spf13-vim : Steve Francia's Vim Distribution](https://github.com/spf13/spf13-vim)

[MacVim]:http://code.google.com/p/macvim/
[spf13-vim]:https://github.com/spf13/spf13-vim
[2ret-vim]:https://github.com/benichu/2ret-vim

[Vundle]:http://github.com/gmarik/vundle
[NERDCommenter]:http://github.com/scrooloose/nerdcommenter
[NERDTree]:http://github.com/scrooloose/nerdtree
[Neocomplcache]:http://github.com/shougo/neocomvim
[Fugitive]:http://github.com/tpope/vim-fugitive
[Surround]:https://github.com/tpope/vim-surround
[Tagbar]:http://github.com/godlygeek/tagbar
[Syntastic]:http://github.com/scrooloose/syntastic
[Matchit]:http://www.vim.org/scripts/script.php?script_id=39
[Tabularize]:http://github.com/godlygeek/tabular
[Ack.vim]:https://github.com/mileszs/ack.vim
[ZoomWin]:https://github.com/vim-scripts/ZoomWin
[Ctrlp.vim]:https://github.com/kien/ctrlp.vim.git
[Gundo]:https://github.com/sjl/gundo.vim

[vim-key-mapping-img]:http://i.imgur.com/hP67T.png