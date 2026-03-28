# Purple-Dusk for Omarchy

Purple-Dusk is an Omarchy theme package built to coordinate the wider desktop theme with the Neovim theme **`purple-dusk`**.

This repo is the Omarchy-side theme bundle. It provides the files Omarchy uses for desktop and application styling, while Neovim itself is styled by the separate Neovim colorscheme named `purple-dusk`.

## Relationship to the Neovim theme

This Omarchy theme is designed to pair with the Neovim theme:

- **Neovim theme name:** `purple-dusk`
- **Omarchy theme repo:** `omarchy-purple-dusk-theme`

The visual intent is simple:

- Omarchy styles the desktop and supported applications
- Neovim loads `purple-dusk`
- both follow the same theme direction

## What this repo contains

Typical files include:

- `colors.toml`
- `colors.css`
- `btop.theme`
- `cava_theme`
- `chromium.theme`
- `mako.ini`
- `walker.css`
- `warp.yaml`
- `palette.json`

## How it works with Omarchy

This repo gives Omarchy the theme data it needs. The matching Neovim theme `purple-dusk` should be used separately for editor styling.

## Naming convention

- **Omarchy repo:** `omarchy-purple-dusk-theme`
- **Neovim theme:** `purple-dusk`

## Goal

Purple-Dusk is intended to make the desktop, terminal utilities, and Neovim feel like parts of one single theme.
