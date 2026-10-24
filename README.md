# netbeans-themes

**Themes for Apache NetBeans 31** — each theme recolors the editor syntax highlighting **and** the whole IDE UI, packaged as a single ZIP you can import with one click.

| Theme | Variant | Look & Feel | Download | Image |
| --- | --- | --- | --- | --- |
| Catppuccin Mocha | dark | FlatLaf Dark | [catppuccin-mocha-full.zip](./themes/catppuccin-mocha-full.zip) | ![catpuccin mocha image](https://github.com/joko675/netbeans-themes/blob/main/images/catpuccin-mocha.png)
| Catppuccin Macchiato | dark | FlatLaf Dark | [catppuccin-macchiato-full.zip](./themes/catppuccin-macchiato-full.zip) | ![catpuccin macchiato image](https://github.com/joko675/netbeans-themes/blob/main/images/catpuccin-macchiato.png)
| Catppuccin Frappé | dark | FlatLaf Dark | [catppuccin-frappe-full.zip](./themes/catppuccin-frappe-full.zip) | ![catpuccin frappe image](https://github.com/joko675/netbeans-themes/blob/main/images/catpuccin-frappe.png)
| Catppuccin Latte | light | FlatLaf Light | [catppuccin-latte-full.zip](./themes/catppuccin-latte-full.zip) | ![catpuccin latte image](https://github.com/joko675/netbeans-themes/blob/main/images/catpuccin-latte.png)
| Dracula | dark | FlatLaf Dark | [dracula-full.zip](./themes/dracula-full.zip) | ![dracula image](https://github.com/joko675/netbeans-themes/blob/main/images/dracula.png)
| Nord | dark | FlatLaf Dark | [nord-full.zip](./themes/nord-full.zip) | ![nord image](https://github.com/joko675/netbeans-themes/blob/main/images/nord.png)
| Rosé Pine | dark | FlatLaf Dark | [nord-full.zip](./themes/rose-pine-full.zip) | ![rose pine image](https://github.com/joko675/netbeans-themes/blob/main/images/rose-pine.png)
| Rosé Pine Moon | dark | FlatLaf Dark | [nord-full.zip](./themes/rose-pine-moon-full.zip) | ![rose pine moon image](https://github.com/joko675/netbeans-themes/blob/main/images/rose-pine-moon.png)
| Rosé Pine Dawn | light | FlatLaf Light | [nord-full.zip](./themes/rose-pine-dawn-full.zip) | ![rose pine dawn image](https://github.com/joko675/netbeans-themes/blob/main/images/rose-pine-dawn.png)


> More themes on the way

## What these themes include

- **Full IDE theme** — not just editor tokens: tabs, the Projects/Files tree, buttons, scrollbars and the rest of the UI (via FlatLaf).
- **Editor color profile** for all languages, plus extra token overrides for specific languages (Java, …).
- **One-click import** — every ZIP is in the standard NetBeans settings-export format (**Tools → Options → Import**).

## Installation

Applies to every theme ZIP in this repo.


### Option A — import in the IDE (recommended)

1. Download the theme ZIP from the table above.
2. Open **Tools → Options** (macOS: **NetBeans → Preferences…**).
3. Click **Import…**, pick the ZIP, tick **All** (the archive only contains
   `config/Editors/` and `config/LookAndFeel/`), confirm and let the IDE restart.
4. In **Options → Appearance → Look and Feel** select **FlatLaf Dark**
   (or **FlatLaf Light** for Catppuccin Latte) and restart.
5. In **Options → Fonts & Colors → Profile** select the theme's profile
   (e.g. `Catppuccin_Mocha`).

> Import overwrites matching settings in your userdir, including any custom
> `config/LookAndFeel/FlatLaf.properties` and the editor font settings of the
> imported profile. Back up first via **Tools → Options → Export**.
> Only one UI theme can be active at a time — installing another theme> replaces the previous one.

### Option B — editor only, keep your current UI

Want just the syntax colors? Copy only `config/Editors/` into your userdir and skip `config/LookAndFeel/`.

## License & Disclaimer

This is a hobby project, not affiliated with the Apache Software Foundation
(Apache NetBeans) or with any of the palette projects. The themes are ports of
third-party color palettes — all rights to the palettes belong to their
original authors; see [`THIRD_PARTY_NOTICES.md`](./THIRD_PARTY_NOTICES.md) for
copyright notices and licenses.

All themes were crearted by AI so they can be not 100% accurate, i only tested them briefly and they seem ok to me.
