# repairbay: Spare parts · behaviour and review notes

Page: 05 · Spare parts

Source node: 43:1026 · FRAME · 1080 × 1144 px

[SVG reference](../svg/43-1026--spare-parts-behaviour-and-review-notes.svg) · [Layer properties](../json/43-1026--spare-parts-behaviour-and-review-notes.json)

## Layout structure

- Spare parts · behaviour and review notes [FRAME; 1080 x 1144] — layoutMode=VERTICAL, itemSpacing=16, paddingTop=32, paddingRight=32, paddingBottom=32, paddingLeft=32
  - Spare parts · design specification [TEXT; 344 x 28] — fontSize=21, textAlignHorizontal=LEFT
  - Same navy header, green active-section rule, Inter type, compact field [TEXT; 1016 x 20] — fontSize=13, textAlignHorizontal=LEFT
  - Part identity [TEXT; 90 x 22] — fontSize=15, textAlignHorizontal=LEFT
  - Part number is the identifier. No serial-number field. Quantity and wa [TEXT; 1016 x 40] — fontSize=13, textAlignHorizontal=LEFT
  - Known part lookup [TEXT; 137 x 22] — fontSize=15, textAlignHorizontal=LEFT
  - On leaving Part number, look up the known description, bulletins and r [TEXT; 1016 x 40] — fontSize=13, textAlignHorizontal=LEFT
  - GSPN fetch [TEXT; 84 x 22] — fontSize=15, textAlignHorizontal=LEFT
  - Only beside a single Part number inside Add part. Fetch fills Descript [TEXT; 1016 x 40] — fontSize=13, textAlignHorizontal=LEFT
  - Other warehouses [TEXT; 134 x 22] — fontSize=15, textAlignHorizontal=LEFT
  - Unchecked by default. Show only authorized warehouses in the company.  [TEXT; 1016 x 40] — fontSize=13, textAlignHorizontal=LEFT
  - Bulletins and history [TEXT; 149 x 22] — fontSize=15, textAlignHorizontal=LEFT
  - Reuse documents from previous POs/repairs by part number. Automaticall [TEXT; 1016 x 40] — fontSize=13, textAlignHorizontal=LEFT
  - Stock take [TEXT; 77 x 22] — fontSize=15, textAlignHorizontal=LEFT
  - Enter/scan part number and total quantity found. Repeat replaces, not  [TEXT; 1016 x 40] — fontSize=13, textAlignHorizontal=LEFT
  - Missing entries [TEXT; 111 x 22] — fontSize=15, textAlignHorizontal=LEFT
  - Not entered/scanned entries remain separate as Not yet counted. Explic [TEXT; 1016 x 40] — fontSize=13, textAlignHorizontal=LEFT
  - Save boundaries [TEXT; 121 x 22] — fontSize=15, textAlignHorizontal=LEFT
  - Add to stock applies a normal addition. Save counted part changes the  [TEXT; 1016 x 40] — fontSize=13, textAlignHorizontal=LEFT
  - Repair stock use [TEXT; 121 x 22] — fontSize=15, textAlignHorizontal=LEFT
  - Existing repair allocation deducts stock; deleting the associated repa [TEXT; 1016 x 40] — fontSize=13, textAlignHorizontal=LEFT
  - Accessibility and density [TEXT; 182 x 22] — fontSize=15, textAlignHorizontal=LEFT
  - 1280 CSS px target, 38 px fields, comfortable compact row height, no h [TEXT; 1016 x 40] — fontSize=13, textAlignHorizontal=LEFT
  - Scope [TEXT; 46 x 22] — fontSize=15, textAlignHorizontal=LEFT
  - Editable design only. Example inventory/counts are illustrative. Produ [TEXT; 1016 x 20] — fontSize=13, textAlignHorizontal=LEFT

## Text layers in source order

Spare parts · design specification

Same navy header, green active-section rule, Inter type, compact fields and shared controls as the repair card.

Part identity

Part number is the identifier. No serial-number field. Quantity and warehouse/location identify a stock entry. Free-text locations such as Crate #2; display Warehouse / Location.

Known part lookup

On leaving Part number, look up the known description, bulletins and repair history. Fill an untouched description; never silently overwrite user-entered text. The underlying part-number knowledge base links records across authorized warehouses.

GSPN fetch

Only beside a single Part number inside Add part. Fetch fills Description only. Blue GSPN cue; hover/focus highlights Description, not Quantity/Location/Warehouse. Source badge means capability, not provenance. Require Chrome bridge and signed-in GSPN; explain unavailable, timeout, retry and outdated-extension states.

Other warehouses

Unchecked by default. Show only authorized warehouses in the company. Other warehouse rows carry a textual badge as well as a blue tint; no implied automatic transfer or courier booking.

Bulletins and history

Reuse documents from previous POs/repairs by part number. Automatically show available linked bulletins, with downloadable files and repair-history links. Preserve authorization when opening or downloading them.

Stock take

Enter/scan part number and total quantity found. Repeat replaces, not increments. Multiple storage locations require individual counts. New part/location prompts Add part with quantity and Fetch from GSPN. No serial-number workflow.

Missing entries

Not entered/scanned entries remain separate as Not yet counted. Explicit Out of stock confirmation records zero. Do not auto-zero unscanned stock. Confirmation applies counts; cancelling draft applies nothing.

Save boundaries

Add to stock applies a normal addition. Save counted part changes the draft count, not inventory. Confirm stock take applies reconciliation, then read-only. Keep cancel and destructive confirmation distinct.

Repair stock use

Existing repair allocation deducts stock; deleting the associated repair/part restores it under existing rules. Stock availability prompts remain in repair workflow; no new ordering workflow is invented here.

Accessibility and density

1280 CSS px target, 38 px fields, comfortable compact row height, no horizontal overflow. Stock table document cells use links/icons, no new top-level Fetch button. Modal body scrolls when necessary; header/actions remain available.

Scope

Editable design only. Example inventory/counts are illustrative. Production, local database and application code are unchanged.
