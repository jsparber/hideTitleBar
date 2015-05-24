hideTitleBar
============

Removes Title Bar of legacy (non-headerbar) application windows if they are maximized.

**Works best in combination with the [Status Title Bar Extension](https://github.com/emerinohdz/status-title-bar)**, which will show the window title in the top bar for maximized windows. That way the window title is visible even though the title bar is hidden. You can install it from [GNOME Extension](https://extensions.gnome.org/extension/59/status-title-bar/).

**Meta-themes don't work anymore in Gnome 3.16 use instate the patched mutter version [mutter-hide-legacy-decorations](https://github.com/jsparber/mutter-hide-legacy-decorations)**

##Usage

1. Navigate to the system theme folder.
`
cd /usr/share/themes
`
2. Clone this repository (requires root to write in the system folder).
`
sudo git clone https://github.com/jsparber/hideTitleBar
`
3. Set 'hideTitleBar' as your window theme in GNOME Tweak Tool.

4. Enjoy your extra screen space!

5. **Optional**: Install the [Status Title Bar Extension](https://extensions.gnome.org/extension/59/status-title-bar/) from the GNOME Extensions website.
