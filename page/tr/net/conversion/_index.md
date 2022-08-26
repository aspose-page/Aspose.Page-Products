---
translation: true
template: /_templates/_conversion-net.md
title: PDL Dönüşüm API'si C# | .NET
url: /net/conversion/
description: Aspose.Page PDL dönüştürme işleviyle .NET kitaplığını kullanarak PS, EPS ve XPS'yi PDF ve BMP, JPG, PNG ve TIFF dahil olmak üzere Görüntülere dönüştürün.
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: PS, EPS ve XPS'yi dönüştürün
h2: .NET için PS, EPS ve XPS dönüştürücü API Çözümü.
---

{{<section overview>}}
---
p1: "PostScript PS ve Encapsulated PostScript EPS Dosyalarının yanı sıra XPS belgelerinin programlı olarak dönüştürülmesi gerektiğinde, .NET API bunu sorunsuz bir şekilde yapabilir ve çoklu dosyaları dönüştürür. PS ve EPS için API, Düzey 1-3 PostScript operatörlerini ve EPS başlık yorumlarının çoğunu destekler ve ayrıca birkaç yazı tipi durumu ve Time New Roman gibi yazı tipleriyle API anlaşmaları dışında maksimum uyumluluğa sahip PostScript belgelerini dönüştürür."
p2: "Ayrıca, XPS dosyalarının dönüştürülmesi için API, sayfalar ekleyebilir veya kaldırabilir, tuvaller, yollar ve glif öğeleriyle ilgilenebilir, vektör grafik şekilleri, metin dizeleri oluşturabilir, XPS anahat öğelerini dönüştürebilir ve daha fazlasını yapabilir."
p3: "Buradaki .NET için API çözümü, PS, EPS ve XPS gibi PDL biçimlerindeki dosyaları programlı olarak dönüştürmenize izin verir, ancak bu yerel API'ler üzerinde geliştirilmiş çapraz platformları görmek ve denemek faydalı olabilir."
---

{{<section feature1>}}
---
title: C# .NET aracılığıyla PostScript'ten PDF'ye Dönüştürme.
h3: "PS EPS'den PDF'ye Dönüştürme için C# Kodu"
item1: "PostScript PS ve Encapsulated PostScript EPS dosyalarını .NET API aracılığıyla PDF'ye dönüştürmek için sonraki adımları uygulamanız gerekir:"
item2: "[*PsDocument Class*](https://reference.aspose.com/page/net/aspose.page.eps/psdocument/) kullanarak PS veya EPS dosyasını yükleyin."
item3: "[*PdfSaveOptions Class*](https://reference.aspose.com/page/net/aspose.page.eps.device/pdfsaveoptions/) kullanarak PDF kaydetmeyi ayarlayın."
item4: "Çıktı PDF dosyası için [*FileStream Class*](https://docs.microsoft.com/en-us/dotnet/api/system.io.filestream) kullanın."
item5: "[*PdfDevice Class*](https://reference.aspose.com/page/net/aspose.page.eps.device/pdfdevice/) çıktı PDF dosya akışı nesnesiyle başlatarak."
item6: "PDF dönüştürme için [*PsDocument.Save*](https://reference.aspose.com/page/net/aspose.page.eps/psdocument/save/) numaralı telefonu arayın."
---

{{<section feature2>}}
---
title: C# .NET aracılığıyla PostScript'ten Görüntülere Dönüştürme.
h3: "PostScript'ten Görüntülere Dönüştürme için C# Kodu"
item1: "Herhangi bir EPS/PS PostScript to görüntü dönüştürücü uygulaması için aşağıdaki C# kodu iyi çalışır, bu nedenle sonraki adımları uygulayın:"
item2: Parametre olarak girdi dosyası akışına sahip PsDocument sınıfını kullanarak belgeyi yükleyin.
item3: "[*ImageSaveOptions Class*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/imagesaveoptions/) nesnesini oluşturun ve gerekli ayarlarla başlatın."
item4: Her giriş dosyası sayfasını PNG, JPG, TIFF, BMP vb. bir resme kaydedin.
---

{{<section feature3>}}
---
title: XPS'yi C# .NET aracılığıyla JPG, PNG, BMP Görüntülerine dönüştürün.
h3: "XPS'den Görüntüye Dönüştürme için C# Kodu"
item1: ".NET API ayrıca BMP, JPG, PNG, TIFF vb. Görüntülere XPS Dönüştürmeyi destekler ve XPS işlemleri için XpsDocument Sınıfı sağlar. XPS'yi Görüntüye dönüştürmek için aşağıdaki adımları izleyin:"
item2: Akıştan XPS dosyasını yükleyin.
item3: "İlgili görüntü kaydetme seçeneklerini başlatın, örneğin **XPS'den JPG'ye** için bu [*JpegSaveOptions*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions/) ve **XPS'den PNG'ye** için [*PngSaveOptions*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions/). İşte tüm XPS'den Görüntüye [*kaydetme seçenekleri*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/) listesi."
item4: İşleme için SmoothingMode, Resolution ve PageNumbers vb. gibi ilgili ayarları tanımlayın. Son olarak, bunları görüntülere kaydetmek için belge bölümlerini yineleyin.
---
