vim-base16-lightline
====================

This is a fork of [the plugin by daviesjamie](https://github.com/daviesjamie/vim-base16-lightline), I wanted the inactive colors to 
be slightly brighter as they are hard to see with the `base16_dark_harmonic` theme.

## Installation

As with any other theme, this can be installed with any of the popular plugin
managers:

 - [vim-plug](https://github.com/junegunn/vim-plug)
     - `Plug 'avishayy/vim-base16-lightline'`
 - [Vundle](https://github.com/VundleVim/Vundle.vim)
     - `Bundle 'avishayy/vim-base16-lightline'`
 - [Pathogen](https://github.com/tpope/vim-pathogen)
     - `git clone https://github.com/avishayy/vim-base16-lightline ~/.vim/bundle/vim-base16-lightline`

You can also install the plugin manually, by copying the files into your
vim / nvim confugration directory.

After it is installed, you need to tell lightline to use the theme:

```VimL
let g:lightline = {
\   'colorscheme': 'base16'
\ }
```
