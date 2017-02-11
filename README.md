# macos-rollover-window-controls
Remove the traffic light window controls from macOS windows unless they're being hovered over.

Made using [ThemeEngine](https://github.com/alexzielenski/ThemeEngine).

## Installation
**SIP must be disabled for this to work.**

**If you're using the Graphite appearance (black & white) not the default Blue appearanced (colored), the equivalent files can be found [here](https://github.com/wallace-aph/osxrice).**

If you're using macOS' Dark Mode (you have "Use dark menu bar and Dock" checked in System Preferences):

1. Open `/System/Library/CoreServices/SystemAppearance.bundle/Contents/Resources/` in Finder.
2. Backup the existing `DarkAppearance.car` file somewhere.
3. Copy the `DarkAppearance.car` file from this repository into the folder.
4. Log out/log in to refresh it.

If you're not using Dark Mode:

1. Open `/System/Library/CoreServices/SystemAppearance.bundle/Contents/Resources/` in Finder.
2. Backup the existing `SystemAppearance.car` file somewhere.
3. Copy the `SystemAppearance.car` file from this repository into the folder.
4. Log out/log in to refresh it.

## Screenshots
Normal (unhovered):

![Normal (unhovered)](http://i.imgur.com/PuxSVdA.png)

Hovered:

![Hovered](http://i.imgur.com/xcSFqaU.png)

Gif demo:

![Gif demo](http://i.imgur.com/xa7DCgn.gif)