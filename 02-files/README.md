# Exercise 02-files

Companion exercise to part 2 of "Claude from Zero to Hero": "Claude with your files: PDFs, spreadsheets and checking the numbers". Runs in any Claude plan, Free included; step 4 needs Pro or higher.

## Task

`orders.xlsx` (and the same data as `orders.csv`) holds 1,000 orders, a different set from the one in the video, from July to September 2026 with `order_id`, `order_date`, `region` and `amount_chf`.

1. In a normal chat (not incognito), upload `orders.xlsx` and ask: `What is the total amount per region? Show me how many rows you read.`
2. Note the four totals and the row count.
3. Check one number yourself: open `orders.xlsx` in Excel (or any spreadsheet app) and compute the total for **one** region with `=SUMIF(C:C,"South",D:D)`. Count the rows with `=COUNTA(A:A)-1`.
4. Optional, Pro and higher: ask Claude to put the table into a Claude sheet with a Totals tab that uses SUMIF formulas. Click one total and read its formula. If Claude asks whether it may upload your file to the sheet, allow it once.

## What a good result looks like

- 1,000 rows read.
- Four totals that match `solution/SOLUTION.md` to the cent.
- Your own SUMIF for one region gives the same number as Claude's.

If Claude says it read 999 rows, or "added these up by hand", don't use the numbers: ask it to run code on the whole file, or check that "Create and edit files" is on under Settings > Capabilities.

## Check yourself

`solution/SOLUTION.md`.
