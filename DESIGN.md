# Yellowstone design notes

## The idea

Yellowstone should feel geothermal rather than generically rustic. Volcanic black forms the base. Ember orange and sulfur gold carry active and semantic roles, while warm parchment keeps text readable.

The theme uses the current Aether palette generated for the illustrated wallpaper without substitutions.

## Palette

| Role | Color | Source |
| --- | --- | --- |
| Volcanic black | `#0f0900` | Main background |
| Deep caldera | `#080500` | Scrims and darkest surfaces |
| Ember orange | `#c7692d` | Functions, links, and active borders |
| Sunset orange | `#cc6b35` | Secondary accent |
| Sulfur gold | `#bda01a` | Warnings and border endpoint |
| Meadow ochre | `#b49200` | Success and strings |
| Sunset red | `#c2612f` | Errors and destructive states |
| Warm parchment | `#eae5cf` | Main text |

## Rules

1. Keep large surfaces near-black and brown. Orange and gold should identify activity.
2. Use the ember-orange-to-sulfur gradient for active borders and major shell surfaces only.
3. Keep the ANSI blue, cyan, and magenta roles warm as defined by Aether.
4. Preserve separation between ember orange, sulfur gold, and sunset red.
5. Use the vertical selected-row marker sparingly.
6. Do not use the National Park Service arrowhead or imply NPS endorsement.
7. Keep the illustrated wallpaper sorted first as the default; keep the embroidered patch as the alternate.

## Release checklist

- Test horizontal and vertical shell bars.
- Check launcher, menu, notifications, OSD, Polkit, lock screen, and image picker.
- Check all ANSI colors in a terminal test chart.
- Check Rust, PHP, TypeScript, Markdown, JSON, and diff syntax.
- Check btop meters and selected process rows.
- Check Chromium, VS Code, Neovim/Aether, Helix, Pi, and Obsidian.
- Keep `preview.png` at 1800x1012 and free of local account, process, and hardware data.
- Keep the wallpaper and preview attribution in `ASSETS.md` current.
- Reinstall from a clean Git URL to test Omarchy's restricted-theme path.
