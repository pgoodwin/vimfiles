# The Vim Configuration of Champions

## Installation

1. `git clone http://github.com/mutewinter/dot_vim.git` in your home folder.
2. `mv dot_vim .vim`
3. `cd .vim`
3. `rake vim:link` to make the .vimrc symbolic link.
4. Install [Vundle](https://github.com/gmarik/vundle) with `git clone http://github.com/gmarik/vundle.git bundle/vundle`
4. Run Vim and type `:BundleInstall` to install the plugins with Vundle.
5. Enjoy enhanced productivity, increased levitation, reduced watermelon-related accidents, and startling sex appeal.

## Screenshots


**MacVim**

[![MacVim](https://github.com/mutewinter/dot_vim/raw/master/screenshots/MacVim1_small.png)](https://github.com/mutewinter/dot_vim/raw/master/screenshots/MacVim1.png)


**Windows gVim**

[![Windows gVim](https://github.com/mutewinter/dot_vim/raw/master/screenshots/Windows1_small.png)](https://github.com/mutewinter/dot_vim/raw/master/screenshots/Windows1.png)


## Requirements

**Mac**

 * [MacVim](http://code.google.com/p/macvim/) - I'm currently using [snapshot 62](https://github.com/b4winckler/macvim/downloads)

**Windows**

 * [gVim](http://www.vim.org/download.php#pc) - I'm currently using [Wu Yongwei's](http://wyw.dcweb.cn) pre-compiled [gVim 7.3.333](http://wyw.dcweb.cn/download.asp?path=vim&file=gvim73.zip) because it has Ruby support and the latest patches

## Notes

Be sure to always edit the vimrc using `,v`, which opens the vimrc in the .vim folder. Vim has a nasty habit of overriding symlinks.

## Plugin Installation / Requirements

I may make this more verbose later, but for now, here's a list of plugins that require further installation:

 * [Command-T](https://github.com/wincent/Command-T) Needs compilation
 * [Fugitive](https://github.com/tpope/vim-fugitive) Requires Git to be installed
 * [syntastic](https://github.com/scrooloose/syntastic) Requires many different binaries installed depending on what filetypes you want it to check
 * [ack.vim](https://github.com/mileszs/ack.vim) Requires [ack](http://betterthangrep.com/) to be installed

## Plugin List

_Note: Auto generated by `rake plugins:readme`_


 * [vundle](https://github.com/gmarik/vundle)
 * [bufpos](https://github.com/mutewinter/bufpos)
 * [FuzzyFinder](https://github.com/vim-scripts/FuzzyFinder)
 * [ZoomWin](https://github.com/vim-scripts/ZoomWin)
 * [Command-T](https://github.com/wincent/Command-T)
 * [vim-space](https://github.com/spiiph/vim-space)
 * [vim-easymotion](https://github.com/Lokaltog/vim-easymotion)
 * [LustyJuggler](https://github.com/mutewinter/LustyJuggler)
 * [vim-indent-guides](https://github.com/mutewinter/vim-indent-guides)
 * [status.vim](https://github.com/dickeytk/status.vim)
 * [nerdtree](https://github.com/scrooloose/nerdtree)
 * [ir_black_mod](https://github.com/mutewinter/ir_black_mod)
 * [csapprox](https://github.com/godlygeek/csapprox)
 * [ColorV](https://github.com/Rykka/ColorV)
 * [browser-refresh.vim](https://github.com/mkitt/browser-refresh.vim)
 * [nerdcommenter](https://github.com/scrooloose/nerdcommenter)
 * [vim-surround](https://github.com/tpope/vim-surround)
 * [vim-speeddating](https://github.com/tpope/vim-speeddating)
 * [vim-fugitive](https://github.com/tpope/vim-fugitive)
 * [tabular](https://github.com/godlygeek/tabular)
 * [ack.vim](https://github.com/mileszs/ack.vim)
 * [IndexedSearch](https://github.com/vim-scripts/IndexedSearch)
 * [vim-session](https://github.com/xolox/vim-session)
 * [delimitMate](https://github.com/Raimondi/delimitMate)
 * [syntastic](https://github.com/scrooloose/syntastic)
 * [supertab](https://github.com/ervandew/supertab)
 * [AutoComplPop](https://github.com/vim-scripts/AutoComplPop)
 * [vim-ruby](https://github.com/vim-ruby/vim-ruby)
 * [cocoa.vim](https://github.com/msanders/cocoa.vim)
 * [vim-haml](https://github.com/tpope/vim-haml)
 * [vim-javascript](https://github.com/pangloss/vim-javascript)
 * [vim-coffee-script](https://github.com/kchmck/vim-coffee-script)
 * [vim-jquery](https://github.com/itspriddle/vim-jquery)
 * [vim-rails](https://github.com/tpope/vim-rails)
 * [taskpaper.vim](https://github.com/mutewinter/taskpaper.vim)
 * [vim-json](https://github.com/leshill/vim-json)
 * [L9](https://github.com/vim-scripts/L9)
 * [vim-repeat](https://github.com/tpope/vim-repeat)
