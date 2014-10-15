# FocusTheme (VIM Colorscheme for HTML documents)

Distraction free colorscheme for VIM that makes editing content inside
HTML documents a breeze, by dimming all tags, and only focussing on the
content inside HTML. Please, see my [VIMRC][vimrc] for an example
implementation.

## Installation

To use the dark theme ensure `set background=dark` is present in your
`~/.vimrc` file. Otherwise Vim will use the light variation by default.

Add `colorscheme focus-dark` to your `~/.vimrc` for dark theme,
and `colorscheme focus-light` for light theme.

### Vundle
Add the following to your `~/.vimrc` file and run `PluginInstall` in Vim.

    Plugin 'nikhgupta/vim-focus-html'
    
### Pathogen

    cd ~/.vim/bundle
    git clone https://github.com/nikhgupta/vim-focus-html.git

### Manual

    cd ~/.vim/colors
    git clone git://github.com/nikhgupta/vim-focus-html.git focus
    cp focus/colors/*.vim .

  [vimrc]: https://github.com/nikhgupta/dotfiles/blob/master/vimrc#L1251
