# My build of st (simple/suckless terminal)

## Patches applied
1. [boxdraw](https://st.suckless.org/patches/boxdraw/) for custom rendering of lines/blocks/braille characters of gapless allignment.
2. [externalpipe](https://st.suckless.org/patches/externalpipe/) for reading and writing st's screen through pipe (to make luke smith's copyoutput & urlhandler scripts work)
3. [font-2](https://st.suckless.org/patches/font2/) for spare font support.
4. [anysize](https://st.suckless.org/patches/anysize/) to fix the unwanted gap in dwm (gives st the ability to resize in any size)
5. [scrollback](https://st.suckless.org/patches/scrollback/) support for both mouse and keyboard in st
6. [alpha](https://st.suckless.org/patches/alpha/) patch for transparency
7. [xresources](https://st.suckless.org/patches/xresources/) patch for reading the xresources (pywal and stuff you know)
## Bindings
+ **scrollback** with <kbd>alt-j/k</kbd> or <kbd>alt-pageup/down</kbd> or just scroll with mouse.
+ **vim-bindings**: scroll up/down in history with <kbd>alt-k</kbd> and <kbd>alt-j</kbd>.
+ **zoom/change font size**: <kbd>control-shift-(pageup/down)/(+/-)</kbd>.
+ **transparency**: 
    - increase with <kbd>alt+s</kbd>
    - decrease with <kbd>alt+a</kbd>
    - reset with <kbd>alt+m</kbd>
