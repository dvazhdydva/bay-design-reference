# repairbay: Save controls

Page: 01 · Core components

Source node: 4:774 · COMPONENT_SET · 488 × 266 px

[SVG reference](../svg/4-774--save-controls.svg) · [Layer properties](../json/4-774--save-controls.json)

## Layout structure

- Save controls [COMPONENT_SET; 488 x 266] — layoutMode=NONE, itemSpacing=0, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
  - State=Saved [COMPONENT; 390 x 38] — layoutMode=HORIZONTAL, itemSpacing=12, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
    - Saved [TEXT; 130 x 18] — fontSize=12, textAlignHorizontal=LEFT
    - Button/Secondary [INSTANCE; 95 x 38] — layoutMode=HORIZONTAL, itemSpacing=6, paddingTop=0, paddingRight=14, paddingBottom=0, paddingLeft=14
      - Discard [TEXT; 45 x 18] — fontSize=12, textAlignHorizontal=LEFT
    - Button/Primary [INSTANCE; 140 x 38] — layoutMode=HORIZONTAL, itemSpacing=6, paddingTop=0, paddingRight=14, paddingBottom=0, paddingLeft=14
      - Save changes [TEXT; 81 x 18] — fontSize=12, textAlignHorizontal=LEFT
  - State=Unsaved [COMPONENT; 390 x 38] — layoutMode=HORIZONTAL, itemSpacing=12, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
    - ● Unsaved changes [TEXT; 130 x 18] — fontSize=12, textAlignHorizontal=LEFT
    - Button/Secondary [INSTANCE; 95 x 38] — layoutMode=HORIZONTAL, itemSpacing=6, paddingTop=0, paddingRight=14, paddingBottom=0, paddingLeft=14
      - Discard [TEXT; 45 x 18] — fontSize=12, textAlignHorizontal=LEFT
    - Button/Primary [INSTANCE; 140 x 38] — layoutMode=HORIZONTAL, itemSpacing=6, paddingTop=0, paddingRight=14, paddingBottom=0, paddingLeft=14
      - Save changes [TEXT; 81 x 18] — fontSize=12, textAlignHorizontal=LEFT
  - State=Saving [COMPONENT; 390 x 38] — layoutMode=HORIZONTAL, itemSpacing=12, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
    - Saving… [TEXT; 130 x 18] — fontSize=12, textAlignHorizontal=LEFT
    - Button/Secondary [INSTANCE; 95 x 38] — layoutMode=HORIZONTAL, itemSpacing=6, paddingTop=0, paddingRight=14, paddingBottom=0, paddingLeft=14
      - Discard [TEXT; 45 x 18] — fontSize=12, textAlignHorizontal=LEFT
    - Button/Primary [INSTANCE; 140 x 38] — layoutMode=HORIZONTAL, itemSpacing=6, paddingTop=0, paddingRight=14, paddingBottom=0, paddingLeft=14
      - Icon/loader [INSTANCE; 16 x 24] — layoutMode=HORIZONTAL, itemSpacing=0, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
      - Saving… [TEXT; 49 x 18] — fontSize=12, textAlignHorizontal=LEFT

## Text layers in source order

Saved

Discard

Save changes

● Unsaved changes

Discard

Save changes

Saving…

Discard

Saving…
