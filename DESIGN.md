# Yellowstone design notes

## The idea

Yellowstone should feel geothermal rather than generically rustic. Volcanic brown forms the base. Pastel blue represents hot-spring water and open sky. Sulfur gold, pale steam, and sunset stone provide warm semantic roles.

The theme starts with the Aether palette generated for the current wallpaper. The original lavender `blue` and `bright_blue` slots were replaced with pastel blue so editor functions, links, and cool interface accents no longer read as purple.

## Palette

| Role | Color | Source |
| --- | --- | --- |
| Volcanic earth | `#1c150b` | Main background |
| Deep caldera | `#0e0b06` | Scrims and darkest surfaces |
| Geothermal blue | `#a9c8df` | Functions, links, and active borders |
| Spring blue | `#94bbce` | Secondary cool accent |
| Sulfur | `#d7c78f` | Warnings and border endpoint |
| Meadow gold | `#d1bc86` | Success and strings |
| Sunset stone | `#cba183` | Errors and destructive states |
| Pale steam | `#d4cfb1` | Main text |

## Rules

1. Keep large surfaces dark brown. Blue and sulfur should identify activity.
2. Use the geothermal-blue-to-sulfur gradient for active borders and major shell surfaces only.
3. Do not reintroduce lavender or violet into the blue syntax slots.
4. Preserve separation between pastel blue, gold, and sunset stone.
5. Use the vertical selected-row marker sparingly.
6. Do not use the National Park Service arrowhead or imply NPS endorsement.
7. Keep the embroidered patch wallpaper sorted first as the default; keep the illustrated landscape as the alternate.

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
