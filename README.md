## About

Flatland for Emacs is a direct port of the popular
[Flatland](http://github.com/thinkpixellab/flatland) theme for Sublime Text.
developed by Jani Nurminen. 

This theme uses the new built-in theming support available starting
with Emacs 24.

![Flatland Emacs Screenshot](http://raw.github.com/gregchapple/flatland-emacs/master/flatland-emacs.png)

### NOTE 
This is still under development. Currently, this has only been tested in the GUI version of emacs, and not in the terminal.
If you find any issues, please report them on the Github Issue Tracker. Pull requests welcome :)

## Installation

### Manual

Download `flatland-theme.el` to the directory `~/.emacs.d/themes/`. Add this to your
`.emacs`:

```lisp
(add-to-list 'custom-theme-load-path "~/.emacs.d/themes/")
```

Now you can load the theme with the interactive function `load-theme` like this:

`M-x load-theme RET flatland`

