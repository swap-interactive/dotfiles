# dotfiles

My personal dev setup. Includes config files for tmux, NeoVim, zsh. Optimized to improve speed, and keep your hands on home row. Tries to reduce cost of context switch.

![tmux + NeoVim setup](https://i.imgur.com/ClYt4QO.png)

## colorscheme

iTerm2, NeoVim and tmux all use same color scheme *base16-default-dark*

# fonts

* Uses *Fira Code* without ligature. Disabling ligatures helps iTerm2 use gpu. 
* *Hack regular code nerd complete* for icons in iTerm2.

## tmux config

* tmux config extends [gpakosz/.tmux](https://github.com/gpakosz/.tmux). 
* changes to colorscheme to match *base16-default-dark* colorscheme. 
* applescript displays itunes and spotify track on status line

## NeoVim setup

* Works great for react development and tdd. Includes sensible plugins includes
    - Ultisnips
    - vim-react-snippets
    - vim-jest-snippets
    - istanbul
    - vim-test
    - vim-jsx
    - vim-prettier
    - vim-styled-components
* Switching to normal mode saves buffer
* Some notable plugins includes
    - vim-commentary
    - vim-surround
    - vim-repeat
    - netrw istead of NerdTree
    - FastFold
    - vim-stay
    - vimwiki
    - fzf
    - deoplete
    - vim-fugitive
    - EasyMotion
    - Ale for linting
    - vim-rails
    - vim-markdown
