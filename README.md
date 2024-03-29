# Neovim configuration file

This file contains personal neovim configuration that can also be used with VIM.

## Installation

If you're running vim for the first time, is recommended to use the installation script,
In case you have a previous configuration you will have to copy the .vimrc manually and then running the installation script

```sh
  ./install.sh
```

## Plug in can be installed via curl

Puglins are installed via Plug
[VIM Plug](https://github.com/junegunn/vim-plug)

An installation file is in progress and will be added before 2022

In order to enable file search, install Rg (ripgrep)

## Main key binding

  1. space + w   ---> :w save current file
  2. space + q   ---> :q quit current file
  3. space + fq  ---> :q! forces quit without saving
  4. space + t   ---> <Plugin> remove empty spaces on the document
  5. space + cc  ---> comments a line or block
  6. space + cu  ---> uncoments a line or block
  7. space + ci  ---> toogles a selected block from commented to uncommented
  8. space + b   ---> <Plugin> shows Conquer Of Completition options
  9. space + a   ---> <Plugin> shows Conquer Of Completition actions
  10. space + nt  ---> <Plugin> opens nerd tree navigation
  11. space + m  ---> <Plugin> easymotion allows navigation with two letters
  12. space + h  ---> :tabl navigates to frist left tab document
  13. space + j  ---> :tabp navigates to left tab document
  14. space + k  ---> :tabn navigates to the right tab document
  15. space + l  ---> :tabr navigates to the last right tab document
  16. space + e [ h | j | k | l ]  ---> Shortcut for <C-w> this allows navigation between splited windows
  17. space + f  ---> :FZF finds a file by name
  18. space + ff ---> :Rg looks for a word recursivelly inside the folder

## Conquer of Completition extensions

- coc-eslint
- coc-git
- coc-go
- coc-java
- coc-jest
- coc-json
- coc-pairs
- coc-prettier
- coc-python
- coc-sh
- coc-tslint
- coc-yaml
