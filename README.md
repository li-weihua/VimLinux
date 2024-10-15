# my vim configure files

just do 

```bash
git clone https://github.com/nnhobby/VimLinux.git ~/.vim
ln -s ~/.vim/vimrc ~/.vimrc
```

## Fix YouCompleteMe clangd cannot run error on linux

The compiled clangd do not support centos 7, at least glibc 2.28!

copy clangd to override YouCompleteMe's clangd
