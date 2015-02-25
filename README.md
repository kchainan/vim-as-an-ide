# Vim as an IDE

This repository contains a sample vimrc that walks you through the changes at
each step so that you can gain an understanding of what's going on (rather than
just copying someone's vimrc!).

## How to use this repository

Each step of the workshop that this repository was originally used for is a
commit in this repository. Use the [list of all commits][master] to peruse what
happened at each step. You'll see a (sometimes lengthy) explanation of what
happened, and then the diff(erence) of exactly what changed from step-to-step.

[master]: https://github.com/jez/vim-as-an-ide/commits/master

Here's a table of contents for convenience

### Table of Contents

*  [Create vimrc file](https://github.com/jez/vim-as-an-ide/commit/0673f0c)
*  [Add some general settings](https://github.com/jez/vim-as-an-ide/commit/dff7da3)
*  [Enable the mouse](https://github.com/jez/vim-as-an-ide/commit/fc77b04)
*  [Set up Vundle boilerplate](https://github.com/jez/vim-as-an-ide/commit/1186be2)
*  [Make Vim look good](https://github.com/jez/vim-as-an-ide/commit/457f2e2)
*  [Plugins NERDTree and NERDTree Tabs](https://github.com/jez/vim-as-an-ide/commit/b7ff90c)
*  [Plugin Syntastic](https://github.com/jez/vim-as-an-ide/commit/144f979)
*  [Plugins vim-easytags and tagbar](https://github.com/jez/vim-as-an-ide/commit/fd2c49c)
*  [Plugin ctrlp](https://github.com/jez/vim-as-an-ide/commit/80db74f)
*  [Plugin A.vim](https://github.com/jez/vim-as-an-ide/commit/8d4223f)
*  [Plugins vim-gitgutter and vim-fugitive](https://github.com/jez/vim-as-an-ide/commit/1e5757e)
*  [Plugin delimitMate](https://github.com/jez/vim-as-an-ide/commit/2fe0507)
*  [Plugin vim-superman](https://github.com/jez/vim-as-an-ide/commit/b185e9f)
*  [Plugin vim-tmux-navigator](https://github.com/jez/vim-as-an-ide/commit/44f5225)
*  [Syntax plugins](https://github.com/jez/vim-as-an-ide/commit/5ba534e)
*  [Add all the extra plugins that I use](https://github.com/jez/vim-as-an-ide/commit/9089a95)


## Installation Instructions

If you just want to use this file as your vimrc, no questions asked, 

1. Move your ~/.vimrc file and ~/.vim folder somewhere else for now.
2. [Download Vundle](https://github.com/jez/vim-as-an-ide/1186be2)
3. [Change your terminal colorscheme to solarized](https://github.com/jez/vim-as-an-ide/457f2e2)
4. [Install a patched font](https://github.com/jez/vim-as-an-ide/457f2e2)
5. Download the file [vimrc.vim](/vimrc.vim) and rename it to ~/.vimrc
6. Run `vim +PluginInstall +qall`
7. ???
8. Profit!

But you should really look through the steps for more information about what went down.


## Now that I'm a plugin master, I want to...

- find more plugins!
    - <http://vimawesome.com/>
- learn how to actually use Vim!
    - `vimtutor`
    - [Learning Vim in 2014][1]
        - In particular, [Vim as Language][2]
- customize my Vimrc!
    - Look at these examples
        - <https://github.com/jez/dotfiles/blob/master/vimrc>
        - <https://github.com/bezi/dotfiles/blob/master/vimrc>
    - See the [first][1] and [last][3] links
- write my own Vim plugin!
     - [Learn Vimscript the Hard Way][3]

[1]: http://benmccormick.org/learning-vim-in-2014/
[2]: http://benmccormick.org/2014/07/02/learning-vim-in-2014-vim-as-language/
[3]: http://learnvimscriptthehardway.stevelosh.com/

