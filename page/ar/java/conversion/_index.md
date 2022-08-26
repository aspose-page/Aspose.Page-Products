---
translation: true
template: /_templates/_conversion-java.md
title: واجهة برمجة تطبيقات تحويل PDL | Java
url: /java/conversion/
description: قم بتحويل PS و EPS و XPS إلى PDF والصور بما في ذلك BMP و JPG و PNG و TIFF باستخدام مكتبة Java مع وظيفة تحويل Aspose.Page PDL.
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: تحويل PS و EPS و XPS
h2: PS و EPS و XPS Converter API حل لJava
---

{{<section overview>}}
---
p1: "كلما دعت الحاجة إلى تحويل ملفات PostScript PS و Encapsulated PostScript EPS بالإضافة إلى مستندات XPS برمجيًا ، يمكن لـ Java API القيام بذلك بسلاسة وتحويل ملفات متعددة. بالنسبة إلى PS و EPS ، تدعم API عوامل تشغيل Levels 1-3 PostScript ومعظم تعليقات رأس EPS بالإضافة إلى تحويل مستندات PostScript ذات المطابقة القصوى باستثناء بعض حالات الخطوط وصفقات API مثل الخطوط مثل Time New Roman."
p2: "علاوة على ذلك ، بالنسبة لتحويل ملفات XPS ، يمكن لواجهة برمجة التطبيقات إضافة أو إزالة الصفحات ، والتعامل مع اللوحات ، والمسارات وعناصر الحروف الرسومية ، وإنشاء أشكال رسومات متجهة ، وسلاسل نصية ، وتحويل عناصر مخطط XPS والمزيد."
p3: "يتيح لك حل API لـ Java هنا تحويل ملفات تنسيقات PDL مثل PS و EPS و XPS برمجيًا ، ولكن قد تجد أنه من المفيد مشاهدة ومحاولة تطوير الأنظمة الأساسية عبر واجهات برمجة التطبيقات الأصلية هذه."
---

{{<section feature1>}}
---
title: PostScript لتحويل PDF عبر Java.
h3: "Java Code لتحويل PS EPS إلى PDF"
item1: "لتحويل ملفات PostScript PS و Encapsulated PostScript EPS إلى PDF عبر Java API ، يلزمك اتخاذ الخطوات التالية:"
item2: "قم بتحميل ملف PS أو EPS باستخدام [*PsDocument Class*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument)."
item3: "قم بتعيين خيارات حفظ PDF باستخدام [*PdfSaveOptions Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfSaveOptions)."
item4: "استخدم [*FileStream Class*](https://docs.oracle.com/javase/7/docs/api/java/io/FileOutputStream.html) لملف PDF الناتج."
item5: "استخدم [*PdfDevice Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfDevice) مع وجود كائن FileOutputStream كمعلمة."
item6: "اتصل بـ [*PsDocument.Save*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) لحفظ الملف في ملف PDF."
---

{{<section feature2>}}
---
title: بوستسكريبت لتحويل الصور عبر Java.
h3: "كود Java لتحويل بوستسكريبت إلى صور"
item1: "لأي تطبيق EPS / PS PostScript لتحويل الصور ، تعمل تعليمات Java البرمجية التالية بشكل جيد ، لذا اتبع الخطوات التالية:"
item2: تهيئة دفق الإدخال باستخدام ملف مصدر PS.
item3: "قم بإنشاء كائن [*PsDocument*](https://reference.aspose.com/page/java/com.aspose.eps/psdocument) باستخدام دفق إدخال PS الذي تم إنشاؤه كمعامل"
item4: "استخدم [*ImageSaveOptions*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagesaveoptions) لتحديد AdditionalFontsFolder و SuppressError وما إلى ذلك."
item5: "استخدم كائن [*ImageDevice*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagedevice) لتحديد نوع الصورة وحجمها إذا لزم الأمر."
item6: احفظ ملف PS / EPS بصيغة وصورة مع خيارات حفظ الصورة كمصفوفة من مصفوفات البايت. صفيف واحد من البايت لصفحة واحدة من ملف الإدخال.
---


{{<section feature3>}}
---
title: قم بتحويل XPS إلى صور JPG و PNG و BMP عبر Java.
h3: كود Java لـ XPS لتحويل الصورة
item1: "تتعامل Java API مع تنسيق XPS المستخدم لتمثيل تخطيط الصفحة. في أي سيناريو ، كلما دعت الحاجة إلى تحويل XPS إلى صور BMP و JPG و PNG و TIFF برمجيًا ، يمكن دمج الكود التالي بسهولة في تطبيق Java."
item2: "استخدم [*XpsDocument class*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument) لتحميل مستند XPS."
item3: "استخدم فئة خيار الصورة ذات الصلة مثل [*PngSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PngSaveOptions) ، [*JpegSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/JpegSaveOptions) ، [*BmpSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/BmpSaveOptions) ، [*TiffSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/TiffSaveOptions) لإعدادات إضافية للصورة."
item4: "أنشئ نسخة فئة [*image device*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/ImageDevice)."
item5: "اتصل بـ [*XpsDocument.save*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) لحفظ صورة JPEG المحولة في كائن ImageDevice ثم استخدم ImageDevice لحفظ الصورة بتنسيق JPG."
---

{{<section feature4>}}
---
title: قم بتحويل XPS إلى PDF عبر Java.
h3: كود Java لتحويل XPS إلى PDF
item1: عملية تحويل XPS إلى مستندات PDF برمجيًا بسيطة ولها نتائج عالية الدقة بين ملفات الإدخال والإخراج.
item2: "قم بتحميل الملف باستخدام فئة XpsDocument. تهيئة كائن [*PdfSaveOptions class*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PdfDevice)."
item3: قم بإنشاء كائن PdfDevice للعرض وحفظ مستند PDF الناتج أخيرًا.
---


