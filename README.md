st - simple terminal
--------------------
st is a simple terminal emulator for X which sucks less.


Requirements
------------
In order to build st you need the Xlib header files.


Installation
------------
Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

    make clean install


Running st
----------
If you did not install st with make clean install, you must compile
the st terminfo entry with the following command:

    tic -sx st.info

See the man page for additional details.

Credits
-------
Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.

Added patches:
- [x]https://st.suckless.org/patches/alpha/
- [x]https://st.suckless.org/patches/anysize/
- [x]https://st.suckless.org/patches/blinking_cursor/
- [x]https://st.suckless.org/patches/boxdraw/
- [x]https://st.suckless.org/patches/externalpipe/
- [x]https://st.suckless.org/patches/font2/
- [x]https://st.suckless.org/patches/iso14755/
- [x]https://st.suckless.org/patches/ligatures/
- [x]~https://st.suckless.org/patches/scrollback/~ cusotom patch from [vimBrowse](https://st.suckless.org/patches/vim_browse/) patch
- [x]https://st.suckless.org/patches/sync/
- [x]https://st.suckless.org/patches/vertcenter/
- [x]https://st.suckless.org/patches/w3m/
- [x]https://st.suckless.org/patches/workingdir/
- [x]https://st.suckless.org/patches/xclearwin/
- [x]https://st.suckless.org/patches/xresources/

- [x]https://st.suckless.org/patches/relativeborder/
