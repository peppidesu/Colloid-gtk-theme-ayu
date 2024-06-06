# Colloid gtk theme

![Colloid](colloid.png?raw=true)

- Icon theme used in the screeenshot: `tela-cricle-blue` (obfuscated for neutrality/privacy)
- Font used in the screenshot: `maple-mono`

Install with the default dark variant (no nord/darcula) to get the intended result. accent color used here is yellow.


### _Below is the original README.md. Some info might not be relevant for this fork._

----

## Requirements

- GTK `>=3.20`
- `gnome-themes-extra` (or `gnome-themes-standard`)
- Murrine engine — The package name depends on the distro.
  - `gtk-engine-murrine` on Arch Linux
  - `gtk-murrine-engine` on Fedora
  - `gtk2-engine-murrine` on openSUSE
  - `gtk2-engines-murrine` on Debian, Ubuntu, etc.
- `sassc` — build dependency

- `Icon theme` [Colloid](https://github.com/vinceliuice/Colloid-icon-theme)

## Donate

If you like my project, you can buy me a coffee:

<span class="paypal"><a href="https://www.paypal.me/vinceliuice" title="Donate to this project using Paypal"><img src="https://www.paypalobjects.com/webstatic/mktg/Logo/pp-logo-100px.png" alt="PayPal donate button" /></a></span>

## Installation

### Manual Installation

Run the following commands in the terminal:

```sh
./install.sh
```

> Tip: `./install.sh` allows the following options:

```
-d, --dest DIR          Specify destination directory (Default: ~/.themes)
-n, --name NAME         Specify theme name (Default: Colloid)
-t, --theme VARIANT...  Specify theme color variant(s) [default|purple|pink|red|orange|yellow|green|teal|grey|all] (Default: blue)
-c, --color VARIANT...  Specify color variant(s) [standard|light|dark] (Default: All variants)
-s, --size VARIANT...   Specify size variant [standard|compact] (Default: standard variant)

-l, --libadwaita        Install specify gtk-4.0 theme into config folder (~/.config/gtk-4.0) for all gtk4 apps use this theme
                        Default ColorSchemes theme will follow the system style (light/dark mode switch), nord|dracula|gruvbox|everforest|black ColorSchemes not support this
                        Options for default ColorSchemes:
                        1. system                      Default option (using system colors for light/dark mode switching)
                        2. fixed                       Using fixed theme colors (that will break light/dark mode switch)

--tweaks                Specify versions for tweaks
                        1. [nord|dracula|gruvbox|all]  (Nord/Dracula/gruvbox/all) ColorSchemes version
                        2. black                       Blackness color version
                        3. rimless                     Remove the 1px border about windows and menus
                        4. normal                      Normal windows button style like gnome default theme (titlebuttons: max/min/close)
                        5. float                       Floating gnome-shell panel style

-r, --remove,
-u, --uninstall         Uninstall/Remove installed themes or links

-h, --help              Show help
```

> For more information, run: `./install.sh --help`

### Fix for Libadwaita

```sh
./install.sh -l
```

Default ColorSchemes themes will follow the system style now ! (switch [light/dark] mode)

https://github.com/vinceliuice/Colloid-gtk-theme/assets/7604295/d5c24086-08bc-45a4-b4d9-124c02249216

![tweaks](tweaks.png?raw=true)

### Flatpak Installation

Automatically install your host GTK+ theme as a Flatpak. Use this:

- [pakitheme](https://github.com/refi64/pakitheme)

## Firefox theme
[Install Firefox theme](src/other/firefox)

![01](src/other/firefox/screenshot.png?raw=true)
