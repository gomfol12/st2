# st
My second fork of st

# patches
alpha
selectionbg alpha
anysize
blinking cursor
bold is not bright
boxdraw
csi 22 23
delkey
desktopentry
fix keyboard input
font2
osc 10 11 12
selectioncolors
title parsing
undercurl
vertcenter
wide glyphs truncation fix
xclearwin
live reload of xresources

# Install
        git clone https://github.com/gomfol12/st2.git
        cd st2
        sudo make install

# Live reload
        kill -SIGUSR1 pid_of_st_process
## Live reload all instances of st
        pidof st | xargs -r kill -SIGUSR1

# Configuration and Keybinds
        see config.def.h

# Thanks
[suckless project](https://suckless.org/)
[xst project for the live reload patch](https://github.com/gnotclub/xst)
[Dreomite for the wide glyphs truncation fix](https://github.com/Dreomite)
