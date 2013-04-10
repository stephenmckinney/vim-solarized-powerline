# Solarized theme for vim\-Powerline

Solarized dark and light colorschemes as well as a short and long theme for [vim-Powerline](https://github.com/Lokaltog/vim-powerline).
Using [Solarized 256 and 16 color values](https://github.com/altercation/vim-colors-solarized#the-values).

## Installation

Using Pathogen, NeoBundle, or Vundle load `vim-powerline` then
`vim-solarized-powerline`, e.g.

    NeoBundle 'Lokaltog/vim-powerline'
    NeoBundle 'stephenmckinney/vim-solarized-powerline'

### Solarized 256 colors

This colorscheme is based on Solarized colors, setting the *approximate* values for the Solarized palette, using the XTERM
limited 256 terminal color values. It combines Solarized with Powerline default colors. To set the short theme and dark
colorscheme for example:

    let g:Powerline_theme='short'
    let g:Powerline_colorscheme='solarized256_dark'

### Solarized 16 colors

This colorscheme is based on Solarized colors, setting the *specific* values for the Solarized palette, using the
terminal's 16 ansi color values. It combines Solarized with Powerline default colors.

Using 16 ansi color values gives the best results for terminal Vim.
See Solarized documentation on [terminal integration]( https://github.com/altercation/vim-colors-solarized#important-note-for-terminal-users ).
To set the short theme and dark colorscheme for example:

    let g:Powerline_theme='short'
    let g:Powerline_colorscheme='solarized16_dark'

## Credits

There are other Solarized vim-powerline colorschemes (see @e-mux, @skwp, @patricklewis)
this one is my opinionated version.
