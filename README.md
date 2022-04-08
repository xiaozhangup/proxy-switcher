proxy-switcher
==============

A Gnome Shell Extension to switch the proxy mode between the pre-defined modes "none", "manual" and "automatic". The extension adds a menu to the aggregate menu bar (i.e. the main menu bar) directly below the network section like this:

![Screenshot](screenshot.png)

The gnome extensions page is [here](https://extensions.gnome.org/extension/771/proxy-switcher/). Install using the [extensions website](https://extensions.gnome.org/extension/771/proxy-switcher/) or alternatively follow the manual installation instructions below.

Any contributions are very welcome (e.g. new features, translations, bug fixes etc) and I will consider all feature requests. Please submit an issue/pull request or email me at `tomflannaghan@gmail.com`.

## Installation

I recommend using the gnome extensions site but this is not always up to date. To get the latest version, do

    git clone https://github.com/xiaozhangup/proxy-switcher.git
    cd proxy-switcher
    make build
    make install

## Translations

I have added the translations I found in the [`gnome-control-center`](https://git.gnome.org/browse/gnome-control-center) project to the extension (these are the translations used in the "Network Settings" menu). I've also used the "Network Settings" desktop shortcut to translate that phrase.
