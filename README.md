# wow-keyboard

Wows when you type. 

A collaboration between [Me](http://github.com/auxiliary/), [Alok Hota](http://github.com/ahota/), [Tanner Hobson](http://github.com/player1537) and [Natalie Bogda](http://github.com/nbogda/). 

This is a fork of linux-clicky [![Flattr this git repo](http://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=skkeeper&url=https://github.com/skkeeper/linux-clicky&title=linux-clicky&language=&tags=github&category=software)

## Usage

Run the main.py file and it will automaticly detect your keyboards and start *clickytty click*.

**Because of the way the script detects the keypresses (by tying itself to the event file in Linux, just like a keylogger would do) it requires root access**

If you are worried about malicious code, the script is pretty small you can easily read it in five minutes, so feel free to.

## Dependencies

- Linux (tested under Ubuntu 12.04)
- Python (tested under 2.7.3)
- SoX (in debian based systems install by typing "sudo apt-get install sox");

## License

The code is under the supplied MIT license, therefore it's completely open source.

evdev.py (by Micah Dowty <micah@navi.cx>) is included under the terms of the GPLv2. Thanks to Micah Dowty for writing this module since without it this script would not be possible, or at least not as easy to code.
