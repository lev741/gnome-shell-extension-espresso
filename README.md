# This extension is barely maintained anymore. New maintainers are welcome!

## gnome-shell-extension-caffeine

Fill the cup to inhibit auto suspend and screensaver.

This extension supports gnome-shell 3.4 to 3.38:

    * master: 3.36 -> 3.38
    * gnome-shell-3.32-3.34: 3.32 -> 3.34
    * gnome-shell-3.10-3.30: 3.10 -> 3.30
    * gnome-shell-before-3.10: 3.4 -> 3.8

![Screenshot](https://github.com/eonpatapon/gnome-shell-extension-caffeine/raw/master/screenshot.png)

![Preferences](https://github.com/eonpatapon/gnome-shell-extension-caffeine/raw/master/screenshot-prefs.png)

Empty cup = normal auto suspend and screensaver. Filled cup = auto suspend and
screensaver off.

## Installation from e.g.o

https://extensions.gnome.org/extension/517/caffeine/

## Installation from git

    git clone git://github.com/eonpatapon/gnome-shell-extension-caffeine.git
    cd gnome-shell-extension-caffeine
    ./update-locale.sh
    glib-compile-schemas --strict --targetdir=caffeine@patapon.info/schemas/ caffeine@patapon.info/schemas
    cp -r caffeine@patapon.info ~/.local/share/gnome-shell/extensions

Restart the shell and then enable the extension.
