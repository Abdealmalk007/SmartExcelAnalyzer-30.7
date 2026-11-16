# SmartExcelAnalyzer 30.7.9 — PRO TECH

برنامج Windows 10/11 x64 لتحليل Excel وإنشاء تقارير وDashboard تفاعلي.

**أحدث إصدار موصى بتنزيله:** `v30.7.9` — **Beta / Preview** (15 نوفمبر 2026). الإصدارات السابقة متاحة للأرشفة، ولم تُحذف.

## التنزيل المباشر

| النسخة | الاستخدام | رابط التحميل |
|---|---|---|
| Windows Setup | التثبيت المعتاد | [SmartExcelAnalyzer_30.7.9_Setup.exe](https://github.com/Abdealmalk007/SmartExcelAnalyzer-30.7/releases/download/v30.7.9/SmartExcelAnalyzer_30.7.9_Setup.exe) |
| Windows Portable | التشغيل دون تثبيت بعد فك ZIP | [SmartExcelAnalyzer_30.7.9_PORTABLE.zip](https://github.com/Abdealmalk007/SmartExcelAnalyzer-30.7/releases/download/v30.7.9/SmartExcelAnalyzer_30.7.9_PORTABLE.zip) |

[GitHub Release v30.7.9](https://github.com/Abdealmalk007/SmartExcelAnalyzer-30.7/releases/tag/v30.7.9) · [صفحة البرنامج العربية](https://alghad.digital/programs/smart-excel/) · [English page](https://alghad.digital/en/programs/smart-excel/)

### New in 30.7.9: All Categories & RTL Analytics

- **Arabic RTL workspace** with optional English, dynamic KPIs, charts and searchable results.
- **Search any Excel column**, then select any different column for Group By.
- **All showroom employees, all branches, all colors:** the full category list has searchable pagination (60 categories per page), not a Top-8 or Top-50 cap.
- A complete **UTF-8 CSV export** includes all groups and metrics, not just the visible page.
- Auto-detection of headers and compatible tables, including many blank rows or repeated heading rows; incompatible tables remain separately selectable.
- Automatic Count / Sum / Average / Min / Max on eligible metrics; identifiers and phone numbers are protected from arithmetic.
- Top-8 bar charts and Top-7 + Other donut charts are **visual summaries only**. All categories and counts are available below the charts.

**QA:** 32/32 engine, 29/29 GUI, 13/13 frozen EXE, 9/9 portable, 25/25 isolated-installer checks passed. Public Setup in-place upgrade remains untested, there is no Authenticode signature, and this release is Beta/Preview.


## التحسينات الرئيسية

- إصلاح شاشة اتفاقية الاستخدام العربية وجعل زر الموافقة مرئيًا على الشاشات الصغيرة.
- إصلاح تشغيل التطبيق بعد الموافقة، وتضمين مكتبات `customtkinter` و`Tcl/Tk` في نسخة Windows المجمّعة.
- تحليل ملف Excel تلقائيًا عند فتحه، مع لوحة مؤشرات KPI ورسوم bar/donut/line وفلاتر تفاعلية.
- فصل المجاميع المالية عن الأمتار والكميات، وعدم احتساب أرقام الهواتف والعقود كمبالغ.
- دعم صيغ `XLS` و`XLSX` و`XLSM` و`XLSB` و`CSV` ضمن الحالات المختبرة.
- تصدير `PDF` و`Excel` و`JSON` مع تقارير وعناوين مناسبة.

## إثبات سلامة الملفات

| اسم الملف | الحجم (بايت) | SHA-256 |
|---|---:|---|
| `SmartExcelAnalyzer_30.7.9_Setup.exe` | 268167389 | `954D49C12F49BDF12EB2BFB5CC09B0F110B03A29FDD5A3ACC2F9B38FCD64C9B6` |
| `SmartExcelAnalyzer_30.7.9_PORTABLE.zip` | 315339583 | `E1C7CE0856500EFDBEBCC6F874EFE2E9D11BE2D994A6F5F22F05C368F76884EA` |

[ملف SHA256SUMS الرسمي](https://github.com/Abdealmalk007/SmartExcelAnalyzer-30.7/releases/download/v30.7.9/SHA256SUMS.txt) · [سجل اختبار التثبيت](https://github.com/Abdealmalk007/SmartExcelAnalyzer-30.7/releases/download/v30.7.9/INSTALLER_QA_RESULT.json)

**اختبارات موثقة:** 25/25 فحصًا ناجحًا لمثبّت QA معزول يحمل payload مطابقًا لحزمة التوزيع، و9/9 لنسخة Portable بعد استخراجها. لم نثبّت ملف Setup العام فوق نسخة المستخدم الحالية 30.7.5 حفاظًا على بياناتها. لا يعني ذلك ضمان التوافق مع كل ورقة Excel أو جهاز Windows.

## التثبيت والترخيص

- **المتطلبات:** Windows 10/11 x64. لا يلزم تثبيت Python.
- **Portable:** فك الضغط وشغّل `RUN_PORTABLE_WINDOWS.bat`.
- احفظ نسخة احتياطية من ملفاتك وإعداداتك وتقاريرك قبل الترقية.
- الملفات **غير موقّعة رقميًا عبر Authenticode**؛ قد تظهر رسالة Windows SmartScreen. تحقق من المصدر الرسمي والبصمة قبل التشغيل، ولا تعطّل الحماية.
- الإصدار Beta / Preview؛ تنصح PRO TECH بالتجربة في بيئة غير إنتاجية أولًا.
- المستودع يعرض حزم التوزيع والوثائق، وليس مصدر التطبيق الخاص.

© 2026–2027 PRO TECH. **All Rights Reserved**. تراخيص المكونات الخارجية والإصدارات المرخصة سابقًا تظل سارية.
