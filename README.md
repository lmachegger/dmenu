# My dmenu (dynamic menu) build


![Screenshot of my desktop](https://github.com/lmachegger/dwm/blob/master/screenshot.png) 
Dmenu is an efficient dynamic menu for X. This is my personal build of dwm. I used the following patches in this build:
+ lineheight (adds additional parameter -h for setting the height of dmenu)


## Requirements
In order to build dmenu you need the Xlib header files.


## Installation
Edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):

    make clean install


## Running dmenu
See the man page for details.
