# dracula-dotfiles
This is my personal rice, built on top of the endeavourOS i3wm configs

![Dracula_Rice](https://github.com/Heoutera/dracula-dotfiles/assets/138242609/e8961a69-f1f2-4384-9599-7d2e13e45770)

## Requirements
1. Nerdfonts - This setup is using BitstromWera Nerd fonts. I highly recommend already having that installed
2. Xed text editor - I have a cheatsheet for keybindings set to SUPER+F1, useful when starting out. Since it uses Xed to open the file, I recommend having that installed
3. i3lock-color - Needed for the dracula lock I'm using
4. Kitty - Keybinds and the terminal button on the bar both assume you're using kitty

## Usage
- SUPER+m to show/hide the i3bar
- SUPER+F1 or click "HELP" in the bar for more info on keybindings
- Make the .sh files inside .configs/i3/scripts executable for random wallpaper and toggleable i3bar
## A word of warning
This setup has customized keybindings, and they're not close to default i3. I recommend you make your own config_keybindings file with your personal choices or check the keybindings in the config file before using these configs. 
Also be aware that keybindings related to workspace are **NOT** in config_keybindings, they're in config_workspaces (since my workspace choices would break otherwise).
