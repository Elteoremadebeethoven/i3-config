# Config steps

## Dependencies

You need to install:

* font-awesome
* picom
* [greenclip](https://github.com/erebe/greenclip)
* rofi
* rofi-calc
* rofi-emoji
* rofi-file-browser-extended
* flameshot
* sysstat
* gpick

## Clone repo

Clone repo to `~/.config`

## Link scripts

```
ln -s $HOME/.config/i3/bin/main_dirs $HOME/.local/bin/main_dirs
ln -s $HOME/.config/i3/bin/i3exit $HOME/.local/bin/i3exit
ln -s $HOME/.config/i3/bin/pick-color $HOME/.local/bin/pick-color
ln -s $HOME/.config/i3/bin/rofi-clip-images $HOME/.local/bin/rofi-clip-images
ln -s $HOME/.config/i3/bin/rofi-open-terminal $HOME/.local/bin/rofi-open-terminal
ln -s $HOME/.config/i3/bin/picom.conf $HOME/.config/picom.conf
```

And add the permissions to the files inside `bin` folder.
