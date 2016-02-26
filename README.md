vim-monokai
===========

Refined monokai color scheme for vim. 

* The colour palette from [sickill/vim-monokai](https://github.com/sickill/vim-monokai). 
* And was a self modifyed version from [crusoexia/vim-monokai](https://github.com/crusoexia/vim-monokai), thankyou verymuch for the effort.

Install
-------

### [Vundle](https://github.com/gmarik/Vundle.vim) (recommend)

    Plugin 'LockonS/vim-monokai'

### No plugin manager way

Download the syntax/monokai.vim file and copy it into your __~/.vim/syntax/__ folder.

__Note:__

If you previously use [sickill/vim-monokai](https://github.com/sickill/vim-monokai) or [crusoexia/vim-monokai](https://github.com/crusoexia/vim-monokai), you need to remove it first to install this one, because the file series inherit the same name "monokai" which could cause conflicts.

Usage
-----

Type below command in your vim or save it in your vimrc:

    colorscheme monokai

Configuration
-------------

### Italic
    
If you are using a font which support italic, you can use below config to enable the italic form:

    let g:monokai_italic = 1

### Thick window border

The default window border is narrow dotted line, use below config to turn on the thick one:

    let g:monokai_thick_border = 1

