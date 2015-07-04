# dmenu - dynamic menu

dmenu is an efficient dynamic menu for X. And originally developed by [suckless.org](http://dwm.suckless.org)
engineers.

This fork is patched with XFT, focus, fuzzymatch, opacity and other patches.
It also includes extra features like:

- **dmenu_app** executable, which solarizes dmenu and sorts results by most hits.
- **dmenu_run** uses **dmenu_app** to find executable and run it.
- **dmenu_workspace**

## Screenshot

![My image](https://raw.github.com/l3pp4rd/dmenu/master/dmenu.png)

## Requirements

In order to build dmenu you need the Xlib header files. See **config.mk** for details.

## Installation

Edit **config.mk** to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):

    make clean install

## Running dmenu

See the man page for details.

You can see my [path application menu configuration](https://github.com/l3pp4rd/dotfiles/blob/master/scripts/path_dmenu) as an example

