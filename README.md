# capscr

Capture screen or window in X using shell scripts

Dependencies:

1. xprop utility to find active window.
2. ImageMagick, specifically 'import' utility.
3. xclip to copy screenshot to clipboard.

Optional dependencies:

1. notify-send
2. zenity
3. kdialog

Usage:

    ./capscr screen         # save screen image to $HOME/capscr
    ./capscr window         # save active window image to $HOME/capscr
    ./capscr screen-to-clip # copy screen image to clipboard
    ./capscr window-to-clip # copy active window image to clipboard
    ./capscr                # same as screen-to-clip
