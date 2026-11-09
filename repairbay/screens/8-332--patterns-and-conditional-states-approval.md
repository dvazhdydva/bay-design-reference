# repairbay: Patterns and conditional states · approval

Page: 01 · Core components

Source node: 8:332 · FRAME · 1380 × 2048 px

[SVG reference](../svg/8-332--patterns-and-conditional-states-approval.svg) · [Layer properties](../json/8-332--patterns-and-conditional-states-approval.json)

## Layout structure

- Patterns and conditional states · approval [FRAME; 1380 x 2048] — layoutMode=VERTICAL, itemSpacing=24, paddingTop=32, paddingRight=32, paddingBottom=32, paddingLeft=32
  - RepairBay / patterns & conditional states [TEXT; 418 x 28] — fontSize=21, textAlignHorizontal=LEFT
  - Core behaviours for the repair card. These examples document existing  [TEXT; 1316 x 20] — fontSize=13, textAlignHorizontal=LEFT
  - Fetch target preview / hover and keyboard focus [FRAME; 1316 x 304] — layoutMode=VERTICAL, itemSpacing=16, paddingTop=20, paddingRight=20, paddingBottom=20, paddingLeft=20
    - Fetch target preview / hover and keyboard focus [TEXT; 496 x 28] — fontSize=21, textAlignHorizontal=LEFT
    - Only the targets of the focused fetch action are highlighted. Source t [TEXT; 1276 x 20] — fontSize=13, textAlignHorizontal=LEFT
    - Target mapping · GSPN [FRAME; 1276 x 50] — layoutMode=HORIZONTAL, itemSpacing=16, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
      - Fetch action [INSTANCE; 230 x 38] — layoutMode=HORIZONTAL, itemSpacing=8, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
      - Targets [FRAME; 1000 x 50] — layoutMode=VERTICAL, itemSpacing=8, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
    - Target mapping · Simpro [FRAME; 1276 x 50] — layoutMode=HORIZONTAL, itemSpacing=16, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
      - Fetch action [INSTANCE; 230 x 38] — layoutMode=HORIZONTAL, itemSpacing=8, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
      - Targets [FRAME; 1000 x 50] — layoutMode=VERTICAL, itemSpacing=8, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
    - Target mapping · IW claim [FRAME; 1276 x 50] — layoutMode=HORIZONTAL, itemSpacing=16, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
      - Fetch action [INSTANCE; 230 x 38] — layoutMode=HORIZONTAL, itemSpacing=8, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
      - Targets [FRAME; 1000 x 50] — layoutMode=VERTICAL, itemSpacing=8, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
  - IW claim / credit · conditional footer [FRAME; 1316 x 310] — layoutMode=VERTICAL, itemSpacing=16, paddingTop=20, paddingRight=20, paddingBottom=20, paddingLeft=20
    - IW claim / credit · conditional footer [TEXT; 365 x 28] — fontSize=21, textAlignHorizontal=LEFT
    - No surrounding frame. Claim fetch is teal and distinct from blue parts [TEXT; 1276 x 20] — fontSize=13, textAlignHorizontal=LEFT
    - IW claim / credit [INSTANCE; 1276 x 188] — layoutMode=VERTICAL, itemSpacing=12, paddingTop=16, paddingRight=16, paddingBottom=16, paddingLeft=16
      - IW claim / credit [TEXT; 117 x 22] — fontSize=15, textAlignHorizontal=LEFT
      - Claim number and total invoice amount, including labour, parts and oth [TEXT; 1160 x 20] — fontSize=13, textAlignHorizontal=LEFT
      - Fetch then claim fields [FRAME; 1160 x 62] — layoutMode=HORIZONTAL, itemSpacing=16, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
      - Automatic claim lookup will be connected later. Enter the claim number [TEXT; 1160 x 16] — fontSize=11, textAlignHorizontal=LEFT
  - OOW approval [FRAME; 1316 x 276] — layoutMode=VERTICAL, itemSpacing=16, paddingTop=20, paddingRight=20, paddingBottom=20, paddingLeft=20
    - OOW approval [TEXT; 149 x 28] — fontSize=21, textAlignHorizontal=LEFT
    - Conditional fields keep the same 6 px label gap, 24 px columns and 38  [TEXT; 1276 x 20] — fontSize=13, textAlignHorizontal=LEFT
    - OOW approval [INSTANCE; 1276 x 154] — layoutMode=VERTICAL, itemSpacing=16, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
      - OOW approval [TEXT; 105 x 22] — fontSize=15, textAlignHorizontal=LEFT
      - Approval fields [FRAME; 1192 x 62] — layoutMode=HORIZONTAL, itemSpacing=24, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
      - Button/Secondary [INSTANCE; 160 x 38] — layoutMode=HORIZONTAL, itemSpacing=6, paddingTop=0, paddingRight=14, paddingBottom=0, paddingLeft=14
  - WEEE approval [FRAME; 1316 x 222] — layoutMode=VERTICAL, itemSpacing=16, paddingTop=20, paddingRight=20, paddingBottom=20, paddingLeft=20
    - WEEE approval [TEXT; 155 x 28] — fontSize=21, textAlignHorizontal=LEFT
    - Conditional fields keep the same 6 px label gap, 24 px columns and 38  [TEXT; 1276 x 20] — fontSize=13, textAlignHorizontal=LEFT
    - WEEE approval [INSTANCE; 1276 x 100] — layoutMode=VERTICAL, itemSpacing=16, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
      - WEEE approval [TEXT; 109 x 22] — fontSize=15, textAlignHorizontal=LEFT
      - Approval fields [FRAME; 1192 x 62] — layoutMode=HORIZONTAL, itemSpacing=24, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
  - Confirmation modal [FRAME; 1316 x 390] — layoutMode=VERTICAL, itemSpacing=16, paddingTop=20, paddingRight=20, paddingBottom=20, paddingLeft=20
    - Confirmation modal [TEXT; 204 x 28] — fontSize=21, textAlignHorizontal=LEFT
    - Example width 620; header/footer padding24, radius6. Do not open an ir [TEXT; 1276 x 20] — fontSize=13, textAlignHorizontal=LEFT
    - Modal / confirm outcome [INSTANCE; 620 x 268] — layoutMode=VERTICAL, itemSpacing=0, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
      - Modal header [FRAME; 620 x 76] — layoutMode=HORIZONTAL, itemSpacing=12, paddingTop=24, paddingRight=24, paddingBottom=24, paddingLeft=24
      - Modal body [FRAME; 620 x 104] — layoutMode=VERTICAL, itemSpacing=16, paddingTop=24, paddingRight=24, paddingBottom=24, paddingLeft=24
      - Modal footer [FRAME; 620 x 86] — layoutMode=HORIZONTAL, itemSpacing=12, paddingTop=24, paddingRight=24, paddingBottom=24, paddingLeft=24
  - Repair status icons / 24 px [FRAME; 1316 x 266] — layoutMode=VERTICAL, itemSpacing=16, paddingTop=20, paddingRight=20, paddingBottom=20, paddingLeft=20
    - Repair status icons / 24 px [TEXT; 272 x 28] — fontSize=21, textAlignHorizontal=LEFT
    - Icons only in job-list cells, with accessible names and tooltips. Arch [TEXT; 1276 x 20] — fontSize=13, textAlignHorizontal=LEFT
    - Status icon row [FRAME; 1276 x 24] — layoutMode=HORIZONTAL, itemSpacing=16, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
      - Registered [FRAME; 300 x 24] — layoutMode=HORIZONTAL, itemSpacing=10, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
      - Assessment [FRAME; 300 x 24] — layoutMode=HORIZONTAL, itemSpacing=10, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
      - Parts required [FRAME; 300 x 24] — layoutMode=HORIZONTAL, itemSpacing=10, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
      - Awaiting parts [FRAME; 300 x 24] — layoutMode=HORIZONTAL, itemSpacing=10, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
    - Status icon row [FRAME; 1276 x 24] — layoutMode=HORIZONTAL, itemSpacing=16, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
      - Ready to repair [FRAME; 300 x 24] — layoutMode=HORIZONTAL, itemSpacing=10, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
      - Repair in progress [FRAME; 300 x 24] — layoutMode=HORIZONTAL, itemSpacing=10, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
      - Awaiting OOW approval [FRAME; 300 x 24] — layoutMode=HORIZONTAL, itemSpacing=10, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
      - DOA received [FRAME; 300 x 24] — layoutMode=HORIZONTAL, itemSpacing=10, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
    - Status icon row [FRAME; 1276 x 24] — layoutMode=HORIZONTAL, itemSpacing=16, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
      - Returns pending [FRAME; 300 x 24] — layoutMode=HORIZONTAL, itemSpacing=10, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
      - Repaired [FRAME; 300 x 24] — layoutMode=HORIZONTAL, itemSpacing=10, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
      - QC pass [FRAME; 300 x 24] — layoutMode=HORIZONTAL, itemSpacing=10, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
      - WEEE [FRAME; 300 x 24] — layoutMode=HORIZONTAL, itemSpacing=10, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
    - Status icon row [FRAME; 1276 x 24] — layoutMode=HORIZONTAL, itemSpacing=16, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0
      - Archive marker [FRAME; 300 x 24] — layoutMode=HORIZONTAL, itemSpacing=10, paddingTop=0, paddingRight=0, paddingBottom=0, paddingLeft=0

