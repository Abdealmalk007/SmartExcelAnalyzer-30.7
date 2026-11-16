# SmartExcelAnalyzer v30.7.9 — All Categories Analytics (Beta / Preview)

**PRO TECH | Windows 10/11 x64 | 16 November 2026**

This release brings the approved Arabic-first RTL analytics workspace and fixes the long-standing Top-N limitation.

## Improvements
- Modernized desktop analytics workspace with Arabic (RTL) as default and optional English.
- Automatically detect headers and compatible tables despite preamble text, empty rows, or repeated report headings; preserve original source data and allow selection of an individual table.
- Search within a selected column or across all columns; update Dashboard results based on the filtered rows.
- Group by *any* selected column independent of the search column, including every showroom employee, branch, porcelain color, customer, or item.
- Support Count / Sum / Average / Min / Max on eligible numeric measures; protect telephone numbers, dates and ID columns from accidental summation.
- **Complete category browser** within the Dashboard with name search, 60 categories per page, and full CSV export (not restricted to current page or a Top-N threshold).
- Summary charts remain a readable **Top 8 preview**; donut chart has an "Other" segment. All individual categories and their counts are available in the complete category browser and exported CSV.
- Portable ZIP is provided alongside the Windows Setup installer.

## Verification
- Data engine: **32/32 tests passed**; representative cases with 75 employees, 120 branches, 250 porcelain colors, and 10,000 distinct categories retained.
- Windows GUI: **29/29 tests passed**, including changing group columns, searching the last category, pagination, and full 250-category CSV export.
- Frozen EXE: **13/13 tests passed**; extracted Portable: **9/9 tests passed**.
- **25/25** installer tests passed using a separate QA installer with a different AppId and identical release payload. The public installer was **not** installed over the existing 30.7.5 user installation.
- SHA-256 hashes are provided in the release asset `SHA256SUMS.txt`.

## Limitations and installation
**Beta / Preview**. No trusted Authenticode code-signing certificate was available, so Windows SmartScreen may warn; do not disable operating-system protection to bypass it. Verify the SHA-256 fingerprints and back up your existing files before upgrading.

The published public Setup file has not had an independent clean-install / in-place-upgrade acceptance pass, and visual pixel-by-pixel comparison with the concept mockup is not certified. Not all unusual, corrupted, encrypted or radically different Excel workbooks can be guaranteed to parse automatically.

**Recommended for evaluation before production rollout.** Earlier versions remain available in GitHub Releases.

## Downloads
- [Windows Setup 30.7.9](https://github.com/Abdealmalk007/SmartExcelAnalyzer-30.7/releases/download/v30.7.9/SmartExcelAnalyzer_30.7.9_Setup.exe)
- [Windows Portable 30.7.9](https://github.com/Abdealmalk007/SmartExcelAnalyzer-30.7/releases/download/v30.7.9/SmartExcelAnalyzer_30.7.9_PORTABLE.zip)

© 2026–2027 PRO TECH. **All Rights Reserved**; applicable third-party licenses remain in effect.
