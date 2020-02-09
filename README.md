Configured following: https://realpython.com/vim-and-python-a-match-made-in-heaven/

![gvim screenshot](https://raw.githubusercontent.com/lluisgomez/vimrc/master/Screenshot_2020-02-09.png)

- Compiled VIM with:

```
./configure --with-features=huge --enable-multibyte --enable-rubyinterp=yes --enable-pythoninterp=yes --with-python-config-dir=$(python-config --configdir) --enable-perlinterp=yes --enable-luainterp=yes --enable-gui=gtk2 --enable-cscope --prefix=/usr/local
```

- Compiled YouCompleteMe with:
```
cd ~/.vim/bundle/YouCompleteMe
git submodule update --init --recursive
./install.py
```
