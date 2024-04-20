# Zenity fork (GTK3)

This fork is a modified version of Zenity 3.44 that removes the hardcoded paths that zenity has, it is used to make this [AppImage](https://github.com/Samueru-sama/Zenity-GTK3-AppImage)

Credit and big thanks goes to @aferrero2707 for the patches (I tried to merge them here but couldn't lol). 

# Zenity

This is Zenity - a rewrite of gdialog, the GNOME port of dialog
which allows you to display dialog boxes from the commandline
and shell scripts.

This software is licensed under the LGPL.

Zenity is part of the GNOME Extra Apps family and is not a core
GNOME application.

## Dependencies

* gtk+-3.16

## Optional Dependencies

* libnotify (for desktop notification support)
* webkit2gtk-4.1 (for HTML support)

Please see the meson.build file for minimal versions required
for optional dependencies, and meson_options.txt for the build
options to enable these features if desired.
