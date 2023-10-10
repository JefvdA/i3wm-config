# i3wm-config
This is my personal i3wm configuration. Read the README for what I configured.

# Mod key
12: `set $mod Mod4`
-> The `windows` key is the mod key

# Terminal
48: `bindsym $mod+Return exec ~/.local/kitty.app/bin/kitty`
-> The default terminal to open is kitty

TODO : add link to my kitty config

# Movement keys
This is for changing focus, moving windows, and resizing.

The movement keys have been changed from jkl; to hjkl , the vim way.
The arrow keys have been disabled, this to force me in using the other keys.

# Split horizontal
88: `bindym $mod+g split h`
-> mod + g will split horizontal.

As h is now already used as a movement key, g is instead used to split horizontal.
