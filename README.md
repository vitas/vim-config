About
====
This a forked version of vim settings I tuned for my Go development.

Usage
====

After cloning the repository at a location, say, `$HOME/vim-config`, you want to make symbolic links of vim to `$HOME/.vim` and vimrc to `$HOME/.vimrc`
and then run  `git submodule update --init --recursive`

Or, you can just clone using `git clone git@github.com:prasincs/vim-config --recursive`

You'd want to symlink `$CONFIG_DIR/vimrc` to `$HOME/.vimrc` and `$CONFIG_DIR/gvimrc` to `$HOME/.gvimrc`. 
Additionally, I use `$HOME/.vimrc_local` to store things specific to my machines, or when I'm debugging scripts.

Features
===

They're all included using Pathogen from the vim/bundles directory. 

Major ones

* Syntastic
* Surround -- I rarely use it but it's handy to have around
* NERDCommenter
* Tagbar
* Ctrl-P
* Go support
* Markdown edit and preview support
