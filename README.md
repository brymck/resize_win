resize_win
==========

Just a quick little Ruby script to help with resizing windows in Mac OS X for
screenshots, screencasts, etc.

Installation
------------

### Global

    sudo curl https://raw.github.com/brymck/resize_win/master/resize_win > /usr/bin/resize_win
    sudo chmod +x /usr/bin/resize_win

### Local

You can of course also save the script anywhere in your `$PATH`:

    curl https://raw.github.com/brymck/resize_win/master/resize_win > ~/bin/resize_win
    chmod +x ~/bin/resize_win

Usage
-----

If you wanted to be prompted for size, just run this:

    resize_win

You can also specify your own resolution:

    resize_win 1280 720

And even the name of the Application:

    resize_win Terminal 1280 720
    resize_win "Google Chrome" 1440 900
    resize_win MacVim 720p
