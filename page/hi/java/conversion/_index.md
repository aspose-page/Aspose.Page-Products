---
translation: true
template: /_templates/_conversion-java.md
title: पीडीएल रूपांतरण एपीआई | Java
url: /java/conversion/
description: Aspose.Page PDL रूपांतरण कार्यक्षमता के साथ जावा लाइब्रेरी का उपयोग करके PS, EPS, और XPS को PDF और छवियों में BMP, JPG, PNG और TIFF सहित कनवर्ट करें।
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: पीएस, ईपीएस और एक्सपीएस कन्वर्ट करें
h2: जावा के लिए पीएस, ईपीएस और एक्सपीएस कनवर्टर एपीआई समाधान
---

{{<section overview>}}
---
p1: "जब भी पोस्टस्क्रिप्ट पीएस और एनकैप्सुलेटेड पोस्टस्क्रिप्ट ईपीएस फाइलों के साथ-साथ एक्सपीएस दस्तावेजों को प्रोग्रामेटिक रूप से परिवर्तित करने की आवश्यकता होती है, जावा एपीआई इसे आसानी से कर सकता है और कई फाइलों को परिवर्तित कर सकता है। पीएस और ईपीएस के लिए, एपीआई स्तर 1-3 पोस्टस्क्रिप्ट ऑपरेटरों का समर्थन करता है और अधिकांश ईपीएस हेडर टिप्पणियों के साथ-साथ कुछ फोंट मामलों के अपवाद के साथ अधिकतम अनुरूपता वाले पोस्टस्क्रिप्ट दस्तावेजों को बदल देता है और एपीआई टाइम न्यू रोमन जैसे फोंट से संबंधित है।"
p2: "इसके अलावा, एक्सपीएस फाइलों के परिवर्तन के लिए, एपीआई पृष्ठों को जोड़ या हटा सकता है, कैनवस, पथ और ग्लिफ़ तत्वों से संबंधित है, वेक्टर ग्राफिक्स आकार, टेक्स्ट स्ट्रिंग्स बना सकता है, एक्सपीएस रूपरेखा वस्तुओं को परिवर्तित कर सकता है और बहुत कुछ कर सकता है।"
p3: "यहां जावा के लिए एपीआई समाधान आपको पीएस, ईपीएस और एक्सपीएस जैसे पीडीएल प्रारूपों की फाइलों को प्रोग्रामेटिक रूप से परिवर्तित करने देता है, लेकिन आपको इन देशी एपीआई पर विकसित क्रॉस-प्लेटफ़ॉर्म को देखने और आज़माने के लिए उपयोगी लग सकता है।"
---

{{<section feature1>}}
---
title: जावा के माध्यम से पीडीएफ रूपांतरण के लिए पोस्टस्क्रिप्ट।
h3: "पीएस ईपीएस को पीडीएफ में बदलने के लिए जावा कोड"
item1: "जावा एपीआई के माध्यम से पोस्टस्क्रिप्ट पीएस और एनकैप्सुलेटेड पोस्टस्क्रिप्ट ईपीएस फाइलों को पीडीएफ में बदलने के लिए आपको अगले कदम उठाने होंगे:"
item2: "[PsDocument Class*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument) का उपयोग करके PS या EPS फ़ाइल लोड करें।"
item3: "[*PdfSaveOptions Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfSaveOptions) का उपयोग करके PDF बचत विकल्प सेट करें।"
item4: "पीडीएफ फाइल को आउटपुट करने के लिए [*फाइलस्ट्रीम क्लास*](https://docs.oracle.com/javase/7/docs/api/java/io/FileOutputStream.html) का इस्तेमाल करें।"
item5: "पैरामीटर के रूप में FileOutputStream ऑब्जेक्ट वाले [*PdfDevice Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfDevice) का उपयोग करें।"
item6: "[*PsDocument.Save*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-परकॉलकरें।) पीडीएफ फाइल में सेव करने के लिए।"
---

