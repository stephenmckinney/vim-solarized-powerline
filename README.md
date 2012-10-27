# Solarized theme for vim\-Powerline

Solarized colorscheme and theme for [vim-Powerline](https://github.com/Lokaltog/vim-powerline). Using [Solarized 256 and 16 color values](https://github.com/altercation/vim-colors-solarized#the-values).

## Installation

Using Pathogen, NeoBundle, or Vundle load `vim-powerline` then
`vim-solarized-powerline`, e.g.

    NeoBundle 'Lokaltog/vim-powerline'
    NeoBundle 'stephenmckinney/vim-solarized-powerline'

### Solarized 256 colors

This colorscheme is based on Solarized-dark colors, setting the *approximate* values for the Solarized palette, using the XTERM limited 256 terminal color values. It combines Solarized with Powerline default colors.

    let g:Powerline_theme='solarized'
    let g:Powerline_colorscheme='solarized256'

### Solarized 16 colors

This colorscheme is based on Solarized-dark colors, setting the *specific* values for the Solarized palette, using the terminal's 16 ansi color values. It combines Solarized with Powerline default colors.

Using 16 ansi color values gives the best results for terminal Vim.
See Solarized documentation on [terminal integration]( https://github.com/altercation/vim-colors-solarized#important-note-for-terminal-users ).

    let g:Powerline_theme='solarized'
    let g:Powerline_colorscheme='solarized16'

## Credits

There are other Solarized vim-powerline colorschemes (see @e-mux, @skwp, @patricklewis)
this one is my opinionated version.
