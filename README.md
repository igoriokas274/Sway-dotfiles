# Sway-dotfiles
Sway WM with monochrome color palette configuration files

![sway-monochrome-personal.png](/assets/sway-monochrome-personal.png)
## System
  - Ubuntu 23.10
## Dependencies
- ranger
- waybar
- wofi
- mako
- kitty
- alacritty
- blueman-applet
- nm-applet (network manager)
- grim
- grimshot
- ffmpeg
- Fonts
	- [Roboto](https://fonts.google.com/specimen/Roboto)
	- [Font Awesome](https://fontawesome.com/download) // Free For Desktop
- Themes
	- [ Graphite-gtk-theme](https://github.com/vinceliuice/Graphite-gtk-theme)
	- [Tela-circle-icon-theme](https://github.com/vinceliuice/Tela-circle-icon-theme)
## Baseg on
- [Kanroot](https://github.com/kanroot/Dotsfiles/tree/master)
- [NOOBDY](https://github.com/NOOBDY/dotfiles)
-  [Alexays Waybar Wiki ](https://github.com/Alexays/Waybar/wiki)
## Wallpaper
- [Man Made Pier HD Wallpaper](https://wall.alphacoders.com/big.php?i=875211)
## Tips and Tricks
  - Waybar keyboard-state module not working. Solution:
  	- ``` sudo usermod -aG input [username] ```
	- Don't forget log out and log in back
  - After copy fonts to `/usr/share/fonts` directories run:
	- ``` sudo fc-cache -f -v ```
