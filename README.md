# i3wm Configuration Files

This repository contains my personal configuration files for the [i3 window manager (i3wm)](https://i3wm.org/), a dynamic tiling window manager, on Arch Linux.

## Status Bar: Bumblebee-Status

![status_bar](https://github.com/Iona-Iobidze/i3wm_configurations/assets/73552612/d29966a0-22a1-4e6b-95e7-1e1c53c451e2)

For the status bar, I use [Bumblebee-Status](https://github.com/tobi-wan-kenobi/bumblebee-status), a modular, theme-able status line generator for the i3 window manager. I have customized the modules and created a personalized theme. However, the modules and the themes that are in this repository are the ones I use. To fully utilize the status bar, you need to install Bumblebee-Status from its [original source](https://github.com/tobi-wan-kenobi/bumblebee-status).

You can install Bumblebee-Status using pip, or clone it from the git repository. Here are the installation instructions:

**Using pip:**
pip install --user bumblebee-status

**Using git:**
git clone git://github.com/tobi-wan-kenobi/bumblebee-status cd bumblebee-status makepkg -sicr

After installing Bumblebee-Status, you can use the personalized theme provided in this repository.

## Configuration

The configuration file is located in the `~/.config/i3/` directory. If you want to use this configuration, clone this repository and copy the file to your `~/.config/i3/` directory.

Please note that you may need to adjust some settings to match your personal preferences and your system's specifications.

## Dependencies 
dex, xss-lock, pactl, kitty, brave, leafpad, blueman-manager, thunar, scrot, xclip, pavucontrol, brightnessctl, nitrogen, setxkbmap, bumblebee-status

## Contributions

Feel free to fork this repository, make changes, and submit a pull request if you think your changes could be beneficial to others.
