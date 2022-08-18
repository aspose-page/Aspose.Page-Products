---
translation: true
template: /_templates/_conversion-cpp.md
title: PDL Dönüşüm API'si | C++
url: /cpp/conversion/
description: Aspose.Page PDL dönüştürme işlevine sahip C++ kitaplığını kullanarak PS, EPS ve XPS'yi PDF ve BMP, JPG, PNG ve TIFF dahil olmak üzere Görüntülere dönüştürün.
family: page
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: PS, EPS ve XPS'yi dönüştürün
h2: C++ için PS, EPS ve XPS dönüştürücü API Çözümü.
---

{{<section overview>}}
---
p1: "PostScript PS ve Encapsulated PostScript EPS Dosyalarının yanı sıra XPS belgelerini programlı olarak dönüştürmeye ihtiyaç duyulduğunda, Java API bunu sorunsuz bir şekilde yapabilir ve çoklu dosyaları dönüştürür. PS ve EPS için API, Düzey 1-3 PostScript operatörlerini ve EPS başlık yorumlarının çoğunu destekler ve ayrıca birkaç yazı tipi durumu ve Time New Roman gibi yazı tipleriyle API anlaşmaları dışında maksimum uyumluluğa sahip PostScript belgelerini dönüştürür."
p2: "Programcılar bunu PostScript ve XPS belgelerinin toplu işlenmesi için kolayca kullanabilir, hatta tuvalleri, yolları ve glif öğelerini değiştirebilir ve vektör grafik şekillerini ve metin dizelerini işleyebilir."
p3: "Buradaki Java için API çözümü, PS, EPS ve XPS gibi PDL biçimlerindeki dosyaları programlı olarak dönüştürmenize izin verir, ancak bu yerel API'ler üzerinde geliştirilmiş çapraz platformları görmek ve denemek faydalı olabilir. EPS'den Görüntülere, EPS'den PDF'ye, PostScript'ten PDF'ye, PostScript'ten Görüntülere, XPS'den Görüntülere ve XPS'den PDF'ye dönüştürme için birkaç senaryo"
---

{{<section feature1>}}
---
title: EPS'yi C++ ile Görüntülere dönüştürün.
h3: EPS'den Görüntülere Dönüştürme için C++ Kodu
item1: "C++ kitaplığı, Encapsulated PostScript (EPS) dosyalarının Windows ve Linux platformlarında görüntülere dönüştürülmesine izin verir. Süreç:"
item2: "EPS dosyası için giriş akışını oluşturmak ve ayrıca giriş akışına sahip [*PsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.ps_document) nesnesini oluşturmak için FileStream'i kullanın parametre olarak. Görüntülere özel ayarlar için [*ImageSaveOptions Class*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_save_options) kullanın."
item3: "[*ImageDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_device) kullanarak görüntü türünü ve boyutunu tanımlayın."
item4: EPS'yi, her bayt dizisi için yeni bir dosya çıktı akışı oluşturan bir dizi bayt dizisine görüntü kaydetme seçenekleriyle görüntüler olarak kaydedin.
---


{{<section feature2>}}
---
title: Java ile PostScript'ten PDF'ye Dönüştürme.
h3: PostScript'ten PDF'ye Dönüştürme için C++ Kodu
item1: "PostScript'i PDF'ye dönüştürme işlemi, EPS'den Görüntüler'e olanla aynıdır, ancak geliştiriciler, EkFontsFolder ve SuppressError değeri vb. gibi ek ayarları tanımlamak için [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_save_options)'ü kullanır. Ayrıca, oluşturulan çıktı akışından [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_device)'i kullanır."
---

{{<section feature3>}}
---
title: XPS'yi C++ ile PDF'ye dönüştürün.
h3: XPS'den PDF'ye Dönüştürme için C++ Kodu
item1: "C++ XPS Processing API, XPS'nin BMP, JPG, TIFF, PNG ve daha fazlasını içeren Görüntülere dönüştürülmesinin yanı sıra Windows ve Linux tabanlı sistemlerde XPS'den PDF'ye dönüştürülmesiyle ilgilenir. XPS'yi PDF'ye dönüştürme işlemi:"
item2: Giriş XPS belgesi için giriş akışını tanımlamanın yanı sıra çıkış akışını tanımlayın.
item3: "[*XpsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.xps_document) Nesnesine parametre olarak iletin."
item4: "[*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_save_options) kullanarak TextCompression, ImageCompression ve JpegQualityLevel gibi PDF'ye özel kaydetme seçeneklerini belirtin."
item5: "Daha önce oluşturulan çıktı akışından bir [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_device) örneği oluşturun."
item6: Son olarak, PDF kaydetme seçenekleriyle XPS belgesini PDF olarak dönüştürün.
---
