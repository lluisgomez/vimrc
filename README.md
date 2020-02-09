Configured following: https://realpython.com/vim-and-python-a-match-made-in-heaven/



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
