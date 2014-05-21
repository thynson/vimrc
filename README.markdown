# vimrc

Execute the following commands to setup your vim.
```bash
cd ~/.vim
git init
git remote add origin https://github.com/thynson/vimrc.git
git pull origin master
git submodule init
git submodule update
```
Then build the YCM plugins, at least clang development package(clang-devel or
libclang-dev, depends on your distros), C++ compiler(most situation it'll be
g++), and cmake need to be installed on your machine. This powerful plugins
may depends other stuffes.
```
cd ~/.vim/bundle/YouCompleteMe/
./install.sh --clang-completer --system-libclang
```
For older version of vim, you may need one more step:
```bash
ln -snf ~/.vim/vimrc .vimrc
ln -snf ~/.vim/gvimrc .gvimrc
```

