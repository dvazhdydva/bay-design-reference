# warehousebay and repairbay — separate design references

This repository contains DESIGN REFERENCES ONLY. There is no application implementation, deployment configuration, live database or API credential here.

## Choose the requested project

- **warehousebay**: read `warehousebay/DESIGN.md`, then `warehousebay/SCREENS.md`. The Figma palette, Inter UI font and IBM Plex Mono identifier font are the approved visual base. Stitch is currently used to improve layout, not to replace the visual theme.
- **repairbay**: read `repairbay/DESIGN.md`, then `repairbay/SCREENS.md`. Use this project's own native component variants, named tokens and Inter text styles.

Do not mix the two applications' workflows, component contracts or sample data. Use only the screens relevant to the requested design task.

## Reading the files

Each project has readable screen Markdown in `screens/`, CSS design tokens, SVG visual references and per-screen JSON layer snapshots. If SVG/JSON cannot be processed, use DESIGN.md, the CSS and the matching screen Markdown for layout structure, dimensions, spacing and text.

Static mockups are visual references. Current verified application behaviour and explicit user instructions take precedence over older design annotations.
