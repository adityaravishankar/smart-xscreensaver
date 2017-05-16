# smart-xscreensaver
Simple script to deactivate XScreenSaver while video (or audio) is running (in a browser or video player)

### Features
* Works for browser video as well as apps like VLC
* Will allow XScreenSaver if video is paused
* Will work on windowed or full screen mode
* Should detect change in XScreenSaver timeout and adjust polling interval to minimize unnecessary running

## Installation 

1. Download smart-xscreensaver

```bash
sudo wget https://raw.githubusercontent.com/adityaravishankar/smart-xscreensaver/master/smart-xscreensaver -O /usr/local/bin/smart-xscreensaver
```

2. Make smart-xscreensaver executable
```bash
sudo chmod +x /usr/local/bin/smart-xscreensaver
```

3. Load smart-xscreensaver on boot using your OS startup application editor.

### License

Copyright (c) 2017 [Aditya Ravi Shankar](https://www.adityaravishankar.com)

Released under the [MIT License](https://github.com/adityaravishankar/smart-xscreensaver/blob/master/LICENSE).