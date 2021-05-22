# vim-config
My .vimrc file I use for programming in vim

## How to use:
* Copy the config settings from the `vimrc.txt` file
* Paste the config settings into your own vimrc file
* Write the changes
* Install vim-plug (https://github.com/junegunn/vim-plug)
* Make a new directory in `~/.vim` and call it `undodir`. This is a directory where undo history for edited files will be stored.
* Finally, in vim, run `:PlugInstall` to install all of the plugins


* To setup YouCompleteMe, change directory to `~/.vimrc/plugged/YouCompleteMe` and run `python3 install.py`

To see the changes, you have to quit out of vim and open it again, or do `:source %` within vim.
