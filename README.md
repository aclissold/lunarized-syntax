Lunarized
=========
A fork of the Atom version of the famous [Solarized] theme—with a moonlit aura.

Design Decisions
----------------

I love the harmonious blend of Solarized's accent colors and how well they all fit together.
After all, the most important facet of a syntax theme is to be able to easily differentiate
the different tokens in source code. And Solarized manages to achieve this while still
looking beautiful.

However, the dark blue "in the shade of a tree" background (as well as the yellow
morning-sun variant) break this neutrality. Lunarized fixes it by completely
desaturating the base colors as well as lowering each of their brightnesses by 15%.
Plain text has also been bumped from the base0 to base1 color to compensate.

Installation
------------

### To get the Atom package:

* Bring up Settings via `cmd-,`
* Go to the Themes page
* Search for Lunarized and install

### To get the Xcode colorscheme:

    mkdir -p ~/Library/Developer/Xcode/UserData/FontAndColorThemes
    cp Lunarized.dvtcolortheme !:2

### To get the Vim colorscheme:

With [pathogen]:

    cd ~/.vim/bundle
    git clone https://github.com/aclissold/lunarized-syntax

Without pathogen:

    mkdir -p ~/.vim/colors
    cd ~/.vim/colors
    curl -O https://raw.githubusercontent.com/aclissold/lunarized-syntax/master/lunarized.vim

Screenshots
-----------

![Atom Screenshot](https://cloud.githubusercontent.com/assets/4397642/5238939/34d4b03c-789c-11e4-9aee-7184b902f848.png)
![Vim Screenshot](https://cloud.githubusercontent.com/assets/4397642/5238940/3729b8aa-789c-11e4-9ebb-b161cbcee591.png)

[Solarized]: http://ethanschoonover.com/solarized
[pathogen]: https://github.com/tpope/vim-pathogen
