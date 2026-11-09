# repairbay: Active jobs / review notes

Page: 03 · Active jobs

Source node: 24:1283 · FRAME · 1280 × 928 px

[SVG reference](../svg/24-1283--active-jobs-review-notes.svg) · [Layer properties](../json/24-1283--active-jobs-review-notes.json)

## Layout structure

- Active jobs / review notes [FRAME; 1280 x 928] — layoutMode=VERTICAL, itemSpacing=20, paddingTop=32, paddingRight=32, paddingBottom=32, paddingLeft=32
  - Active jobs / design review [TEXT; 276 x 28] — fontSize=21, textAlignHorizontal=LEFT
  - Source: local RB at1280×631 CSS px, devicePixelRatio1.5. Screen exampl [TEXT; 1216 x 20] — fontSize=13, textAlignHorizontal=LEFT
  - Keep [TEXT; 1216 x 22] — fontSize=15, textAlignHorizontal=LEFT
  - Home warehouse selection with session persistence; serial lookup, Scan [TEXT; 1216 x 40] — fontSize=13, textAlignHorizontal=LEFT
  - Compact the WB queue [TEXT; 1216 x 22] — fontSize=15, textAlignHorizontal=LEFT
  - The observed incoming queue uses180px before search. Use a44–52px coll [TEXT; 1216 x 40] — fontSize=13, textAlignHorizontal=LEFT
  - Use the space for actual data [TEXT; 1216 x 22] — fontSize=15, textAlignHorizontal=LEFT
  - The observed checkbox column is about101px. Proposed widths total1216p [TEXT; 1216 x 40] — fontSize=13, textAlignHorizontal=LEFT
  - Status icons only [TEXT; 1216 x 22] — fontSize=15, textAlignHorizontal=LEFT
  - One main status plus optional warning/return marker. Tooltip and acces [TEXT; 1216 x 40] — fontSize=13, textAlignHorizontal=LEFT
  - Selection is not navigation [TEXT; 1216 x 22] — fontSize=15, textAlignHorizontal=LEFT
  - Clicking a checkbox does not open the repair. Selected count is visibl [TEXT; 1216 x 20] — fontSize=13, textAlignHorizontal=LEFT
  - Fix the filter density [TEXT; 1216 x 22] — fontSize=15, textAlignHorizontal=LEFT
  - Current Type choices are stretched far apart beside the long Status li [TEXT; 1216 x 40] — fontSize=13, textAlignHorizontal=LEFT
  - No premature feature additions [TEXT; 1216 x 22] — fontSize=15, textAlignHorizontal=LEFT
  - Natural-language/voice search is future work and is not shown as worki [TEXT; 1216 x 40] — fontSize=13, textAlignHorizontal=LEFT
  - Example and acceptance limits [TEXT; 1216 x 22] — fontSize=15, textAlignHorizontal=LEFT
  - Real filter options are retained for compatibility. Engineer labels he [TEXT; 1216 x 40] — fontSize=13, textAlignHorizontal=LEFT

## Text layers in source order

Active jobs / design review

Source: local RB at1280×631 CSS px, devicePixelRatio1.5. Screen examples use DEMO serials and illustrative workflow icons, not assertions about live repair status.

Keep

Home warehouse selection with session persistence; serial lookup, Scan, Find unit and Register unit; Filter; direct selected-label printing; serial/model/site/Fz/Simpro/Var job; row navigation and outcome colours.

Compact the WB queue

The observed incoming queue uses180px before search. Use a44–52px collapsible summary with count, retain all incoming cards on expansion and their existing Review action. This is a layout proposal, not automatic RMA acceptance.

Use the space for actual data

The observed checkbox column is about101px. Proposed widths total1216px:40/208/104/240/328/104/104/88. Values remain13px; labels12px. Site and Fz wrap to two lines, full values remain available.

Status icons only

One main status plus optional warning/return marker. Tooltip and accessible name are mandatory. Assessment uses stethoscope; QC blue thumbs-up; Repaired green check; WEEE red ordinary bin. Never require manual icon selection.

Selection is not navigation

Clicking a checkbox does not open the repair. Selected count is visible. Print is disabled at0 and active after selection; no unnecessary bulk-action modal. Preview does not send a print job.

Fix the filter density

Current Type choices are stretched far apart beside the long Status list. Align short lists at the top; keep Status/Type/Engineer groups and all current status options. Use TBC instead of technical UNASSESSED. Sticky header/footer and scrollable body in the real dialog; Escape/Cancel do not apply filters.

No premature feature additions

Natural-language/voice search is future work and is not shown as working. No new pagination, sorting defaults or company access changes are introduced. Oldest registered remains the default; completed jobs stay7days.

Example and acceptance limits

Real filter options are retained for compatibility. Engineer labels here illustrate the current visible names; implementation must reuse server-authorised choices without merging accounts. These editable frames are a design proposal; live status derivation and responsive acceptance require implementation tests.
