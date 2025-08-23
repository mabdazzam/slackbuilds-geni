This custom SlackBuild script builds [bspwm](https://github.com/baskerville/bspwm) 0.9.10.

```bash
sbopkg -i "bspwm lemonbar stalonetray dmenu xtitle sutils sxhkd xdo xdotool xautolock feh"
```

* [bspwm](https://github.com/baskerville/bspwm): window manager
* [lemonbar](https://github.com/LemonBoy/bar): status bar
* [stalonetray](https://github.com/kolbusa/stalonetray): system tray
* [dmenu](https://tools.suckless.org/dmenu/): program launcher
* [xtitle](https://github.com/baskerville/xtitle): window title
* [sutils](https://github.com/baskerville/sutils): status information
* [sxhkd](https://github.com/baskerville/sxhkd): keyboard shortcuts
* [xdo](https://github.com/baskerville/xdo): window actions
* [xdotool](https://github.com/jordansissel/xdotool): window reparenting for [tabc.sh](https://github.com/HuidaeCho/tabc.sh)
  * Install [tabc.sh](https://github.com/HuidaeCho/tabc.sh) for tab management: `wget https://raw.githubusercontent.com/HuidaeCho/tabc.sh/refs/heads/master/tabc.sh --directory-prefix ~/usr/local/bin`
* [tabbed](https://tools.suckless.org/tabbed/): window tabbing
* [xautolock](https://ibiblio.org/pub/Linux/X11/screensavers/): screen lock trigger
* [feh](https://github.com/derf/feh): wallpaper displayer
