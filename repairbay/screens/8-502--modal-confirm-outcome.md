# repairbay: Modal / confirm outcome

Page: 01 · Core components

Source node: 8:502 · COMPONENT · 620 × 268 px

[SVG reference](../svg/8-502--modal-confirm-outcome.svg) · [Layer properties](../json/8-502--modal-confirm-outcome.json)

## Layout structure

- Modal / confirm outcome [COMPONENT; 620 x 268] — layoutMode=VERTICAL, itemSpacing=0, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
  - Modal header [FRAME; 620 x 76] — layoutMode=HORIZONTAL, itemSpacing=12, paddingTop=24, paddingRight=24, paddingBottom=24, paddingLeft=24
    - Confirm repair outcome [TEXT; 520 x 28] — fontSize=21, textAlignHorizontal=LEFT
    - Icon/x [INSTANCE; 20 x 24] — layoutMode=HORIZONTAL, itemSpacing=0, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
      - Editable vector [FRAME; 24 x 24] — layoutMode=NONE, itemSpacing=0, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
  - Modal body [FRAME; 620 x 104] — layoutMode=VERTICAL, itemSpacing=16, paddingTop=24, paddingRight=24, paddingBottom=24, paddingLeft=24
    - Confirming will lock this repair. All job fields become read-only. [TEXT; 572 x 20] — fontSize=13, textAlignHorizontal=LEFT
    - The repair remains in Active jobs for seven days, then moves to the ar [TEXT; 572 x 20] — fontSize=13, textAlignHorizontal=LEFT
  - Modal footer [FRAME; 620 x 86] — layoutMode=HORIZONTAL, itemSpacing=12, paddingTop=24, paddingRight=24, paddingBottom=24, paddingLeft=24
    - Button/Secondary [INSTANCE; 100 x 38] — layoutMode=HORIZONTAL, itemSpacing=6, paddingTop=0, paddingRight=14, paddingBottom=0, paddingLeft=14
      - Discard [TEXT; 41 x 18] — fontSize=12, textAlignHorizontal=LEFT
    - Button/Primary [INSTANCE; 212 x 38] — layoutMode=HORIZONTAL, itemSpacing=6, paddingTop=0, paddingRight=14, paddingBottom=0, paddingLeft=14
      - Save changes [TEXT; 136 x 18] — fontSize=12, textAlignHorizontal=LEFT

## Text layers in source order

Confirm repair outcome

Confirming will lock this repair. All job fields become read-only.

The repair remains in Active jobs for seven days, then moves to the archive.

Cancel

Confirm and lock repair
