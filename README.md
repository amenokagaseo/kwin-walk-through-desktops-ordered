# kwin-walk-through-desktops-ordered

KWin script to walk through desktops, sorted by desktop name.

This is a modified version of [rflafla/kwin-walk-through-desktop](https://github.com/rflafla/kwin-walk-through-desktop) that hides the GUI for use with the "Desktop Change OSD" effect included with KDE 6, which shows desktops in their proper position on-grid. This was mostly made for personal reasons, as the other alternative (scripted with JS) doesn't work very well if at all at times.

## Installation

The included Makefile contains targets : install, uninstall and upgrade.

## Shortcuts

By default the addon uses <kbd>Meta</kbd>+<kbd>Tab</kbd> and <kbd>Meta</kbd>+<kbd>Shift</kbd>+<kbd>Tab</kbd>.

Shortucts can be changed in `System Settings` -> `Shortcuts` if you search for "Walk Through Desktops".
