# dmenu - dynamic menu

dmenu is an efficient dynamic menu for X. And originally developed by [suckless.org](http://dwm.suckless.org)
engineers.

This fork is for custom personal use and includes extra features like:

- **XFT** support.
- **PATH** executable scan as an option.
- Historical hit based sorting through option.

## Screenshot

![My image](https://raw.github.com/l3pp4rd/dmenu/master/dmenu.png)

## Requirements

In order to build dmenu you need the Xlib header files.

## Installation

Edit **config.mk** to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):

    make clean install

## Running dmenu

See the man page for details.

You can see my [path application menu configuration](https://github.com/l3pp4rd/dotfiles/blob/master/scripts/path_dmenu) as an example

