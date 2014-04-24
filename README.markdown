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
For older version of vim, you may need one more step:
```bash
ln -snf ~/.vim/vimrc .vimrc
ln -snf ~/.vim/gvimrc .gvimrc
```

