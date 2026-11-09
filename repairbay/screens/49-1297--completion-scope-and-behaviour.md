# repairbay: Completion scope and behaviour

Page: 06 · Forms, admin & remaining screens

Source node: 49:1297 · FRAME · 1100 × 422 px

[SVG reference](../svg/49-1297--completion-scope-and-behaviour.svg) · [Layer properties](../json/49-1297--completion-scope-and-behaviour.json)

## Layout structure

- Completion scope and behaviour [FRAME; 1100 x 422] — layoutMode=VERTICAL, itemSpacing=16, paddingTop=32, paddingRight=32, paddingBottom=32, paddingLeft=32
  - Remaining screens · implementation contract [TEXT; 465 x 28] — fontSize=21, textAlignHorizontal=LEFT
  - Preserve all existing form fields, permissions and server validation. [TEXT; 1036 x 20] — fontSize=13, textAlignHorizontal=LEFT
  - Archived jobs reuse the active-list grid, retain outcome colours, and  [TEXT; 1036 x 20] — fontSize=13, textAlignHorizontal=LEFT
  - Forms use shared Inter styles, 38 px controls, 24 px columns, six-pixe [TEXT; 1036 x 20] — fontSize=13, textAlignHorizontal=LEFT
  - External-form action comes before its resulting reference inside a das [TEXT; 1036 x 40] — fontSize=13, textAlignHorizontal=LEFT
  - PO confirmation locks order contents; free parts remain selectable/rem [TEXT; 1036 x 40] — fontSize=13, textAlignHorizontal=LEFT
  - Administration remains company scoped. Signed-in users cannot delete t [TEXT; 1036 x 20] — fontSize=13, textAlignHorizontal=LEFT
  - About uses Ctrl+F1, accessible release notes and unavailable User manu [TEXT; 1036 x 20] — fontSize=13, textAlignHorizontal=LEFT
  - This design inventory includes existing standalone forms as well as mo [TEXT; 1036 x 20] — fontSize=13, textAlignHorizontal=LEFT

## Text layers in source order

Remaining screens · implementation contract

Preserve all existing form fields, permissions and server validation.

Archived jobs reuse the active-list grid, retain outcome colours, and keep archive distinct from repair outcome.

Forms use shared Inter styles, 38 px controls, 24 px columns, six-pixel label gaps. Errors appear beside fields; success/failure never silently clears entered values.

External-form action comes before its resulting reference inside a dashed group. Fetch actions use source colours and capability badges, with affected fields highlighted on hover/focus.

PO confirmation locks order contents; free parts remain selectable/removable. Outcome confirmation locks the repair and records date/engineer. WEEE requires external approval details.

Administration remains company scoped. Signed-in users cannot delete themselves. Do not expose hidden owner capabilities in public help or release notes.

About uses Ctrl+F1, accessible release notes and unavailable User manual. Login remains compact at effective1280×~650 viewport.

This design inventory includes existing standalone forms as well as modal variants; preserve route and server semantics during implementation.
