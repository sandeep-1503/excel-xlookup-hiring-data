# XLOOKUP Practice: Hiring Data

A small Excel workbook that shows how `XLOOKUP` works, using sample hiring data.

## What's inside
- **Candidates** sheet: 8 made-up candidates (ID, name, source, role, status, days to hire).
- **XLOOKUP Demo** sheet: pick a Candidate ID from the dropdown and XLOOKUP returns that candidate's details.
  An `INDEX/MATCH` column sits beside it as a cross-check.

## Formula
```
=XLOOKUP($B$3, Candidates!$A$2:$A$9, Candidates!$B$2:$B$9, "Not found")
```
`lookup value, lookup column, return column, text if not found`

## Why XLOOKUP over VLOOKUP
- Returns from any column, no column index number
- Can look left as well as right
- Exact match by default
- Built-in "not found" message

## Tools
Microsoft Excel 365 / Excel 2021+ (XLOOKUP is not available in older versions).

*All data is fictional and for practice only.*
