# repairbay: IW claim / credit

Page: 01 · Core components

Source node: 8:381 · COMPONENT · 1192 × 188 px

[SVG reference](../svg/8-381--iw-claim-credit.svg) · [Layer properties](../json/8-381--iw-claim-credit.json)

## Layout structure

- IW claim / credit [COMPONENT; 1192 x 188] — layoutMode=VERTICAL, itemSpacing=12, paddingTop=16, paddingRight=16, paddingBottom=16, paddingLeft=16
  - IW claim / credit [TEXT; 117 x 22] — fontSize=15, textAlignHorizontal=LEFT
  - Claim number and total invoice amount, including labour, parts and oth [TEXT; 1160 x 20] — fontSize=13, textAlignHorizontal=LEFT
  - Fetch then claim fields [FRAME; 1160 x 62] — layoutMode=HORIZONTAL, itemSpacing=16, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
    - Fetch action [INSTANCE; 230 x 38] — layoutMode=HORIZONTAL, itemSpacing=8, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
      - Icon/download [INSTANCE; 16 x 24] — layoutMode=HORIZONTAL, itemSpacing=0, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
      - Fetch claim from GSPN [TEXT; 133 x 18] — fontSize=12, textAlignHorizontal=LEFT
    - Field/Text [INSTANCE; 430 x 62] — layoutMode=VERTICAL, itemSpacing=6, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
      - Model code [TEXT; 124 x 18] — fontSize=12, textAlignHorizontal=LEFT
      - Control [FRAME; 430 x 38] — layoutMode=HORIZONTAL, itemSpacing=8, paddingTop=10, paddingRight=10, paddingBottom=10, paddingLeft=10
    - Field/Text [INSTANCE; 468 x 62] — layoutMode=VERTICAL, itemSpacing=6, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
      - Model code [TEXT; 129 x 18] — fontSize=12, textAlignHorizontal=LEFT
      - Control [FRAME; 468 x 38] — layoutMode=HORIZONTAL, itemSpacing=8, paddingTop=10, paddingRight=10, paddingBottom=10, paddingLeft=10
  - Automatic claim lookup will be connected later. Enter the claim number [TEXT; 1160 x 16] — fontSize=11, textAlignHorizontal=LEFT

## Text layers in source order

IW claim / credit

Claim number and total invoice amount, including labour, parts and other charges. This does not confirm approval or payment.

Fetch claim from GSPN

Claim / credit number

Total claim amount (£)

Automatic claim lookup will be connected later. Enter the claim number and amount manually for now.
