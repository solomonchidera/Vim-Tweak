## Vim customisation

# create a file with " .vimrc "as a name and paste all this script there
save the file and open vim

on normal mode press esc to be sure, then enter this command :Pluginistall to install all the necessary plugin.

# Guildline coming soon..

" Disable compatibility with vi which can cause unexpected issues.
set nocompatible

" Enable type file detection. Vim will be able to try to detect the type of file in use.
filetype on

" Enable plugins and load plugin for the detected file type.
filetype plugin on

" Load an indent file for the detected file type.
filetype indent on


" Highlight cursor line underneath the cursor horizontally.
set cursorline

" Highlight cursor line underneath the cursor vertically.
set cursorcolumn

" Do not let cursor scroll below or above N number of lines when scrolling.
set scrolloff=10

"------------------------NERDTree-----------------
set nocompatible
filetype off

" Plugin Manager - Vundle
set rtp+=~/.vim/bundle/Vundle.vim
call vundle#begin()

" ... your other plugins ...

" NERDTree Plugin
Plugin 'preservim/nerdtree'

" ... your other plugins ...

call vundle#end()
filetype plugin indent on

"------------------------------NERDTree----------

" Do not wrap lines. Allow long lines to extend as far as the line goes.
set nowrap


" Ignore capital letters during search.
set ignorecase

" Override the ignorecase option if searching for capital letters.
" This will allow you to search specifically for capital letters.
set smartcase

" Show the mode you are on the last line.
set showmode

" Show matching words during a search.
set showmatch

" Use highlighting when doing a search.
set hlsearch

" Set the commands to save in history default number is 20.
set history=1000

" Enable auto completion menu after pressing TAB.
set wildmenu

" Make wildmenu behave like similar to Bash completion.
set wildmode=list:longest

" There are certain files that we would never want to edit with Vim.
" Wildmenu will ignore files with these extensions.
set wildignore=*.docx,*.jpg,*.png,*.gif,*.pdf,*.pyc,*.exe,*.flv,*.img,*.xlsx


" Enable automatic brace and bracket completion
inoremap { {<CR>}<Esc>O
inoremap ( ()<Left>
inoremap [ []<Left>
inoremap < <><Left>
inoremap " ""<Left>
inoremap ' ''<Left>

" Enable line-wise visual block selection with Ctrl-v
set selection=exclusive
set selectmode=mouse,key

"-------------------------------------------

" VIM Configuration Profile

" Use the PowerLine plugin. Change Python directory if needed.
set rtp+=$HOME/.local/lib/python3.8/site-packages/powerline/bindings/vim/

" Always show statusline
set laststatus=2

" Use 256 colours (Use this setting only if your terminal supports 256 colours)
set t_Co=256

" Always show the command as it is being typed.

set showcmd

set tabstop=8 shiftwidth=8

set autoindent
set number
set pastetoggle=<F2>
let g:codeium_manual = v:true
set statusline+=\{…\}%3{codeium#GetStatusString()}
set smartindent
set backspace=indent,eol,start
set cindent

syntax on



" PLUGINS ---------------------------------------------------------------- {{{

" Plugin code goes here.

" }}}


" MAPPINGS --------------------------------------------------------------- {{{

" Mappings code goes here.

" }}}


" VIMSCRIPT -------------------------------------------------------------- {{{

" This will enable code folding.
" Use the marker method of folding.
augroup filetype_vim
    autocmd!
    autocmd FileType vim setlocal foldmethod=marker
augroup END

" More Vimscripts code goes here.

" }}}


" STATUS LINE ------------------------------------------------------------ {{{

" Status bar code goes here.

" }}}
