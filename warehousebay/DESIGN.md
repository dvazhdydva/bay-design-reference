# WarehouseBay — approved visual design

This package contains all 94 top-level screens and dialogs from the separate WarehouseBay v2.0 Figma concept. The concept name is not the application release version.

## Grounding and precedence

- Use the Foundations / Shared shell & control patterns SVG as the visual authority for colours, typography, spacing, borders, controls and the application shell.
- Use the matching desktop and phone SVGs together when designing a screen. Individual screen names and dimensions are listed in manifest.json.
- Preserve existing application business rules. A static mockup does not establish permissions, live counts or successful workflows.
- Keep WarehouseBay's approved font family and palette. Do not replace these with another AI tool's default design system.
- Explicit user instructions override older mockups. Stitch is currently used to improve layout, while the Figma visual language remains the base.

## Approved visual foundation

- UI font: Inter. Monospaced identifiers/code: IBM Plex Mono.
- Page background: #f3f5f8. Surfaces: #ffffff.
- Primary text: #172738. Secondary text: #607184.
- Primary action blue: #185db4.
- Control borders: #d6dee7. Subtle dividers: #e4e9ef.
- Success text: #267451. Success surface: #ebf6ef.
- These values are extracted from the exported layers. Refer to the Foundations SVG for their intended use and to design-tokens.css for all observed values.

## Files

- design-tokens.css: values extracted from actual Figma layers, with frequency counts for colours. This is a reference, not a finished application stylesheet.
- svg/: complete visual export of every top-level screen. Text remains text to support AI reading and editing. Referenced fonts are not bundled.
- json/: one layer/property snapshot per screen.
- warehousebay-v2.json: combined page and layer tree, including text, geometry, paints, typography, layout and vector paths where exposed by the connector.
- index.html: local visual catalogue of the SVG screens.

## How to use in Stitch

Start with this DESIGN.md, the Foundations SVG, and only the relevant desktop/phone screen SVGs. Uploading all screens at once is unnecessary and can reduce clarity. The combined JSON is useful as a structured reference if accepted; it is not an importable .fig file.
