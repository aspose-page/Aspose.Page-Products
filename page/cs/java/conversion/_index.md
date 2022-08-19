---
translation: true
template: /_templates/_conversion-java.md
title: PDL Conversion API | Jáva
url: /java/conversion/
description: Převádějte PS, EPS a XPS do PDF a obrázků včetně BMP, JPG, PNG a TIFF pomocí knihovny Java s funkcí převodu Aspose.Page PDL.
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: Převod PS, EPS a XPS
h2: Řešení API pro převodníky PS, EPS a XPS pro Javu
---

{{<section overview>}}
---
p1: "Kdykoli je potřeba programově převést soubory PostScript PS a Encapsulated PostScript EPS, stejně jako dokumenty XPS, Java API to dokáže hladce a převede více souborů. Pro PS a EPS API podporuje PostScriptové operátory úrovní 1-3 a většinu komentářů hlaviček EPS, stejně jako transformuje PostScriptové dokumenty s maximální shodou s výjimkou několika případů písem a API se zabývá písmy jako Time New Roman."
p2: "Navíc pro transformaci souborů XPS může API přidávat nebo odebírat stránky, zabývá se prvky plátna, cestami a glyfy, vytváří tvary vektorové grafiky, textové řetězce, převádí obrysové položky XPS a další."
p3: "Řešení API pro Javu vám zde umožňuje převádět soubory takových formátů PDL, jako jsou PS, EPS a XPS, programově, ale může být užitečné vidět a vyzkoušet multiplatformní vývoj na těchto nativních rozhraních API."
---

{{<section feature1>}}
---
title: Převod PostScriptu do PDF přes Java.
h3: "Java kód pro převod PS EPS do PDF"
item1: "Chcete-li převést soubory PostScript PS a Encapsulated PostScript EPS do PDF pomocí Java API, musíte provést následující kroky:"
item2: "Načtěte soubor PS nebo EPS pomocí [*PsDocument Class*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument)."
item3: "Nastavte možnosti uložení PDF pomocí [*PdfSaveOptions Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfSaveOptions)."
item4: "Pro výstupní soubor PDF použijte [*FileStream Class*](https://docs.oracle.com/javase/7/docs/api/java/io/FileOutputStream.html)."
item5: "Použijte [*PdfDevice Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfDevice) s objektem FileOutputStream jako parametrem."
item6: "Zavolejte na [*PsDocument.Save*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) pro uložení souboru do PDF."
---

{{<section feature2>}}
---
title: Převod PostScriptu na obrázky přes Java.
h3: "Java kód pro převod PostScript na obrázky"
item1: "Pro jakoukoli aplikaci pro převod EPS/PS PostScript na obrázek funguje následující kód Java dobře, takže proveďte následující kroky:"
item2: Inicializujte vstupní proud se zdrojovým souborem PS.
item3: "Vytvořte objekt [*PsDocument*](https://reference.aspose.com/page/java/com.aspose.eps/psdocument) s vytvořeným vstupním tokem PS jako parametrem"
item4: "Pomocí [*ImageSaveOptions*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagesaveoptions) zadejte AdditionalFontsFolder a SuppressError atd."
item5: "V případě potřeby použijte objekt [*ImageDevice*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagedevice) pro určení typu a velikosti obrázku."
item6: Uložit soubor PS/EPS jako a obrázek s možnostmi uložení obrázku jako pole polí bajtů. Jedno pole bajtů pro jednu stránku vstupního souboru.
---


{{<section feature3>}}
---
title: Převod XPS na obrázky JPG, PNG, BMP přes Java.
h3: Java kód pro převod XPS na obrázek
item1: "Java API nabízí formát XPS, který se používá pro reprezentaci rozvržení stránky. V jakémkoli scénáři, kdykoli je potřeba převést XPS na obrázky BMP, JPG, PNG a TIFF programově, lze následující kód snadno integrovat do aplikace Java."
item2: "K načtení dokumentu XPS použijte [*XpsDocument class*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument)."
item3: "Použijte příslušnou třídu možností obrázku, jako je [*PngSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PngSaveOptions), [*JpegSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/JpegSaveOptions), [*BmpSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/BmpSaveOptions) , [*TiffSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/TiffSaveOptions) pro další nastavení obrázků."
item4: "Vytvořte instanci třídy [*image device*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/ImageDevice)."
item5: "Zavolejte na [*XpsDocument.save*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) uložte převedený obrázek JPEG do objektu ImageDevice a poté použijte ImageDevice k uložení obrázku jako JPG."
---

{{<section feature4>}}
---
title: Převod XPS do PDF přes Java.
h3: Java kód pro převod XPS do PDF
item1: Proces programového převodu XPS na PDF dokumenty je jednoduchý a má vysoce věrné výsledky mezi vstupními a výstupními soubory.
item2: "Načtěte soubor pomocí třídy XpsDocument. Inicializujte objekt [*třída PdfSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PdfDevice)."
item3: Vytvořte objekt PdfDevice pro vykreslení a nakonec uložte výstupní dokument PDF.
---


