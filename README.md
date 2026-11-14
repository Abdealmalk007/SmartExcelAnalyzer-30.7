# SmartExcelAnalyzer 30.7.3 — PRO TECH

**برنامج لتحليل ملفات Excel وإعداد التقارير على Windows 10/11 x64.**

**الإصدار الحالي:** `v30.7.3` — **Beta / Preview** (14 نوفمبر 2026). يتضمن الإصدار الجديد إصلاحات للتشغيل والتصدير، وتوحيد الهوية البصرية والأيقونة الجديدة.

## التنزيل المباشر

| النسخة | الاستخدام | التحميل |
|---|---|---|
| Windows Setup | تثبيت البرنامج بالطريقة المعتادة | [SmartExcelAnalyzer_30.7.3_Setup.exe](https://github.com/Abdealmalk007/SmartExcelAnalyzer-30.7/releases/download/v30.7.3/SmartExcelAnalyzer_30.7.3_Setup.exe) |
| Windows Portable | التشغيل من مجلد دون تثبيت | [SmartExcelAnalyzer_30.7.3_BrandFixed_PORTABLE.zip](https://github.com/Abdealmalk007/SmartExcelAnalyzer-30.7/releases/download/v30.7.3/SmartExcelAnalyzer_30.7.3_BrandFixed_PORTABLE.zip) |

[صفحة الإصدار وملفات التحقق](https://github.com/Abdealmalk007/SmartExcelAnalyzer-30.7/releases/tag/v30.7.3) · [صفحة البرنامج على موقع الغد الرقمي](https://alghad.digital/programs/smart-excel/) · [English description](https://alghad.digital/en/programs/smart-excel/)

## أبرز التحسينات في 30.7.3

- دعم اختبارات القراءة لصيغ `XLSX` و`XLS` و`XLSB` و`XLSM` و`ODS`، إضافة إلى مسارات `CSV`.
- إصلاح تعطل `UnicodeEncodeError` عند تصدير التقارير عبر Windows مع النصوص العربية ورموز Emoji.
- تحسينات على فحص البيانات، وتقارير `PDF` و`Excel`، واختبارات سلامة المخرجات.
- توحيد شعار **PRO TECH** الجديد المخصص لتحليل الجداول وإزالة أصول الشعار القديم من نسخة التوزيع الحالية.
- حزمة مستقلة لا تتطلب تثبيت Python على جهاز المستخدم، مع خيار Portable منفصل.

## التحقق من الإصدار

تم اختبار المثبّت النهائي بحزمة قبول شملت **21/21** فحصًا ناجحًا: التثبيت النظيف، تشغيل واجهة Tk، تحليل Excel، إنشاء ملفات JSON وPDF وXLSX، إزالة البرنامج مع بقاء بيانات اختبارية، والتحقق من أصول الشعار الجديد. كما تم تنزيل ملفي التثبيت وPortable كاملين من GitHub ومطابقة SHA-256 مع الملفات الأصلية.

| الملف | الحجم بالبايت | SHA-256 |
|---|---:|---|
| `SmartExcelAnalyzer_30.7.3_Setup.exe` | 268083614 | `631D153AEEC70E6602B5AA4848BEFA057F41FFBF265B9F04A258CDE1D6FABA3B` |
| `SmartExcelAnalyzer_30.7.3_BrandFixed_PORTABLE.zip` | 315247973 | `D40088B561E7A95EE7F77ACD7BCCAA9D1E29005E8DA30796433FBF8DDCD10CAB` |

يمكن مراجعة [ملف SHA256SUMS](https://github.com/Abdealmalk007/SmartExcelAnalyzer-30.7/releases/download/v30.7.3/SHA256SUMS.txt) و[تقرير ضمان الجودة بالعربية](https://github.com/Abdealmalk007/SmartExcelAnalyzer-30.7/releases/download/v30.7.3/QA_FINAL_RELEASE_REPORT_AR.md) و[سجل فحص المثبّت](https://github.com/Abdealmalk007/SmartExcelAnalyzer-30.7/releases/download/v30.7.3/INSTALLER_QA_RESULT.json).

## متطلبات وملاحظات

- **النظام:** Windows 10/11 بنواة x64.
- **Portable:** فك الضغط في مجلد قابل للكتابة، ثم تشغيل `RUN_PORTABLE_WINDOWS.bat`.
- يوصى بنسخ الملفات والإعدادات والتقارير المهمة احتياطيًا قبل ترقية نسخة سابقة.
- **التوقيع الرقمي:** لا تتضمن هذه الحزم توقيع `Authenticode` معتمدًا؛ قد يظهر تحذير Windows SmartScreen. تحقّق من عنوان GitHub الرسمي وبصمة SHA-256 قبل التثبيت.
- الإصدار **تجريبي**؛ نجاح اختبارات محددة لا يضمن توافق جميع ملفات Excel غير القياسية أو جميع أجهزة Windows.
- يضم المستودع الوثائق والأيقونات وملفات التوزيع، ولا ينشر الشيفرة المصدرية للتطبيق.

## حقوق الملكية

Copyright © 2026–2027 **PRO TECH**. **All Rights Reserved.**

المطور: عبدالملك علي حمزة. لا يلغي هذا الإعلان الحقوق أو التراخيص الممنوحة سابقًا لنسخ سابقة أو للمكونات الخارجية المستقلة.
