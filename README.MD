# dwm
Hello I am Josh Wright and this is my fork of suckless dwm,
see the OG at https://dwm.suckless.org,
thank you for coming to my ted talk

## Keybinds
- Alt in OG dwm is Super now
- Super+Enter for terminal (st)
- Super+Space for reorder master
- Super+Shift+Enter for toggle float
- Super+Q to quit window
- Super+B for Browser ($BROWSER env var)
- Super+E for Editor ($EDITOR env var)
- Super+Shift+B for bar toggle

## Patches
- [autostart-20161205](https://dwm.suckless.org/patches/autostart/)
- [fullgaps-6.2](https://dwm.suckless.org/patches/fullgaps/)
- [swallow-20200522](https://dwm.suckless.org/patches/swallow/)

## Original Suckless Readme

```
dwm - dynamic window manager
============================
dwm is an extremely fast, small, and dynamic window manager for X.


Requirements
------------
In order to build dwm you need the Xlib header files.


Installation
------------
Edit config.mk to match your local setup (dwm is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dwm (if
necessary as root):

    make clean install


Running dwm
-----------
Add the following line to your .xinitrc to start dwm using startx:

    exec dwm

In order to connect dwm to a specific display, make sure that
the DISPLAY environment variable is set correctly, e.g.:

    DISPLAY=foo.bar:1 exec dwm

(This will start dwm on display :1 of the host foo.bar.)

In order to display status info in the bar, you can do something
like this in your .xinitrc:

    while xsetroot -name "`date` `uptime | sed 's/.*,//'`"
    do
    	sleep 1
    done &
    exec dwm


Configuration
-------------
The configuration of dwm is done by creating a custom config.h
and (re)compiling the source code.
```
