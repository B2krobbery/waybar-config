# Waybar Config

Waybar configuration for Arch Linux with Hyprland.

## Screenshot

![Waybar Screenshot](waybar.png)

## Features

* Minimal top bar
* Workspace indicator
* Clock in the center
* System modules (volume, network, bluetooth, battery)

## Files

* `config` → Waybar module layout
* `style.css` → Waybar styling

## Author

Visal Vijay (GitHub: B2krobbery)

Modified and customized Waybar configuration.

Based on a Waybar configuration found online and customized for my setup.
## Setup

Clone the repository:

```
git clone https://github.com/B2krobbery/waybar-config.git
```

Copy the files to your Waybar config directory:

```
cp waybar-config/config ~/.config/waybar/
cp waybar-config/style.css ~/.config/waybar/
```

Restart Waybar:

```
pkill waybar && waybar &
```
