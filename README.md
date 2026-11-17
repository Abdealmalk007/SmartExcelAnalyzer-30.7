# SmartExcelAnalyzer 30.7.11 — PRO TECH

برنامج Windows 10/11 x64 لتحليل Excel وإنشاء تقارير وDashboard تفاعلي.

**أحدث إصدار موصى بتنزيله:** `v30.7.11` — **Beta / Preview** (17 نوفمبر 2026). الإصدارات السابقة متاحة للأرشفة، ولم تُحذف.

## التنزيل المباشر

| النسخة | الاستخدام | رابط التحميل |
|---|---|---|
| Windows Setup | التثبيت المعتاد | [SmartExcelAnalyzer_30.7.11_Setup.exe](https://github.com/Abdealmalk007/SmartExcelAnalyzer-30.7/releases/download/v30.7.11/SmartExcelAnalyzer_30.7.11_Setup.exe) |
| Windows Portable | التشغيل دون تثبيت بعد فك ZIP | [SmartExcelAnalyzer_30.7.11_PORTABLE.zip](https://github.com/Abdealmalk007/SmartExcelAnalyzer-30.7/releases/download/v30.7.11/SmartExcelAnalyzer_30.7.11_PORTABLE.zip) |

[GitHub Release v30.7.11](https://github.com/Abdealmalk007/SmartExcelAnalyzer-30.7/releases/tag/v30.7.11) · [صفحة البرنامج العربية](https://alghad.digital/programs/smart-excel/) · [English page](https://alghad.digital/en/programs/smart-excel/)

## إصدار 30.7.11 — الواجهة المبسّطة

أُزيل زرا «مركز المؤسسة» و«منصة المؤسسة» القديمان من القائمة الجانبية، وبقي أسفلها «النسخ الاحتياطي» و«تسجيل الخروج» فقط. زر «عرض الكل» يعرض جميع الموظفين والفروع والألوان والفئات الأخرى في Dashboard تفصيلي، مع بحث وتصفح وتصدير CSV لكل النتائج. نجحت 40/40 حالة اختبار واجهة و34/34 حالة تدقيق حسابات مستقلة على بيانات مرجعية. لا يمكن ضمان دقة جميع ملفات Excel غير المعروفة 100%، لذا يجب مراجعة المجاميع المهمة. هذا إصدار Beta غير موقّع رقميًا.

### New in 30.7.11: All Categories & RTL Analytics

- **Arabic RTL workspace** with optional English, dynamic KPIs, charts and searchable results.
- **Search any Excel column**, then select any different column for Group By.
- **All showroom employees, all branches, all colors:** the full category list has searchable pagination (60 categories per page), not a Top-8 or Top-50 cap.
- A complete **UTF-8 CSV export** includes all groups and metrics, not just the visible page.
- Auto-detection of headers and compatible tables, including many blank rows or repeated heading rows; incompatible tables remain separately selectable.
- Automatic Count / Sum / Average / Min / Max on eligible metrics; identifiers and phone numbers are protected from arithmetic.
- Top-8 bar charts and Top-7 + Other donut charts are **visual summaries only**. All categories and counts are available below the charts.

**QA:** 32/32 engine, 40/40 GUI, 13/13 frozen EXE, 9/9 portable, 25/25 isolated-installer checks passed. Public Setup in-place upgrade remains untested, there is no Authenticode signature, and this release is Beta/Preview.


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
| `SmartExcelAnalyzer_30.7.11_Setup.exe` | 268173968 | `F9BC6DC6B7269FEE5AE17DE4A19C8688B47A50806C159DAC4632E953887902FC` |
| `SmartExcelAnalyzer_30.7.11_PORTABLE.zip` | 315370146 | `9CB86AB2DE193D0D7A459665B68DFBF7158CE74EBCACE87AC7E4007CD6A6B187` |

[ملف SHA256SUMS الرسمي](https://github.com/Abdealmalk007/SmartExcelAnalyzer-30.7/releases/download/v30.7.11/SHA256SUMS.txt) · [سجل اختبار التثبيت](https://github.com/Abdealmalk007/SmartExcelAnalyzer-30.7/releases/download/v30.7.11/INSTALLER_QA_RESULT.json)

**اختبارات موثقة:** 25/25 فحصًا ناجحًا لمثبّت QA معزول يحمل payload مطابقًا لحزمة التوزيع، و9/9 لنسخة Portable بعد استخراجها. لم نثبّت ملف Setup العام فوق نسخة المستخدم الحالية 30.7.5 حفاظًا على بياناتها. لا يعني ذلك ضمان التوافق مع كل ورقة Excel أو جهاز Windows.

## التثبيت والترخيص

- **المتطلبات:** Windows 10/11 x64. لا يلزم تثبيت Python.
- **Portable:** فك الضغط وشغّل `RUN_PORTABLE_WINDOWS.bat`.
- احفظ نسخة احتياطية من ملفاتك وإعداداتك وتقاريرك قبل الترقية.
- الملفات **غير موقّعة رقميًا عبر Authenticode**؛ قد تظهر رسالة Windows SmartScreen. تحقق من المصدر الرسمي والبصمة قبل التشغيل، ولا تعطّل الحماية.
- الإصدار Beta / Preview؛ تنصح PRO TECH بالتجربة في بيئة غير إنتاجية أولًا.
- المستودع يعرض حزم التوزيع والوثائق، وليس مصدر التطبيق الخاص.

© 2026–2027 PRO TECH. **All Rights Reserved**. تراخيص المكونات الخارجية والإصدارات المرخصة سابقًا تظل سارية.
