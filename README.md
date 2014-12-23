#vim-abaqus
[VIM](http://www.vim.org/) filetype plugin for [Abaqus](http://www.3ds.com/products-services/simulia/) FE solver.

##Introduction

**What is Abaqus filetype plugin?** It is bunch of scripts for VIM to make easier work with Abaqus inputdeck.


**For whom is the plugin?** Well ... for anyone who works with Abaqus.
- If you do not work directly with Abaqus inputdeck but use a pre-processor you might try use VIM and the plugin.
- If you already familiar with Abaqus inputdeck but not use VIM the plugin can be a good reason to switch to VIM.
- If you already use VIM to work with Abaqus inputdeck you will love the plugin :-)

##Main plugin features
- Syntax highlighting
- Folding
- Keyword completion
- Useful commands, functions and mappings

####Syntax highlighting
With color syntax it's easier to navigate through a keyword file.

![vimAbaqusColorSyntax](https://raw.github.com/wiki/gradzikb/vim-abaqus/gifs/vimAbaqusColorSyntax.gif)

####Folding
Node & element table folding, no more never ending scrolling.

![vimAbaqusFolding](https://raw.github.com/wiki/gradzikb/vim-abaqus/gifs/vimAbaqusFolding.gif)

####Keyword completion
With keyword completion you can in easy way add a new Abaqus keyword or update existing one.

![vimAbaqusKeywordCompletion](https://raw.github.com/wiki/gradzikb/vim-abaqus/gifs/vimAbaqusKeywordCompletion.gif)

####Amplitude commands
You can use commands to operate with amplitude data directly in VIM.

![vimAbaqusAmpCommand](https://raw.github.com/wiki/gradzikb/vim-abaqus/gifs/vimAbaqusAmpCommand.gif)

####Commands, functions & mappings
The plugin has couple of great mappings/functions to make your work even faster.

##??

You are wondering how work with the plugin looks like? Take a look for [example]() on wiki pages.
##Installation

[Pathogen](https://github.com/tpope/vim-pathogen)

```
cd ~/.vim/bundle
git clone https://github.com/gradzikb/vim-abaqus
```

##Documentation

List of all plugin functions and detail information about them you will find in the plugin documentation.

`:help abaqus`

##License

The GNU General Public License

Copyright &copy; 2014 Bartosz Gradzik

