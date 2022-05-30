# Pawelee.github.io

## Vim tips

### How to save super fast in vim using ,w (leader w)
let mapleader = ","
" [ Leader key save and exit vim ]
nmap <Leader>w :w<CR>
  
### How to compile C from vim
autocmd FileType c map <buffer> <F8> <esc>:w<CR>:exec '!gcc'  shellescape(@%, 1)<CR>
autocmd FileType c imap <buffer> <F8> <esc>:w<CR>:exec '!gcc' shellescape(@%, 1)<CR> 

## Python 
  
### Making a python program with time constrained license
