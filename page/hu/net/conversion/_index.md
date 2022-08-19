---
translation: true
template: /_templates/_conversion-net.md
title: PDL Conversion API C# | .NET
url: /net/conversion/
description: Konvertálja a PS-t, EPS-t és XPS-t PDF-be és képekké, beleértve a BMP-t, JPG-t, PNG-t és TIFF-et a .NET-könyvtár segítségével az Aspose.Page PDL-konverziós funkcióval.
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: PS, EPS és XPS konvertálása
h2: PS, EPS és XPS konverter API megoldás .NET-hez.
---

{{<section overview>}}
---
p1: "Amikor szükség van a PostScript PS és Encapsulated PostScript EPS fájlok, valamint XPS dokumentumok programozott konvertálására, a .NET API zökkenőmentesen meg tudja csinálni, és többszörös fájlokat konvertál. PS és EPS esetén az API támogatja az 1-3. szintű PostScript operátorokat és a legtöbb EPS fejléc megjegyzést, valamint a PostScript dokumentumokat maximális konformációval alakítja át, kivéve néhány betűtípus esetet, és az API olyan betűtípusokkal foglalkozik, mint a Time New Roman."
p2: "Ezenkívül az XPS-fájlok átalakításához az API hozzáadhat vagy eltávolíthat oldalakat, foglalkozhat vásznakkal, útvonalakkal és karakterjelekkel, vektorgrafikus alakzatokat, szöveges karakterláncokat hozhat létre, XPS-vázlatelemeket konvertálhat stb."
p3: "A .NET-hez készült API-megoldás itt lehetővé teszi az olyan PDL formátumú fájlok, mint a PS, EPS és XPS, programozott konvertálását, de hasznos lehet megnézni és kipróbálni az ezeken a natív API-kon kifejlesztett többplatformos fájlokat."
---

{{<section feature1>}}
---
title: PostScript konvertálás PDF-be C# .NET-en keresztül.
h3: "C# kód a PS EPS-ből PDF-be konvertálásához"
item1: "A PostScript PS és Encapsulated PostScript EPS fájlok PDF formátumba konvertálásához .NET API-n keresztül a következő lépéseket kell tennie:"
item2: "Töltsön be PS- vagy EPS-fájlt a használatával [*PsDocument Class*](https://reference.aspose.com/page/net/aspose.page.eps/psdocument/)."
item3: "Állítsa be a PDF-mentést a [*PdfSaveOptions Class*](https://reference.aspose.com/page/net/aspose.page.eps.device/pdfsaveoptions/) használatával."
item4: "A kimeneti PDF-fájlhoz használja a [*FileStream Class*](https://docs.microsoft.com/en-us/dotnet/api/system.io.filestream) elemet."
item5: "[*PdfDevice Class*](https://reference.aspose.com/page/net/aspose.page.eps.device/pdfdevice/) a kimeneti PDF fájlfolyam objektummal történő inicializálással."
item6: "Hívja a [*PsDocument.Save*](https://reference.aspose.com/page/net/aspose.page.eps/psdocument/save/) fájlt a PDF-konverzióhoz."
---

{{<section feature2>}}
---
title: PostScript konvertálás képekké C# .NET-en keresztül.
h3: "C# kód a PostScript képekké konvertálásához"
item1: "Bármely EPS/PS PostScript to image konverter alkalmazás esetén a következő C# kód jól működik, ezért tegye meg a következő lépéseket:"
item2: Dokumentum betöltése PsDocument osztály használatával, amelynek paramétere a bemeneti fájlfolyam.
item3: "Hozzon létre [*ImageSaveOptions Class*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/imagesaveoptions/) objektumot, és inicializálja a szükséges beállításokkal."
item4: Mentse el az egyes bemeneti fájloldalakat PNG, JPG, TIFF, BMP stb. képként.
---

{{<section feature3>}}
---
title: Az XPS konvertálása JPG, PNG, BMP képekké C# .NET-en keresztül.
h3: "C# kód az XPS képátalakításhoz"
item1: "A .NET API támogatja az XPS BMP, JPG, PNG, TIFF stb. képekké történő konvertálását is, és XPS-műveletekhez XPSDocument Class-t biztosít. Az XPS képpé konvertálásához tegye a következő lépéseket:"
item2: Töltse be az XPS-fájlt az adatfolyamból.
item3: "Inicializálja a megfelelő képmentési beállításokat, például **XPS-ről JPG-re**, ez [*JpegSaveOptions*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions/) **XPS to PNG** esetén pedig a [*PngSaveOptions*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions/). Itt található az összes XPS to Image listája [*mentési opciók*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/)."
item4: Adja meg a megfelelő beállításokat, például a SmoothingMode, Resolution és PageNumbers stb. megjelenítést. Végül ismételje meg a dokumentumpartíciókat, és mentse őket képekbe.
---
