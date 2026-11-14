# SmartExcelAnalyzer 30.7.3 — Release Notes

**Release:** 14 November 2026 · **Channel:** Beta / Preview · **Windows:** 10/11 x64.

## Changes

- Unified PRO TECH branding and replaced former logo assets with the approved spreadsheet analytics icon in the app, installer, and report assets.
- Corrected Windows `UnicodeEncodeError` when printing Arabic text and emoji from the frozen executable.
- Verified import of XLSX, XLS, XLSB, XLSM, and ODS fixtures, along with selected CSV workflows.
- Validated Excel and PDF report generation, application startup, audit/performance commands, and clean installation/uninstallation.
- Added separate Setup and Portable downloads with published SHA-256 checksums.

## Verified artifacts

- [Setup.exe — 268,083,614 bytes](https://github.com/Abdealmalk007/SmartExcelAnalyzer-30.7/releases/download/v30.7.3/SmartExcelAnalyzer_30.7.3_Setup.exe)
- [Portable ZIP — 315,247,973 bytes](https://github.com/Abdealmalk007/SmartExcelAnalyzer-30.7/releases/download/v30.7.3/SmartExcelAnalyzer_30.7.3_BrandFixed_PORTABLE.zip)
- [SHA256SUMS](https://github.com/Abdealmalk007/SmartExcelAnalyzer-30.7/releases/download/v30.7.3/SHA256SUMS.txt)
- [QA report (Arabic)](https://github.com/Abdealmalk007/SmartExcelAnalyzer-30.7/releases/download/v30.7.3/QA_FINAL_RELEASE_REPORT_AR.md)

The final compact installer passed **21/21** acceptance checks. The public Setup and Portable downloads were retrieved fully and their SHA-256 values matched the local builds.

## Limitations

The application remains a **Beta / Preview** release. Successful acceptance tests do not guarantee compatibility with all Windows devices or unusual Excel files. The executables are **unsigned (no Authenticode certificate)**, so SmartScreen prompts may occur. Back up your data before upgrading.

Copyright © 2026–2027 PRO TECH. **All Rights Reserved.** Third-party components retain their respective licenses.
