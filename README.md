Recommended vim version: 8.0

Installing the submodules
-------------------------
git submodule update --init --recursive

Updating all submodules in one go
---------------------------------
git submodule update --remote --merge

Installing fonts
-------------------------
Go to <https://github.com/powerline/fonts> and install the fonts you want on to your system.
This will ensure that special characters used for the Powerline statusline plugin will look as they should.

Special Module information
==========================

Tagbar
------
Requires excuberant ctags: http://ctags.sourceforge.net/

YouCompleteMe
-------------
```bash
cd ~/.vim/bundle/vim-youcompleteme/
./install.sh --clang-completer
```

cPanel Snippets
---------------
* Clone the vim snippets repo to a location outside of the repo.
* Create a symlink to that location in the 'bundle' directory:
```
cd bundle
ln -s /path/to/cpanel-vim-snippets/ ./cpanel-snippets
```
