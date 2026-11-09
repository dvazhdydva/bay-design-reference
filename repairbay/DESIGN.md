# RepairBay — design-system reference

Source: https://www.figma.com/design/2GCDc8UQqTr8e2U4GK2HLR/RepairBay-Design-System

## Visual authority

Start with the Foundations & audit specification SVG, then inspect the Core components review instances. Preserve the source font families, colours, control sizes, spacing and status treatments. Do not replace these with an AI tool's default visual theme.

Use the existing component variants and conditional states as references. Business-rule annotations in the mockups are design references; the current application's verified behaviour and explicit user instructions take precedence.

## Structured references

- named-tokens.css contains native named variables and text-style classes. Numeric FLOAT values are preserved as raw numbers; apply the appropriate CSS units when binding them to layout.
- styles-and-variables.json preserves the 3 variable collections, 73 variables and 8 local text styles, including mode values and aliases.
- design-tokens.css lists observed colours, fonts, sizes, radii and spacing extracted from rendered layers.
- manifest.json maps every exported screen, component and component set to its page, source ID, dimensions, SVG and JSON.
- repairbay-design-system.json combines all pages and available layer properties.

## Using this in Stitch

Upload this DESIGN.md, the Foundations specification and the relevant component-review SVG first. Add only the screens required for the current task. The full JSON is an optional structured reference, not an importable native Figma file.

SVGs retain text to support AI reading. Font binaries are not bundled. No original Figma nodes were changed.
