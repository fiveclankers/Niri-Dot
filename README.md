# niri-dot

My personal Niri dotfiles. Primarily built for my own use — shared publicly in case any of it is useful to someone else.

---

## Overview

[Niri](https://github.com/YaLTeR/niri) is a scrollable-tiling Wayland compositor. This repo holds the configs I use day-to-day, including terminals, shell, fetch, and a Spotify theme.

<!-- Add a screenshot of your desktop here once you have one
![desktop](Pictures/Wallpapers/desktop.png)
-->

---

## Structure

```
.config/
  alacritty/     — Alacritty terminal config
  fastfetch/     — Fastfetch system info config
  fish/          — Fish shell config and functions
  ghostty/       — Ghostty terminal config
  kitty/         — Kitty terminal config
  niri/          — Core Niri compositor config (keybinds, window rules, layout)
  noctalia/      — Noctalia colorscheme
.spicetify/      — Spicetify Spotify theme overrides
Pictures/
  Wallpapers/    — Wallpaper collection
```

---

## Stack

| Role            | Program                                                        |
|-----------------|----------------------------------------------------------------|
| Compositor      | [Niri](https://github.com/YaLTeR/niri) (Wayland, scrollable-tiling) |
| Terminal        | Ghostty / Kitty / Alacritty                                    |
| Shell           | Fish                                                           |
| System info     | Fastfetch                                                      |
| Music client    | Spotify + Spicetify                                            |
| Colorscheme     | Noctalia                                                       |

---

## Installation

This is not a plug-and-play rice. Things may break or conflict with your existing setup.

```bash
git clone https://github.com/fiveclankers/Niri-Dot.git

# Back up your existing configs first
cp -r ~/.config ~/.config.bak

# Copy what you need
cp -r Niri-Dot/.config/* ~/.config/
cp -r Niri-Dot/.spicetify/ ~/.spicetify/
```

Review each config before applying. Don't blindly overwrite things.

---

## Notes

- Niri config lives at `.config/niri/config.kdl` — keybinds and layout rules are all in there.
- Fish config is at `.config/fish/config.fish`.
- For Spicetify, run `spicetify apply` after copying the theme files.
- Wallpapers go in `Pictures/Wallpapers/` — point your wallpaper daemon there.

---

## Gallery

<!-- Drop screenshots here as you take them
![overview](Pictures/Wallpapers/overview.png)
-->

*No screenshots yet.*

---

Feel free to take whatever you find useful.
