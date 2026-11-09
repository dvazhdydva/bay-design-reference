# repairbay: Returns · implementation rules and review

Page: 04 · Returns

Source node: 36:1390 · FRAME · 1100 × 1150 px

[SVG reference](../svg/36-1390--returns-implementation-rules-and-review.svg) · [Layer properties](../json/36-1390--returns-implementation-rules-and-review.json)

## Layout structure

- Returns · implementation rules and review [FRAME; 1100 x 1150] — layoutMode=VERTICAL, itemSpacing=18, paddingTop=32, paddingRight=32, paddingBottom=32, paddingLeft=32
  - Returns · review notes [TEXT; 229 x 28] — fontSize=21, textAlignHorizontal=LEFT
  - Editable design examples, not live shipment records. Reuses RepairBay  [TEXT; 1036 x 20] — fontSize=13, textAlignHorizontal=LEFT
  - Warehouse context [TEXT; 142 x 22] — fontSize=15, textAlignHorizontal=LEFT
  - Use the authorized current/home warehouse and persist selection for th [TEXT; 1036 x 20] — fontSize=13, textAlignHorizontal=LEFT
  - Pending → shipment [TEXT; 150 x 22] — fontSize=15, textAlignHorizontal=LEFT
  - Return required only. Oldest completed repairs first. Allow individual [TEXT; 1036 x 40] — fontSize=13, textAlignHorizontal=LEFT
  - Shipment status [TEXT; 119 x 22] — fontSize=15, textAlignHorizontal=LEFT
  - Done when relevant fields are valid; In progress for partially entered [TEXT; 1036 x 40] — fontSize=13, textAlignHorizontal=LEFT
  - Accordion behaviour [TEXT; 151 x 22] — fontSize=15, textAlignHorizontal=LEFT
  - Collapse Done sections on page entry only. User-opened sections remain [TEXT; 1036 x 40] — fontSize=13, textAlignHorizontal=LEFT
  - Save and operations [TEXT; 148 x 22] — fontSize=15, textAlignHorizontal=LEFT
  - Saved / Unsaved / Saving / failure states follow the repair card. Disc [TEXT; 1036 x 40] — fontSize=13, textAlignHorizontal=LEFT
  - Cargo calculation [TEXT; 127 x 22] — fontSize=15, textAlignHorizontal=LEFT
  - Length=max(pallet length, longest box); width=max(pallet width, sum of [TEXT; 1036 x 40] — fontSize=13, textAlignHorizontal=LEFT
  - Documents [TEXT; 84 x 22] — fontSize=15, textAlignHorizontal=LEFT
  - Preserve commercial invoice generation, record/sent date, return label [TEXT; 1036 x 40] — fontSize=13, textAlignHorizontal=LEFT
  - Read-only / archive [TEXT; 141 x 22] — fontSize=15, textAlignHorizontal=LEFT
  - Courier reference + collection date completes shipment. Archive seven  [TEXT; 1036 x 20] — fontSize=13, textAlignHorizontal=LEFT
  - Pallet removal [TEXT; 102 x 22] — fontSize=15, textAlignHorizontal=LEFT
  - At least one pallet; move assigned parts before deletion. Extra empty  [TEXT; 1036 x 40] — fontSize=13, textAlignHorizontal=LEFT
  - Accessibility [TEXT; 93 x 22] — fontSize=15, textAlignHorizontal=LEFT
  - Keyboard-operable tabs and section disclosures; focus visible; names f [TEXT; 1036 x 40] — fontSize=13, textAlignHorizontal=LEFT
  - Visual scope [TEXT; 93 x 22] — fontSize=15, textAlignHorizontal=LEFT
  - Inter UI, existing field height, navy headings, green active-section b [TEXT; 1036 x 20] — fontSize=13, textAlignHorizontal=LEFT

## Text layers in source order

Returns · review notes

Editable design examples, not live shipment records. Reuses RepairBay tokens and controls.

Warehouse context

Use the authorized current/home warehouse and persist selection for the session. No cross-company records.

Pending → shipment

Return required only. Oldest completed repairs first. Allow individual/group selection. Mixed IW/OOW/DOA selection must be explained and cannot create a mixed shipment.

Shipment status

Done when relevant fields are valid; In progress for partially entered data; Pending for essential missing values. Section badge at the far right; Packing list Add part immediately before it.

Accordion behaviour

Collapse Done sections on page entry only. User-opened sections remain open through edits, saves and completion. Expanded review frame intentionally reveals all fields.

Save and operations

Saved / Unsaved / Saving / failure states follow the repair card. Discard restores saved data. Preserve edits before add/remove operations; do not block deleting a genuinely empty pallet with a false dirty state.

Cargo calculation

Length=max(pallet length, longest box); width=max(pallet width, sum of box widths); height=pallet+highest box only when pallet height is lower, otherwise keep pallet height. Gross=tare+assigned part weights. P1 example: 150×200×98 cm; 45 kg gross, 25 kg net.

Documents

Preserve commercial invoice generation, record/sent date, return labels and box-only handling symbols. Explain every disabled prerequisite next to its action. Do not invent a manual cargo override until agreed.

Read-only / archive

Courier reference + collection date completes shipment. Archive seven days later. Retain documents and access to details; no editing collected shipments.

Pallet removal

At least one pallet; move assigned parts before deletion. Extra empty pallets removable. Existing maximum four pallets retained. Destructive actions separated from routine controls.

Accessibility

Keyboard-operable tabs and section disclosures; focus visible; names for selection/trash icons; status conveyed by text as well as colour. No horizontal scrolling at1280 CSS px.

Visual scope

Inter UI, existing field height, navy headings, green active-section bottom rule. English UI. No production or application code change.
