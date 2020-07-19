# My Build of dwm

This is my build of [dwm](https://dwm.suckless.org/). Default terminal set to [Alacritty](https://github.com/alacritty/alacritty). Key bindings and other settings in `config.h`.

## Building 
Run `sudo make install && make clean`.

## Patches + fixes
* [actualfullscreen](https://dwm.suckless.org/patches/actualfullscreen/) with `super + shift + f`.
* Per tag specific window layouts with [pertag](https://dwm.suckless.org/patches/pertag/).
* Tag navigation via [shiftview](https://lists.suckless.org/dev/1104/7590.html) with `super + alt + h/l`.
* Signal support for dwmblocks via [statuscmd](https://dwm.suckless.org/patches/statuscmd/).
* [Sticky](https://dwm.suckless.org/patches/sticky/) with `super + s`.
* Gaps via [useless gap](https://dwm.suckless.org/patches/uselessgap/).
* Window [swallowing](https://dwm.suckless.org/patches/swallow/) (requires Linux/NetBSD).
* Manual window management with [stacker](https://dwm.suckless.org/patches/stacker/).
* Picom transparent border [fix](https://github.com/szatanjl/dwm/commit/1529909466206016f2101457bbf37c67195714c8)
