# shotty
![shotty icon](icons/shotty.png)

Simple desktop screenshot app, written in Python with PyQt5

## Features

- Whole screen screenshot
- Region screenshot
- Save to disk
- Copy to clipboard
- Run in the background
- Hotkey

### Region screenshot

Press 'Print', select your area, rename, and hit save!

![region screenshot](readme/region_screenshot.gif)

### Icon tray menu - full screenshot

![icon tray menu](readme/icon_tray_menu_fullscreenshot.gif)

## Requirements

### Windows:

Get pyHook for your python version here:

    https://www.lfd.uci.edu/~gohlke/pythonlibs/#pyhook

## Troubleshoot

### Linux

If you get the error:
    [Errno 2] No such file or directory: 'notify-send': 'notify-send'
try:
    sudo apt-get --reinstall install libnotify-bin notify-osd

## Author

- Victor Meunier - victormeunier.dev@gmail.com

Want to support me? Buy me a coffee!
<a href="https://www.buymeacoffee.com/mreliptik" target="_blank"><img src="https://bmc-cdn.nyc3.digitaloceanspaces.com/BMC-button-images/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: auto !important;width: auto !important;" ></a>