{{<section feature2>}}
---
title: जावा के माध्यम से छवियों के रूपांतरण के लिए पोस्टस्क्रिप्ट।
h3: "पोस्टस्क्रिप्ट से छवियों के रूपांतरण के लिए जावा कोड"
item1: "किसी भी ईपीएस/पीएस पोस्टस्क्रिप्ट टू इमेज कन्वर्टर एप्लिकेशन के लिए, निम्नलिखित जावा कोड अच्छी तरह से काम करता है, इसलिए अगले कदम उठाएं:"
item2: पीएस स्रोत फ़ाइल के साथ इनपुट स्ट्रीम प्रारंभ करें।
item3: "एक पैरामीटर के रूप में बनाए गए PS इनपुट स्ट्रीम के साथ [*PsDocument*](https://reference.aspose.com/page/java/com.aspose.eps/psdocument) ऑब्जेक्ट बनाएं"
item4: "[ImageSaveOptions*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagesaveoptions) का इस्तेमाल करके ExtraFontsFolder और SuppressError आदि निर्दिष्ट करें।"
item5: "यदि आवश्यक हो तो छवि प्रकार और आकार निर्दिष्ट करने के लिए [*ImageDevice*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagedevice) ऑब्जेक्ट का उपयोग करें।"
item6: PS/EPS फ़ाइल को इस रूप में सहेजें और छवि के साथ छवि सहेजें विकल्प बाइट्स की सरणी की एक सरणी के रूप में। इनपुट फ़ाइल के एक पृष्ठ के लिए बाइट्स की एक सरणी।
---


{{<section feature3>}}
---
title: जावा के माध्यम से XPS को छवियाँ JPG, PNG, BMP में बदलें।
h3: छवि रूपांतरण के लिए एक्सपीएस के लिए जावा कोड
item1: "जावा एपीआई एक्सपीएस प्रारूप से संबंधित है जिसका उपयोग पेज लेआउट का प्रतिनिधित्व करने के लिए किया जाता है। किसी भी परिदृश्य में, जब भी एक्सपीएस को बीएमपी, जेपीजी, पीएनजी, और टीआईएफएफ प्रोग्रामेटिक रूप से छवियों में बदलने की आवश्यकता होती है, तो निम्न कोड आसानी से जावा एप्लिकेशन के भीतर एकीकृत किया जा सकता है।"
item2: "XPS दस्तावेज़ लोड करने के लिए [*XpsDocument class*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument) का उपयोग करें।"
item3: "प्रासंगिक छवि विकल्प वर्ग का उपयोग करें जैसे कि [*PngSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PngSaveOptions), [*JpegSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/JpegSaveOptions), [*BmpSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/BmpSaveOptions) , [*TiffSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/TiffSaveOptions) छवि अतिरिक्त सेटिंग्स के लिए।"
item4: "[*इमेज डिवाइस*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/ImageDevice) क्लास इंस्टेंस बनाएं।"
item5: "[*XpsDocument.save*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-परकॉलकरें।) परिवर्तित JPEG छवि को ImageDevice ऑब्जेक्ट में सहेजने के लिए और फिर छवि को JPG के रूप में सहेजने के लिए ImageDevice का उपयोग करें।"
---

{{<section feature4>}}
---
title: जावा के माध्यम से एक्सपीएस को पीडीएफ में बदलें।
h3: एक्सपीएस से पीडीएफ रूपांतरण के लिए जावा कोड
item1: XPS को PDF दस्तावेज़ों में प्रोग्रामेटिक रूप से परिवर्तित करने की प्रक्रिया सरल है, जिसमें इनपुट और आउटपुट फ़ाइलों के बीच उच्च निष्ठा परिणाम होते हैं।
item2: "XpsDocument वर्ग का उपयोग करके फ़ाइल लोड करें। इनिशियलाइज़ [*PdfSaveOptions class*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PdfDevice) ऑब्जेक्ट।"
item3: रेंडरिंग के लिए PdfDevice ऑब्जेक्ट बनाएं और अंत में आउटपुट PDF डॉक्यूमेंट को सेव करें।
---


