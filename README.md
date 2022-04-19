# leg7 build of st

This is my build of the suckless terminal, a terminal emulator available at https:/st.suckless.org

My build of st is based on version 0.8.5 (2022-01-07)

## Features

St is a suckless utility so the configuration file is just a header file, in this case config.def.h.
I don't have any particular settings for st but if you are looking for any they will be located in this file for sure.

### Here is a list of features/patches of my build:

* st can be resized to any size to avoid unsightly gaps
* scrollback support with shift+pageup shift+pagedown
* boxdraw and ligatures for pretty fonts and characters
* copyurls that span multiple lines with alt+l and enter
* nord theme
* ordered patches for automatic patching with portage (gentoo)

## Install guide

```
git clone https://git.leonardgomez.xyz/leg7/st
cd st
make Install
```

Please refer to the st documentation for more details
