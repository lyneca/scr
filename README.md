# scr

A Maim/Slop screenshot tool

## Usage:

```bash
# Take and save a screenshot
$ scr

# Take a screenshot, copying to clipboard
$ scr -c

# Take and save a screenshot of a selected area or window using slop
$ scr -s

# Same as above, but copy to clipboard
$ scr -sc

# Same as -s, but add 10px of padding (for aesthetic purposes)
$ scr -p

# Same as above, but copy to clipboard
$ scr -pc
```

Screenshots are saved to ~/screenshots, and a symlink ~/screenshots/latest.png
is made whenever one is saved.
