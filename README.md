# Hyprland-Waybar-Files
Just the files I used for my waybar. 
Files are highly customizable, and the tutorial for adding/removing app icons is also included.


# How to install:
  * Download the file from this repository
  * Extract it into your ~/.config/ directory

# How to set it up:
  * Go into your main hyprland configuration file (most are at ~/.config/hypr/hyprland.conf)
  * Make sure your waybar is set to autostart, by adding this line:
      * exec-once = waybar

# How to add app icons:
  * Go into your ~/.config/waybar/config file and look for the section that says: "modules-left", "modules-center", and "modules-right".
  * Go to modules-right, and add your custom app, by naming it "custom/<app>" (let <app> be your name for it).
  * Next, add the configuration for it. To do this add the following lines:
    "custom/<app>": {
      "format": "<icon>",      (more info on this below)
      "tooltip": <app-name, with capital letter>,
      "on-click": <app-name>
      }
# To add an app icon photo:
  * Go to www.nerdfonts.com/cheat-sheet
  * Search for the app you want an icon for
  * Copy the UTF, and put that where <icon> is.

# To delete an app icon:
  * Go into your ~/.config/waybar/config file and look for the section that says: "modules-left", "modules-center", and "modules-right".
  * Go to modules-right, and delete the "custom/<app>" for whichever app you want removed.
────୨ৎ────────୨ৎ────────୨ৎ────────୨ৎ────────୨ৎ────────୨ৎ────

# All credits/inspos are linked down below:

https://www.reddit.com/r/unixporn/comments/1lya9uw/hyprland_gruvbox_is_superior/
