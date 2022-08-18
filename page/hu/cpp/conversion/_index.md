---
translation: true
template: /_templates/_conversion-cpp.md
title: PDL Conversion API | C++
url: /cpp/conversion/
description: Konvertálja a PS-t, EPS-t és XPS-t PDF-be és képekké, beleértve a BMP-t, JPG-t, PNG-t és TIFF-et a C++ könyvtár használatával az Aspose.Page PDL-konverziós funkcióval.
family: page
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: PS, EPS és XPS konvertálása
h2: PS, EPS és XPS konverter API megoldás C++-hoz.
---

{{<section overview>}}
---
p1: "Amikor szükség van a PostScript PS és Encapsulated PostScript EPS fájlok, valamint XPS dokumentumok programozott konvertálására, a Java API zökkenőmentesen meg tudja csinálni, és többszörös fájlokat konvertál. PS és EPS esetén az API támogatja az 1-3. szintű PostScript operátorokat és a legtöbb EPS fejléc megjegyzést, valamint a PostScript dokumentumokat maximális konformációval alakítja át, kivéve néhány betűtípus esetet, és az API olyan betűtípusokkal foglalkozik, mint a Time New Roman."
p2: "A programozók könnyedén használhatják PostScript- és XPS-dokumentumok kötegelt feldolgozására, még a vásznak, útvonalak és karakterjelek elemeit is kezelhetik, és vektorgrafikus alakzatokat és szöveges karakterláncokat is kezelhetnek."
p3: "Az itt található Java API-megoldás lehetővé teszi az olyan PDL formátumú fájlok, mint a PS, EPS és XPS, programozott konvertálását, de hasznos lehet az ezeken a natív API-kon kifejlesztett platformok közötti áttekintés és kipróbálás. Íme néhány forgatókönyv az EPS-ből képekké, EPS-ből PDF-be, PostScript-ből PDF-be, PostScript-ből képekké, XPS-ből képekké és XPS-ből PDF-be"
---

{{<section feature1>}}
---
title: Konvertálja az EPS-t képekké a C++ segítségével.
h3: C++ kód az EPS-képekké konvertálásához
item1: "A C++ könyvtár lehetővé teszi az Encapsulated PostScript (EPS) fájlok képpé konvertálását Windows és Linux platformokon. A folyamat a következő:"
item2: "A FileStream segítségével hozza létre az EPS-fájl bemeneti adatfolyamát, valamint hozzon létre [*PsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.ps_document) objektumot bemeneti adatfolyammal paraméterként. A képspecifikus beállításokhoz használja az [*ImageSaveOptions Class*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_save_options) elemet."
item3: "Határozza meg a kép típusát és méretét az [*ImageDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_device) segítségével."
item4: Mentse az EPS-t képként képmentési lehetőségekkel egy bájttömbbe, amely minden bájttömbhöz új fájlkimeneti adatfolyamot hoz létre.
---


{{<section feature2>}}
---
title: PostScript konvertálás PDF-be Java segítségével.
h3: C++ kód a PostScript PDF-be konvertálásához
item1: "A PostScript PDF-be konvertálásának folyamata ugyanaz, mint az EPS-nél képekké, azzal a különbséggel, hogy a fejlesztők [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_save_options) további beállítások megadásához, például az AdditionalFontsFolder és a SuppressError érték stb. A [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_device) a létrehozott kimeneti adatfolyamból."
---

{{<section feature3>}}
---
title: Az XPS konvertálása PDF-be C++ segítségével.
h3: C++ kód az XPS-ből PDF-be konvertáláshoz
item1: "A C++ XPS Processing API az XPS képekké konvertálásával foglalkozik, beleértve a BMP-t, JPG-t, TIFF-et, PNG-t és egyebeket, valamint XPS-t PDF-be konvertálásával Windows és Linux alapú rendszereken. Az XPS PDF-be konvertálásának folyamata a következő:"
item2: Határozza meg a kimeneti adatfolyamot, valamint a bemeneti adatfolyamot a bemeneti XPS-dokumentumhoz.
item3: "Adja át paraméterként az [*XpsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.xps_document) objektumnak."
item4: "Adja meg a PDF-specifikus mentési beállításokat, például TextCompression, ImageCompression és JpegQualityLevel a [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_save_options) segítségével."
item5: "Hozzon létre egy [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_device) példányt a létrehozott korábbi kimeneti adatfolyamból."
item6: Végül konvertálja az XPS-dokumentumot PDF-be a PDF mentési lehetőségekkel.
---
