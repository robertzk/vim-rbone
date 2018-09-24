# rbone.vim

*Editor's note*: This is an augmented version of the original [tbone](https://github.com/tpope/vim-tbone) by tpope.
Basic tmux support for Vim.

* `:Tmux` lets you call any old `tmux` command (with really good tab
  complete).
* `:Tyank` and `:Tput` give you direct access to tmux buffers.
* `:Twrite` sends a chunk of text to another pane.  Give an argument like
  `windowtitle.2`, `top-right`, or `last`, or let it default to the previously
  given argument.
* `:Tattach` lets you use a specific tmux session from outside of it.

Would you like to paste a shell command into another pane over and over again?
I am sorry but you will have to install one of the 300 other Vim plugins for
tmux.

## Installation

If you don't have a preferred installation method, I recommend
installing [pathogen.vim](https://github.com/tpope/vim-pathogen), and
then simply copy and paste:

    cd ~/.vim/bundle
    git clone git://github.com/tpope/vim-rbone.git

Once help tags have been generated, you can view the manual with
`:help rbone`.

## License

Copyright © Robert Krzyzanowski, Tim Pope.  Distributed under the same terms as Vim itself.
See `:help license`.

