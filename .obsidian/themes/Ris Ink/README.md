# Ris Ink — an Obsidian theme

Warm paper surfaces, saturated ink accents, and a field-notebook feel. A port of the
[vs-ris](https://github.com/risadams/vs-ris) VS Code themes to Obsidian:

- **Light — Ink Paper**: warm `#faf6ef` paper with rose/teal/plum/sepia ink accents
- **Dark — Ink Parchment**: inverted paper (`#1a1614`) with softened ink variants

Tagline: **Ship code. Stay human.**

## What you get

- Full light + dark palettes mapped to Obsidian's CSS variables (surfaces, text,
  links, tags, callouts, graph view, file explorer, scrollbars)
- The signature move from the brand: **parchment-dark code blocks even in light
  mode**, using the vs-ris token palette (rose keywords, teal strings, plum
  functions, ochre numbers)
- Inline code stays plum-on-warm-paper, distinct from blocks
- Headings led by rose with a plum/sepia chorus; Fraunces `SOFT`/`WONK` optical
  character on H1/H2 when the variable font is installed
- Callouts styled as margin notes: dashed accent bar, handwritten (Caveat) title
- Dashed hairline `<hr>`s, dashed table row separators, painterly link underlines
- A subtle paper-grain noise overlay (see below)
- WCAG AA-tuned text colors inherited from the brand guide

## Install

1. Copy this folder into your vault at `.obsidian/themes/Ris Ink/`
   (the folder must contain `manifest.json` and `theme.css`).
2. In Obsidian: **Settings → Appearance → Themes**, select **Ris Ink**.
3. Light/dark follows your base color scheme toggle in the same settings pane.

## Fonts (optional but recommended)

The theme falls back to Georgia/Consolas/Segoe Script if these aren't installed,
but for the full effect install locally:

- [Fraunces](https://fonts.google.com/specimen/Fraunces) (variable) — body, headings, UI
- [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) — code, tags, metadata
- [Caveat](https://fonts.google.com/specimen/Caveat) — callout titles

No remote font loading: the theme makes zero network requests and works offline.

## Disabling the paper grain

The full-viewport noise overlay is what makes the background feel like paper. If
you'd rather have flat color (or notice any rendering softness), delete or comment
out section **9. Paper grain** at the bottom of `theme.css`.

## Palette reference

| Role | Light (Ink Paper) | Dark (Ink Parchment) |
|---|---|---|
| Background | `#faf6ef` | `#1a1614` |
| Text | `#1a1614` | `#f0e6d2` |
| Accent (rose) | `#CB0162` | `#e24a8a` |
| Secondary (teal) | `#1a5b6e` | `#5ba3b8` |
| Tertiary (plum) | `#6b3a6e` | `#b183b5` |
| Quaternary (sepia) | `#8a5a3c` | `#b8875f` |
| Code block bg | `#2a2220` | `#1a1210` |

## License

MIT, same as [vs-ris](https://github.com/risadams/vs-ris).
