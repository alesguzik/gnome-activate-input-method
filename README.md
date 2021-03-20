# gnome-activate-input-method

This script allows to list input methods in gnome, and to switch to an input method from a command line.
I use it in conjunction with Gnome's custom keyboard shortcuts (Settings → Keyboard Shortcuts → + (at the very bottom)).

## How to use

List input methods:

```
$ gnome-activate-input-method
```

Switch to input method:

```
$ gnome-activate-input-method 1
```

## Requirements

* GNOME Shell (tested on 3.38.2)
* ruby, any version (tested on 2.6.6p146)
