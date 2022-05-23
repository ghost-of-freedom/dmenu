[dmenu](https://tools.suckless.org/dmenu/) with following patches applied:
- [solarized-light](https://tools.suckless.org/dmenu/patches/solarized/)
- [case-insensitive](https://tools.suckless.org/dmenu/patches/case-insensitive/)
- [center](https://tools.suckless.org/dmenu/patches/center/)
- [border](https://tools.suckless.org/dmenu/patches/border/)
- [mouse-support](https://tools.suckless.org/dmenu/patches/mouse-support/)

Customizations:
- dmenu_run is modified to use `#!zsh` shebang (for use in guix), source ~/.zshrc and use functions and aliases as well as programs
- normal and selected text colors are changed for better visibility
- IBM Plex is set as the default font, with the default dmenu font set as fallback