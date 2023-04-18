The X11 window manager for the tiger desktop environment.

Dependencies:
* The same as tinywm - which is what this is based on.

Install instructions:
* Install the dependencies
* Run the following commands:
`git clone https://github.com/Tiger-Desktop-Environment/Tiger-Window-Manager`
`cd Tiger-Window-Manager/src`
`make`
`sudo make install`

Lastly, open up your ~/.xinitrc file, and add this line to the top:
`exec Tiger-Window-Manager`

You will then be able to run the window manager using `startx`.

Todo:
* Add a config file in c where the super key is defined
* Add a keyboard shortcut to quit the whole window manager (with an alert)
* Add wallpaper support to the window manager
* Open a terminal when super+enter is pressed
* Make windows tile by default
* Allow windows to be floating
* Implement full screen mode (stage manager)
* Allow it to work even if window bars are disabled in the config file
* Add window decorations and borders to the window
