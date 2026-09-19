# Lot Drawer

Google Sheets is the only data source.

Spreadsheet ID: `1LtBZ-hZaZurSwKl-E44WWt8IUxRPT2wnZvcru6ALlo0`

Mapping:
- B1 = Subject tab title; B2:B21 = Subject items
- C1 = Plot tab title; C2:C21 = Plot items
- D1 = Twist tab title; D2:D21 = Twist items

Blank cells from rows 2–21 are ignored. No localStorage, add, edit, or delete controls are used.

The page fetches B1:B21, C1:C21, and D1:D21 independently using Google Visualization JSON with `headers=0`, so row 1 is treated as data rather than a response header.
