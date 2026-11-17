# SmartExcelAnalyzer v30.7.11 — Clean Sidebar & Verified Analytics (Beta / Preview)

**PRO TECH | Windows 10/11 x64 | 17 November 2026**

## What changed

- Removed the two obsolete right-side shortcuts **مركز المؤسسة (Enterprise Center)** and **منصة المؤسسة (Enterprise Platform)**. Their internal modules remain intact.
- Sidebar footer now provides only **النسخ الاحتياطي (Backup & Restore)** and **تسجيل الخروج (Log out)**; repeated Exit action is hidden and remains available in Settings.
- Retained the approved compact Arabic RTL workspace (optional English), the visible **عرض الكل / View All** button, and the larger dashboard area.
- Search any column, group by any other column, and explore **every employee, every branch, every color** in a paginated/searchable category browser with complete UTF-8 CSV export.
- Main Top-8 bar/donut charts are **summaries**. No category is discarded from the complete category browser, results grid, or export.
- Compatible Excel tables can be combined without modifying the source. Incompatible table schemas remain independently selectable.

## Quality evidence

- **40/40 GUI tests passed:** exact two-button footer; both obsolete shortcuts hidden; sidebar and RTL; complete category browser, filter, group selection, page navigation, and bilingual switching.
- **34/34 independent accuracy checks passed:** an independent oracle computed counts, sums, averages, minimums, maximums, filtered-row totals, and timeline results for 1,500 synthetic rows, with 75 employees, 120 branches, and 250 colors. No tested categories or source rows were lost; phone and contract IDs were excluded from arithmetic.
- Frozen executable, Portable ZIP and isolated installer checks are included as separate reports in the release evidence when available.

## Important scope and limitations

This is **Beta / Preview** for evaluation. Passing representative tests does **not** establish guaranteed 100% accuracy for every arbitrarily structured, encrypted, corrupted, macro-driven or atypical Excel file. Users should inspect report structure and reconcile critical totals before operational decisions.

The executable is **not signed with an Authenticode certificate**, so Windows SmartScreen may warn. The *public* Setup installer has not been installed over the user's existing installation. QA uses an isolated installer with a different AppId to avoid overwriting user data.

Keep a backup of your Excel documents and app data before any installation. Older GitHub releases are retained.

## Downloads

- [Windows Setup v30.7.11](https://github.com/Abdealmalk007/SmartExcelAnalyzer-30.7/releases/download/v30.7.11/SmartExcelAnalyzer_30.7.11_Setup.exe)
- [Windows Portable v30.7.11](https://github.com/Abdealmalk007/SmartExcelAnalyzer-30.7/releases/download/v30.7.11/SmartExcelAnalyzer_30.7.11_PORTABLE.zip)
- [SHA-256 checksum file](https://github.com/Abdealmalk007/SmartExcelAnalyzer-30.7/releases/download/v30.7.11/SHA256SUMS.txt)

© 2026–2027 PRO TECH. **All Rights Reserved**. Third-party notices and licenses continue to apply.