## Text layers in source order

RepairBay / patterns & conditional states

Core behaviours for the repair card. These examples document existing rules; sample PO data below is illustrative.

Fetch target preview / hover and keyboard focus

Only the targets of the focused fetch action are highlighted. Source tags stay subtle at rest. Focus and hover have the same target mapping.

Fetch from GSPN

Model · Model code · Version · Purchase date · Warranty expiry

GSPN

Fetch from Simpro

Job site · Franchisee / Fz · Received · Repair comments

Simpro

Fetch claim from GSPN

Claim / credit number · Total claim amount (£)

GSPN claim

IW claim / credit · conditional footer

No surrounding frame. Claim fetch is teal and distinct from blue parts fetching.

IW claim / credit

Claim number and total invoice amount, including labour, parts and other charges. This does not confirm approval or payment.

Fetch claim from GSPN

Claim / credit number

Total claim amount (£)

Automatic claim lookup will be connected later. Enter the claim number and amount manually for now.

OOW approval

Conditional fields keep the same 6 px label gap, 24 px columns and 38 px controls.

OOW approval

Approved by

Approval date

Copy OOW details

WEEE approval

Conditional fields keep the same 6 px label gap, 24 px columns and 38 px controls.

WEEE approval

Approved by

Approval date

Approval source

Email, phone call, etc.

Confirmation modal

Example width 620; header/footer padding24, radius6. Do not open an irreversible action from a disclosure click.

Confirm repair outcome

Confirming will lock this repair. All job fields become read-only.

The repair remains in Active jobs for seven days, then moves to the archive.

Cancel

Confirm and lock repair

Repair status icons / 24 px

Icons only in job-list cells, with accessible names and tooltips. Archive is a secondary marker; it never replaces the repair outcome.

Registered

Assessment

Parts required

Awaiting parts

Ready to repair

Repair in progress

Awaiting OOW approval

DOA received

Returns pending

Repaired

QC pass

WEEE

Archive marker
