# GTA HATO Handbook Assets

Image assets and HTML snippets for the **Highways Agency (HATO)** faction handbook, part of the [Grand Theft Arma](https://grandtheftarma.com) community.

## Repository Structure

```
images/
├── equipment/      # Binoculars, compass, GPS, NVGs, radio, rangefinder, toolkit, etc.
├── goggles/        # Aviator glasses, respirators, safety goggles, shades, etc.
├── headgear/       # Hard hats in various colours with optional ear-protection/headset
├── items/          # Inventory item icons (bottle, first-aid, jerrycan, multitool)
├── objects/        # Placeable objects - barriers, cones, signs, tents, lights, etc.
├── signs/          # Road signage (checkpoint, diversion, speed, road closed, etc.)
├── uniforms/       # HATO uniforms and coveralls (standard & construction variants)
├── vehicles/       # HATO vehicles - quad, truck, van, offroad, SUV, fuel truck, etc.
├── vests/          # Safety vests and deck-crew vests in multiple colours
├── placeholder-*   # Generic placeholder images (large & thumbnail, square & wide)
snippets/
├── objects-table.html   # Styled HTML table listing all placeable objects
├── vehicles-table.html  # Styled HTML table listing all HATO vehicles
```

## Images

Each image is provided in two variants:

| Suffix | Purpose |
|--------|---------|
| `-large.jpg` | Full-size image (linked on click) |
| `-thumb.jpg` | Thumbnail for inline display |

Images are served via GitHub raw URLs:

```
https://raw.githubusercontent.com/ReallyMartin/GTA-HATO-Handbook-Assets/refs/heads/main/images/<category>/<name>-large.jpg
https://raw.githubusercontent.com/ReallyMartin/GTA-HATO-Handbook-Assets/refs/heads/main/images/<category>/<name>-thumb.jpg
```

## HTML Snippets

Self-contained HTML tables with scoped CSS (Open Sans font, responsive with horizontal scroll on mobile):

- **`objects-table.html`** - Lists placeable objects with preview, name, required rank, and weight.
- **`vehicles-table.html`** - Lists HATO vehicles with preview, name, required rank, top speed, horsepower, seats, item load, virtual load, fuel capacity, and skin name.

Each thumbnail links to the corresponding full-size image in a new tab.

## Usage

Copy a snippet directly into any HTML-based handbook or wiki page. Styles are scoped to `.object-table` / `.vehicle-table` class names so they won't conflict with surrounding content.

## Disclaimer

This repository contains assets and depictions of assets that are the property of the **Grand Theft Arma** community / **Vector Dynamics LTD** and **Bohemia Interactive**. All rights belong to their respective owners. These assets are provided here solely for use within the Grand Theft Arma community and are not intended for redistribution or commercial use outside of that context.