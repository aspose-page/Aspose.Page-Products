---
translation: true
template: /_templates/_conversion-java.md
title: PDL Conversion API | Jáva
url: /java/conversion/
description: Konvertálja a PS-t, EPS-t és XPS-t PDF-be és képekké, beleértve a BMP-t, JPG-t, PNG-t és TIFF-et, a Java könyvtár használatával az Aspose.Page PDL konverziós funkcióval.
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: PS, EPS és XPS konvertálása
h2: PS, EPS és XPS konverter API megoldás Java számára
---

{{<section overview>}}
---
p1: "Amikor szükség van a PostScript PS és Encapsulated PostScript EPS fájlok, valamint XPS dokumentumok programozott konvertálására, a Java API zökkenőmentesen meg tudja csinálni, és többszörös fájlokat konvertál. PS és EPS esetén az API támogatja az 1-3. szintű PostScript operátorokat és a legtöbb EPS fejléc megjegyzést, valamint a PostScript dokumentumokat maximális konformációval alakítja át, kivéve néhány betűtípus esetet, és az API olyan betűtípusokkal foglalkozik, mint a Time New Roman."
p2: "Ezenkívül az XPS-fájlok átalakításához az API hozzáadhat vagy eltávolíthat oldalakat, foglalkozhat vásznakkal, útvonalakkal és karakterjelekkel, vektorgrafikus alakzatokat, szöveges karakterláncokat hozhat létre, XPS-vázlatelemeket konvertálhat stb."
p3: "Az itt található Java API-megoldás lehetővé teszi az olyan PDL formátumú fájlok, mint a PS, EPS és XPS, programozott konvertálását, de hasznos lehet az ezeken a natív API-kon kifejlesztett platformok közötti áttekintés és kipróbálás."
---

{{<section feature1>}}
---
title: PostScript konvertálás PDF-be Java segítségével.
h3: "Java kód a PS EPS PDF-be konvertálásához"
item1: "A PostScript PS és az Encapsulated PostScript EPS fájlok PDF formátumba konvertálásához Java API-n keresztül, meg kell tennie a következő lépéseket:"
item2: "Töltsön be PS- vagy EPS-fájlt a használatával [*PsDocument Class*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument)."
item3: "Állítsa be a PDF-mentési beállításokat a [*PdfSaveOptions Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfSaveOptions) segítségével."
item4: "A kimeneti PDF-fájlhoz használja a [*FileStream Class*](https://docs.oracle.com/javase/7/docs/api/java/io/FileOutputStream.html)-ot."
item5: "Használja a [*PdfDevice Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfDevice) fájlt FileOutputStream objektummal paraméterként."
item6: "Hívja a [*PsDocument.Save*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) a fájl PDF formátumba mentéséhez."
---

{{<section feature2>}}
---
title: PostScript-kép konvertálás Java-n keresztül.
h3: "Java kód a PostScript képekké konvertálásához"
item1: "Bármely EPS/PS PostScript-kép konvertáló alkalmazás esetén a következő Java-kód jól működik, ezért tegye meg a következő lépéseket:"
item2: A bemeneti adatfolyam inicializálása PS-forrásfájllal.
item3: "Hozzon létre [*PsDocument*](https://reference.aspose.com/page/java/com.aspose.eps/psdocument) objektumot a létrehozott PS bemeneti adatfolyammal paraméterként"
item4: "Az [*ImageSaveOptions*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagesaveoptions) használatával adja meg az AdditionalFontsFolder és SuppressError stb."
item5: "Ha szükséges, használja az [*ImageDevice*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagedevice) objektumot a kép típusának és méretének megadásához."
item6: Mentse a PS/EPS-fájlt más néven és a képet egy képmentési lehetőséggel bájttömbként. Egy bájttömb egy bemeneti fájl egy oldalához.
---


{{<section feature3>}}
---
title: Az XPS konvertálása JPG, PNG, BMP képekké Java segítségével.
h3: Java kód az XPS képátalakításhoz
item1: "A Java API XPS formátummal foglalkozik, amelyet az oldalelrendezés ábrázolására használnak. Bármilyen forgatókönyv esetén, amikor az XPS-t BMP, JPG, PNG és TIFF képekké kell programozottan konvertálni, a következő kód könnyen integrálható a Java alkalmazásba."
item2: "Az XPS-dokumentum betöltéséhez használja az [*XpsDocument class*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument) szolgáltatást."
item3: "Használja a megfelelő képbeállítási osztályt, például [*PngSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PngSaveOptions), [*JpegSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/JpegSaveOptions), [*BmpSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/BmpSaveOptions) , [*TiffSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/TiffSaveOptions) a kép további beállításaiért."
item4: "Hozza létre a [*image device*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/ImageDevice) osztálypéldányt."
item5: "Hívja a [*XpsDocument.save*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-), hogy a konvertált JPEG képet ImageDevice objektumba mentse, majd az ImageDevice segítségével mentse a képet JPG formátumban."
---

{{<section feature4>}}
---
title: Konvertálja az XPS-t PDF-be Java segítségével.
h3: Java kód az XPS PDF-be konvertálásához
item1: Az XPS programozottan PDF-dokumentummá konvertálása egyszerű, mivel a bemeneti és kimeneti fájlok között nagy pontosságú eredmények érhetők el.
item2: "Töltse be a fájlt az XpsDocument osztály segítségével. Inicializálja a [*PdfSaveOptions class*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PdfDevice) objektumot."
item3: Hozzon létre PdfDevice objektumot a rendereléshez, majd mentse el a kimeneti PDF dokumentumot.
---


