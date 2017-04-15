vimrc
=====

Update my vimrc

```

git clone https://github.com/thinegan/vimrc.git

$mkdir -p ~/.vim/colors

$cp ~/mygit/vimrc/vim/colors/obsidian.vim ~/.vim/colors/

$vim ~/.vimrc

set t_Co=256
set guifont=Consolas\ 10
colorscheme obsidian
syntax on
set paste
set nu
set hlsearch
set cursorline
set nowrap
set smartindent
set tabstop=4
set shiftwidth=4
set expandtab

" Show tab characters. Visual Whitespace.
set list
set listchars=tab:>-,trail:-

:wq

$reset

done...!
```

