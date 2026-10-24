# 🐈 netbeans-themes

**Themes for Apache NetBeans 31** — each theme recolors the editor syntax highlighting **and** the whole IDE UI, packaged as a single ZIP you can import with one click.

| [`Catppuccin-Mocha-Full.zip`](./themes/Catppuccin-Mocha-Full.zip) |

> More themes on the way

## ✨ What these themes include

- 🎨 **Full IDE theme** — not just editor tokens: tabs, the Projects/Files tree, buttons, scrollbars and the rest of the UI (via FlatLaf).
- 🧩 **Editor color profile** for all languages, plus extra token overrides for specific languages (Java, …).
- 📥 **One-click import** — every ZIP is in the standard NetBeans settings-export format (**Tools → Options → Import**).
- 🪶 **Zero dependencies** — plain userdir configuration, no plugins (`.nbm`) to install.

## 🚀 Installation

Applies to every theme ZIP in this repo.

### Option A — import in the IDE (recommended)

1. Download the theme ZIP (from the table above).
2. Open **Tools → Options** (macOS: **NetBeans → Preferences…**).
3. Click **Import…**, point it at the downloaded ZIP, tick the settings categories (at least *Fonts & Colors* and *Advanced*) and confirm.
4. Restart the IDE.
5. In **Options → Appearance → Look and Feel** select **FlatLaf Dark** (for dark themes), and in **Options → Fonts & Colors → Profile** select the theme's profile (e.g. `Catppuccin_Mocha`).

> ⚠️ Import overwrites the matching settings in your userdir. If you have your own profiles/colors, back them up first via **Tools → Options → Export**.


### Option B — editor only, keep your current UI

Want just the syntax colors? Copy only `config/Editors/` into your userdir and skip `config/LookAndFeel/`.

## License & Disclaimer

This is a hobby project, not affiliated with the Apache Software Foundation
(Apache NetBeans) or with any of the palette projects. The themes are ports of
third-party color palettes — all rights to the palettes belong to their
original authors; see [`THIRD_PARTY_NOTICES.md`](./THIRD_PARTY_NOTICES.md) for
copyright notices and licenses.
