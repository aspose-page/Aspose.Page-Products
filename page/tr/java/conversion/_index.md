---
translation: true
template: /_templates/_conversion-java.md
title: PDL Dönüşüm API'si | Java
url: /java/conversion/
description: Aspose.Page PDL dönüştürme işleviyle Java kitaplığını kullanarak PS, EPS ve XPS'yi PDF'ye ve BMP, JPG, PNG ve TIFF dahil Görüntülere dönüştürün.
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: PS, EPS ve XPS'yi dönüştürün
h2: Java için PS, EPS ve XPS dönüştürücü API Çözümü
---

{{<section overview>}}
---
p1: "PostScript PS ve Encapsulated PostScript EPS Dosyalarının yanı sıra XPS belgelerini programlı olarak dönüştürmeye ihtiyaç duyulduğunda, Java API bunu sorunsuz bir şekilde yapabilir ve çoklu dosyaları dönüştürür. PS ve EPS için API, Düzey 1-3 PostScript operatörlerini ve EPS başlık yorumlarının çoğunu destekler ve ayrıca birkaç yazı tipi durumu ve Time New Roman gibi yazı tipleriyle API anlaşmaları dışında maksimum uyumluluğa sahip PostScript belgelerini dönüştürür."
p2: "Ayrıca, XPS dosyalarının dönüştürülmesi için API, sayfalar ekleyebilir veya kaldırabilir, tuvaller, yollar ve glif öğeleriyle ilgilenebilir, vektör grafik şekilleri, metin dizeleri oluşturabilir, XPS anahat öğelerini dönüştürebilir ve daha fazlasını yapabilir."
p3: "Buradaki Java için API çözümü, PS, EPS ve XPS gibi PDL biçimlerindeki dosyaları programlı olarak dönüştürmenize izin verir, ancak bu yerel API'ler üzerinde geliştirilmiş çapraz platformları görmek ve denemek faydalı olabilir."
---

{{<section feature1>}}
---
title: Java ile PostScript'ten PDF'ye Dönüştürme.
h3: "PS EPS'yi PDF'ye dönüştürmek için Java Kodu"
item1: "PostScript PS ve Encapsulated PostScript EPS dosyalarını Java API aracılığıyla PDF'ye dönüştürmek için sonraki adımları uygulamanız gerekir:"
item2: "[*PsDocument Class*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument) kullanarak PS veya EPS dosyasını yükleyin."
item3: "[*PdfSaveOptions Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfSaveOptions) kullanarak PDF kaydetme seçeneklerini ayarlayın."
item4: "Çıktı PDF dosyası için [*FileStream Class*](https://docs.Oracle.com/javase/7/docs/api/java/io/FileOutputStream.html) kullanın."
item5: "Parametre olarak FileOutputStream nesnesine sahip [*PdfDevice Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfDevice) kullanın."
item6: "[*PsDocument.Save*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) arayın dosyayı PDF'ye kaydetmek için."
---

{{<section feature2>}}
---
title: Java ile PostScript'ten Görüntülere Dönüştürme.
h3: "PostScript'ten Görüntülere Dönüştürme için Java Kodu"
item1: "Herhangi bir EPS/PS PostScript to görüntü dönüştürücü uygulaması için aşağıdaki Java kodu iyi çalışır, bu nedenle sonraki adımları uygulayın:"
item2: PS kaynak dosyasıyla giriş akışını başlatın.
item3: "Parametre olarak oluşturulan PS giriş akışıyla [*PsDocument*](https://reference.aspose.com/page/java/com.aspose.eps/psdocument) nesnesi oluşturun"
item4: "EkFontsFolder ve SuppressError vb. belirtmek için [*ImageSaveOptions*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagesaveoptions) kullanın."
item5: "Gerekirse bir görüntü türü ve boyutu belirtmek için [*ImageDevice*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagedevice) nesnesini kullanın."
item6: PS/EPS dosyasını farklı kaydedin ve görüntüyü bir görüntü kaydetme seçenekleriyle bir bayt dizisi dizisi olarak kaydedin. Bir girdi dosyasının bir sayfası için bir bayt dizisi.
---


{{<section feature3>}}
---
title: XPS'yi Java aracılığıyla JPG, PNG, BMP'ye dönüştürün.
h3: XPS'den Görüntüye Dönüştürme için Java Kodu
item1: "Java API, sayfa düzenini temsil etmek için kullanılan XPS biçimiyle ilgilenir. Herhangi bir senaryoda, XPS'yi programlı olarak BMP, JPG, PNG ve TIFF görüntülerine dönüştürme ihtiyacı olduğunda, aşağıdaki kod Java uygulamasına kolayca entegre edilebilir."
item2: "XPS belgesini yüklemek için [*XpsDocument class*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument) kullanın."
item3: "[*PngSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PngSaveOptions), [*JpegSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/JpegSaveOptions) gibi ilgili görüntü seçeneği sınıfını kullanın, [*BmpSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/BmpSaveOptions), görüntü ek ayarları için [*TiffSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/TiffSaveOptions)."
item4: "[*image device*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/ImageDevice) Sınıf örneğini oluşturun."
item5: "[*XpsDocument.save*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) arayın ) dönüştürülen JPEG görüntüsünü ImageDevice nesnesine kaydetmek ve ardından görüntüyü JPG olarak kaydetmek için ImageDevice'i kullanmak için."
---

{{<section feature4>}}
---
title: Java ile XPS'yi PDF'ye dönüştürün.
h3: XPS'den PDF'ye Dönüştürme için Java Kodu
item1: XPS'yi programlı olarak PDF belgelerine dönüştürme işlemi, giriş ve çıkış dosyaları arasında yüksek kaliteli sonuçlar elde etmek için basittir.
item2: "Dosyayı XpsDocument sınıfını kullanarak yükleyin. [*PdfSaveOptions class*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PdfDevice) nesnesini başlatın."
item3: İşleme için PdfDevice nesnesi oluşturun ve son olarak çıktı PDF belgesini kaydedin.
---


