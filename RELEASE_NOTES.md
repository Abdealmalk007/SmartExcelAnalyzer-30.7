# SmartExcelAnalyzer v30.7.6 — Windows Beta / Preview

**PRO TECH · 15 November 2026 · Windows 10/11 x64**

## What's new
- Corrected Arabic first-run license dialog with an always-visible acceptance control.
- Fixed the frozen EXE startup dependencies (CustomTkinter/Tcl/Tk) and main-window transition.
- Added automatic Excel analysis and a responsive multi-chart Dashboard with KPI values.
- Added semantic detection of amounts, meters, quantities, employee and showroom fields; identifier columns are excluded from summation.
- Verified XLS, XLSX, XLSM, XLSB, CSV samples and Excel/JSON/PDF exports.
- Packaged both Setup EXE and extracted-and-tested Portable ZIP.

## Quality evidence and limitations
- **27/27** isolated Windows installer checks passed, including the installed GUI, exports and data-preserving uninstallation.
- **10/10** extracted Portable checks passed.
- The installed QA payload matches the public build, but the **public Setup EXE was not installed over an existing 30.7.5 system**. The QA installer had a distinct AppId to avoid touching the current installation.
- This is a **Beta/Preview**, and **no trusted Authenticode code-signing certificate** was available. Windows SmartScreen might warn. Back up existing data before upgrading.
- Unusual, password-protected, damaged or otherwise incompatible workbooks may still need additional testing.

[Download Setup](https://github.com/Abdealmalk007/SmartExcelAnalyzer-30.7/releases/download/v30.7.6/SmartExcelAnalyzer_30.7.6_Setup.exe) · [Download Portable ZIP](https://github.com/Abdealmalk007/SmartExcelAnalyzer-30.7/releases/download/v30.7.6/SmartExcelAnalyzer_30.7.6_PORTABLE.zip) · [SHA-256](https://github.com/Abdealmalk007/SmartExcelAnalyzer-30.7/releases/download/v30.7.6/SHA256SUMS.txt)

Copyright © 2026–2027 PRO TECH — All Rights Reserved. Third-party licenses remain applicable.
