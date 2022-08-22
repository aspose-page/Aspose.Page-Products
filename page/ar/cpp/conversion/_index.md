---
translation: true
template: /_templates/_conversion-cpp.md
title: واجهة برمجة تطبيقات تحويل PDL | C++
url: /cpp/conversion/
description: قم بتحويل PS و EPS و XPS إلى PDF والصور بما في ذلك BMP و JPG و PNG و TIFF باستخدام مكتبة C++ مع وظيفة تحويل Aspose.Page PDL.
family: page
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: تحويل PS و EPS و XPS
h2: PS و EPS و XPS Converter API حل لـ C++.
---

{{<section overview>}}
---
p1: "كلما دعت الحاجة إلى تحويل ملفات PostScript PS و Encapsulated PostScript EPS بالإضافة إلى مستندات XPS برمجيًا ، يمكن لـ Java API القيام بذلك بسلاسة وتحويل ملفات مضاعفة. بالنسبة إلى PS و EPS ، تدعم API عوامل تشغيل Levels 1-3 PostScript ومعظم تعليقات رأس EPS بالإضافة إلى تحويل مستندات PostScript ذات المطابقة القصوى باستثناء بعض حالات الخطوط وصفقات API مثل الخطوط مثل Time New Roman."
p2: "يمكن للمبرمجين استخدامه بسهولة للمعالجة المجمعة لوثائق PostScript و XPS ، وحتى معالجة عناصر اللوحات والمسارات والحروف الرسومية والتعامل مع أشكال الرسومات المتجهة وسلاسل النص."
p3: "يتيح لك حل API لـ Java هنا تحويل ملفات تنسيقات PDL مثل PS و EPS و XPS برمجيًا ، ولكن قد تجد أنه من المفيد مشاهدة ومحاولة تطوير الأنظمة الأساسية عبر واجهات برمجة التطبيقات الأصلية هذه. فيما يلي بعض سيناريوهات التحويل مثل EPS إلى صور و EPS إلى PDF و PostScript إلى PDF و PostScript to Images و XPS إلى صور و XPS إلى PDF"
---

{{<section feature1>}}
---
title: تحويل EPS إلى صور عبر C++.
h3: كود C++ لتحويل EPS إلى صور
item1: "تتيح مكتبة C++ تحويل ملفات Encapsulated PostScript (EPS) إلى صور على أنظمة Windows و Linux. العملية هي:"
item2: "استخدم FileStream لإنشاء دفق الإدخال لملف EPS وكذلك لإنشاء كائن [*PsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.ps_document) به دفق إدخال كمعامل. بالنسبة إلى الإعدادات الخاصة بالصور ، استخدم [*ImageSaveOptions Class*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_save_options)."
item3: "حدد نوع الصورة وحجمها باستخدام [*ImageDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_device)."
item4: احفظ EPS كصور مع خيارات حفظ الصورة في مصفوفة من مصفوفات البايت مما يؤدي إلى إنشاء دفق إخراج ملف جديد لكل صفيف بايت.
---


{{<section feature2>}}
---
title: PostScript لتحويل PDF عبر Java.
h3: كود C++ لتحويل PostScript إلى PDF
item1: "عملية تحويل PostScript إلى PDF هي نفس عملية تحويل EPS إلى صور ، باستثناء أن المطورين سيستخدمون [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_save_options) لتعريف إعدادات إضافية مثل قيم ExtraFontsFolder و SuppressError وما إلى ذلك ، علاوة على ذلك ، ستستخدم [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_device) من دفق الإخراج الذي تم إنشاؤه."
---

{{<section feature3>}}
---
title: قم بتحويل XPS إلى PDF عبر C++.
h3: كود C++ لتحويل XPS إلى PDF
item1: "تتعامل واجهة برمجة تطبيقات معالجة XPS C++ مع تحويل XPS إلى صور بما في ذلك BMP و JPG و TIFF و PNG والمزيد ، بالإضافة إلى تحويل XPS إلى PDF على الأنظمة المستندة إلى Windows و Linux. عملية تحويل XPS إلى PDF هي:"
item2: تحديد دفق الإخراج وكذلك تحديد دفق الإدخال لمستند XPS للإدخال.
item3: "مرره كمعامل إلى كائن [*XpsDocument*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.xps_document)."
item4: "حدد خيارات الحفظ الخاصة بـ PDF مثل TextCompression و ImageCompression و JpegQualityLevel باستخدام [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_save_options)."
item5: "قم بإنشاء مثيل لـ [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_device) من تدفق الإخراج الذي تم إنشاؤه مسبقًا."
item6: أخيرًا ، قم بتحويل مستند XPS إلى ملف PDF باستخدام خيارات حفظ PDF.
---
