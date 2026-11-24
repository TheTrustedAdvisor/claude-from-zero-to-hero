# Solution 02-files

The table was generated with a fixed seed, so these numbers are the same for everyone.

| Region | Orders | Total CHF |
|---|---:|---:|
| East | 240 | 63,381.95 |
| North | 248 | 64,727.32 |
| South | 258 | 67,229.35 |
| West | 254 | 64,124.38 |
| **All** | **1,000** | **259,463.00** |

## Check values

- Rows: 1,000 (`=COUNTA(A:A)-1` in Excel, header not counted).
- Last row: `A-1000`, 2026-09-01, East, 189.53. If East comes out as 63,192.42, the last row is missing.
- South with `=SUMIF(C:C,"South",D:D)`: 67,229.35.

Other models, and later versions, word their answers differently; the totals must still match to the cent.

## Why the spot check

In the video, a chat without code read the spreadsheet only up to order A-0999 and still gave four plausible totals. One total was off by exactly the missing row. Counting rows and recomputing one region catches that in under a minute.
