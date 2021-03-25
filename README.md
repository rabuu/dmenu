# dmenu - dynamic menu
dmenu is an efficient dynamic menu for X.


### Requirements
In order to build dmenu you need the Xlib header files.


### Installation
Edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):

`make clean install`


### Running dmenu
See the man page for details.

## edit by rabuu
Font and colors can be defined in Xresources with:
- dmenu.font
- dmenu.background
- dmenu.foreground
- dmenu.selbackground
- dmenu.selforeground

### used patches
- [password](https://tools.suckless.org/dmenu/patches/password/dmenu-password-4.9.diff)
- [xresources](https://tools.suckless.org/dmenu/patches/xresources/dmenu-xresources-4.9.diff)
