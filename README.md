# stx - simple terminal x

st is a simple terminal emulator for X which sucks less.

stx is a fork of st which sucks even less.

Based on 0.6, because reasons. If you need newer, feel free to refer to the original.

* http://st.suckless.org

* http://git.suckless.org/st

## Installation


    git clone git@github.com:nathanchere/stx.git /tmp/stx
    make
    sudo make install

Now run with `st`

NOTE: you still need `freetype2` headers for unicode support, and transparency
 will only work when running a compositor like `compton`.

## Changes from st

* Background transparency support
* Background opacity set to ~90%
* Copy to clipboard on select
* Font set to Iosevka Nerd Font (https://github.com/ryanoasis/nerd-fonts)
* Tab size reduced from 8 spaces to 2
* Default shell changed from `bash` to `fish`
* Character horizontal kerning scaled to 0.5
* Word delimiters extended to: ` ``'"()[]{}<>_-:;,.`

