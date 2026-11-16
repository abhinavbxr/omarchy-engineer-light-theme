# Engineer Light for Omarchy

**Engineer Light** is a Kanagawa Lotus-inspired light engineering theme for [Omarchy](https://omarchy.org/): warm drafting-paper surfaces, ink/blue accents, and technical drawing aesthetics built around real engineering blueprints and converted real-life construction imagery.

![Engineer Light fastfetch + btop preview](preview-fastfetch-btop.png)

## Install

```bash
omarchy theme install https://github.com/abhinavbxr/omarchy-engineer-light-theme
```

## Try locally

```bash
cp -r /path/to/engineer-light ~/.config/omarchy/themes/
omarchy theme set engineer-light
```

## Palette

Kanagawa Lotus-inspired light palette defined in `colors.toml`:

| Role | Color |
| --- | --- |
| Background | `#f2ecbc` |
| Foreground | `#545464` |
| Accent | `#4d699b` |
| Selection | `#c7d7e0` |
| Muted | `#8a8980` |

Omarchy generates application themes from `colors.toml`.

## Backgrounds

Engineering blueprint and converted real-life imagery (all 2560×1440), sourced from the internet and processed for this theme:

- `backgrounds/01-fort-myer-blueprint.png` — converted architectural blueprint (Fort Myer NCO quarters plan)
- `backgrounds/02-glacier-station-blueprint-a.png` — converted engineering blueprint (Glacier Ranger Station plan)
- `backgrounds/03-glacier-station-blueprint-b.png` — converted engineering blueprint (Glacier Ranger Station elevations)
- `backgrounds/04-pampanga-bridge-construction.png` — converted real-life bridge construction photograph
- `backgrounds/05-pampanga-bridge-construction-ii.png` — converted real-life bridge construction photograph

Cycle backgrounds with `omarchy theme bg next`.

## Previews

- `preview-fastfetch-btop.png` — 1920×1200 preview composition showing fastfetch and btop
- `preview.png` — 1600×1000 base preview image
- `preview.webp` — 1200×675 web preview asset

## Files

- `colors.toml` — core theme palette
- `icons.theme` — icon theme name (`Yaru-blue`)
- `backgrounds/` — theme wallpapers (5 images)
- `ATTRIBUTION.md` — source image credits and licenses
- `preview-fastfetch-btop.png`, `preview.png`, `preview.webp` — preview assets
- `README.md`, `LICENSE`

## Image sources & attribution

Backgrounds are converted/processed from Wikimedia Commons sources (public domain NPS/HABS architectural drawings and CC BY-SA 4.0 construction photographs). See [`ATTRIBUTION.md`](ATTRIBUTION.md) for full source links, authors, and license details.

## Community theme compatibility

Prepared for [omarchy-site community theme submission guidelines](https://github.com/omacom/omarchy-site#adding-your-theme) (not submitted). Before submitting, replace the preview with a real 16:9 desktop screenshot of the theme in use (terminal + editor visible, using this theme’s wallpaper).

## License

MIT (theme files). See `ATTRIBUTION.md` for third-party image source licenses/credits.
