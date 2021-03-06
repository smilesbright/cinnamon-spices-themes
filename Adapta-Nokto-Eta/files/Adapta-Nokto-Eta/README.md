## Adapta-Nokto-Eta

A light theme based on Material Design Guidelines. Cinnamon, Metacity, GTK2, GTK3.18 and GTK3.20+ themes are included.

## Credits

This is a build of [Tista's](https://github.com/tista500) [Adapta theme](https://github.com/adapta-project/adapta-gtk-theme) made for Cinnamon Spices.

## Version / Modifications

[Original Source Code](https://github.com/adapta-project/adapta-gtk-theme)

[Fork for this build](https://github.com/smurphos/adapta-gtk-theme)

This build is based on [Adapta version 3.93.0](https://github.com/adapta-project/adapta-gtk-theme/releases/tag/3.93.0.262) with the following modifications.

* Intention to retain support for GTK 3.18 after 26/4/18
* Stylesheets distributed in deobfuscated .css format
* Build includes Cinnamon, GTK 2.0, 3.18, 3.20, 3.22 & Metacity-1 themes only
* GTK3.18, 3.20. 3.22 - Added support for different colored backgrounds in Nemo dual pane view

## License

This theme is distributed under the terms of the [GPLv2.0 license](https://github.com/smurphos/adapta-gtk-theme/blob/master/COPYING)

Assets in svg format are distributed under the terms of the [CC BY-SA 4.0 license](https://github.com/smurphos/adapta-gtk-theme/blob/master/LICENSE_CC_BY_SA4)

Cinnamon thumbnail includes a depiction of icons from Sam Hewitt's [Paper Icons](https://snwh.org/paper) licensed under CC-SA-4.0

Wallpaper in screenshots is from [Adapta Backgrounds](https://github.com/adapta-project/adapta-backgrounds) licensed under [CC BY-SA 4.0 license](https://github.com/adapta-project/adapta-backgrounds/blob/master/LICENSE_CC_BY_SA4)

## Installation

There are 4 variants of this theme available.

* Adapta - light version of theme - recommended for users on GTK 3.20+ systems with 1080p screen resolution or greater
* Adapta-Nokto - dark version of theme - recommended for users on GTK 3.20+ systems with 1080p screen resolution or greater
* Adapta-Eta - light compact version of theme - recommended for users on GTK 3.18 systems or GTK3.20+ systems with screen resolution < 1080p
* Adapta-Nokto-Eta - dark compact version of theme - recommended for users on GTK 3.18 systems or GTK3.20+ systems with screen resolution < 1080p

Install via Cinnamon's Themes module in Cinnamon settings or download from [Cinnamon Spices](https://cinnamon-spices.linuxmint.com/themes) and unzip into your `~/.themes` directory.

Select the theme as your Desktop, Controls and Window Borders in the Cinnamon Themes module.

To allow the GTK2, GTK3 and Metacity1 themes to apply to GUI apps running as root run this command in your terminal after installation to create symlinks to user themes in the system theme directory.

`sudo ln -s ~/.themes/* /usr/share/themes/`

## Compatibility

This theme is compatible with Cinnamon versions `3.2.x`, `3.4.x`, `3.6.x` & `3.8.x`

The GTK3 themes require GTK `3.18.x`, `3.20.x` or `3.22.x`

Tested on Linux Mint `18.2` & `18.3` 64bit with Cinnamon `3.4.x`, `3.6.x`, Manjaro `17.0.6` 64Bit with Cinnamon `3.6.x` and Ubuntu `17.10` with Cinnamon nightly builds.

### Firefox fix

If you have problems seeing text on input fields in Firefox with any particular theme this problem can be solved by adding a userContent.css file to your Firefox default profile including the line `input, textarea { color: #222; background: #eee; }`

The theme includes a helper script that creates the userContent.css file with this content in the correct location. To access the tool open a terminal window and use the following command to make the script executable and launch it.

`chmod +x ~/.themes/Adapta-Nokto-Eta/firefox_fix.sh && ~/.themes/Adapta-Nokto-Eta/cinnamon/firefox_fix.sh`


