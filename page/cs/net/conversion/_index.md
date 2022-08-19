---
translation: true
template: /_templates/_conversion-net.md
title: PDL Conversion API C# | .NET
url: /net/conversion/
description: Převádějte PS, EPS a XPS do PDF a obrázků včetně BMP, JPG, PNG a TIFF pomocí knihovny .NET s funkcí převodu Aspose.Page PDL.
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: Převod PS, EPS a XPS
h2: Řešení API pro převodníky PS, EPS a XPS pro .NET.
---

{{<section overview>}}
---
p1: "Kdykoli je potřeba programově převést soubory PostScript PS a Encapsulated PostScript EPS, stejně jako dokumenty XPS, .NET API to dokáže hladce a převede více souborů. Pro PS a EPS API podporuje PostScriptové operátory úrovní 1-3 a většinu komentářů hlaviček EPS, stejně jako transformuje PostScriptové dokumenty s maximální shodou s výjimkou několika případů písem a API se zabývá písmy jako Time New Roman."
p2: "Navíc pro transformaci souborů XPS může API přidávat nebo odebírat stránky, zabývá se prvky plátna, cestami a glyfy, vytváří tvary vektorové grafiky, textové řetězce, převádí obrysové položky XPS a další."
p3: "Řešení API pro .NET zde umožňuje převádět soubory takových formátů PDL, jako jsou PS, EPS a XPS, programově, ale může být užitečné vidět a vyzkoušet multiplatformní vývoj na těchto nativních rozhraních API."
---

{{<section feature1>}}
---
title: Převod PostScriptu do PDF přes C# .NET.
h3: "C# kód pro převod PS EPS do PDF"
item1: "Chcete-li převést soubory PostScript PS a Encapsulated PostScript EPS do PDF pomocí rozhraní .NET API, musíte provést následující kroky:"
item2: "Načtěte soubor PS nebo EPS pomocí [*PsDocument Class*](https://reference.aspose.com/page/net/aspose.page.eps/psdocument/)."
item3: "Nastavte ukládání PDF pomocí [*PdfSaveOptions Class*](https://reference.aspose.com/page/net/aspose.page.eps.device/pdfsaveoptions/)."
item4: "Pro výstupní soubor PDF použijte [*FileStream Class*](https://docs.microsoft.com/en-us/dotnet/api/system.io.filestream)."
item5: "[*PdfDevice Class*](https://reference.aspose.com/page/net/aspose.page.eps.device/pdfdevice/) inicializací pomocí výstupního objektu PDF filestream."
item6: "Zavolejte [*PsDocument.Save*](https://reference.aspose.com/page/net/aspose.page.eps/psdocument/save/) pro převod PDF."
---

{{<section feature2>}}
---
title: Převod PostScriptu na obrázky přes C# .NET.
h3: "C# kód pro převod PostScriptu na obrázky"
item1: "Pro libovolnou aplikaci pro převod EPS/PS PostScript na obrázek funguje následující kód C# dobře, takže proveďte následující kroky:"
item2: Načtěte dokument pomocí třídy PsDocument, která má jako parametr proud vstupního souboru.
item3: "Vytvořte objekt [*ImageSaveOptions Class*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/imagesaveoptions/) a inicializujte jej s požadovanými nastaveními."
item4: Uložte každou stránku vstupního souboru do obrázku PNG, JPG, TIFF, BMP atd.
---

{{<section feature3>}}
---
title: Převod XPS na obrázky JPG, PNG, BMP přes C# .NET.
h3: "C# kód pro převod XPS na obrázek"
item1: ".NET API také podporuje převod XPS na obrázky BMP, JPG, PNG, TIFF atd. a poskytuje třídu XpsDocument pro operace XPS. Chcete-li převést XPS na obrázek, proveďte následující kroky:"
item2: Načtěte soubor XPS ze streamu.
item3: "Inicializujte příslušné možnosti uložení obrázku, např. pro **XPS to JPG** je to [*JpegSaveOptions*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions/) a pro **XPS to PNG** jeho [*PngSaveOptions*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions/). Zde je seznam všech XPS to Image [*možnosti uložení*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/)."
item4: Definujte relevantní nastavení, jako je SmoothingMode, Resolution a PageNumbers atd. pro vykreslování. Nakonec projděte oddíly dokumentů a uložte je do obrázků.
---
