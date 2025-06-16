# Jenokai
My modified version of Monokai for personal preferences
![image](https://github.com/user-attachments/assets/792d48f6-c9b2-4e01-a20b-7becfaf4b779)

## Setup
First of all, clone this repository and then place Jenokai.vim into your colors directory.
Or rather, use this git command:
```bash
curl -fLo ~/.vim/colors/Jenokai.vim --create-dirs https://raw.githubusercontent.com/acerpixels/Jenokai/master/Jenokai.vim
```

## Adding the Colorscheme Into Your `.vimrc`
Make sure you add these following lines of code into your `.vimrc` configuration file
```vim
syntax on
set termguicolors
set background=dark
colorscheme Jenokai
set scl=auto
```
