---
translation: true
template: /_templates/_conversion-cpp.md
title: PDL Conversion API | C++
url: /cpp/conversion/
description: Převádějte PS, EPS a XPS do PDF a obrázků včetně BMP, JPG, PNG a TIFF pomocí knihovny C++ s funkcí převodu Aspose.Page PDL.
family: page
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: Převod PS, EPS a XPS
h2: Řešení API převodníku PS, EPS a XPS pro C++.
---

{{<section overview>}}
---
p1: "Kdykoli je potřeba programově převést soubory PostScript PS a Encapsulated PostScript EPS, stejně jako dokumenty XPS, Java API to dokáže hladce a převede více souborů. Pro PS a EPS API podporuje PostScriptové operátory úrovní 1-3 a většinu komentářů hlaviček EPS, stejně jako transformuje PostScriptové dokumenty s maximální shodou s výjimkou několika případů písem a API se zabývá písmy jako Time New Roman."
p2: "Programátoři jej mohou snadno použít pro dávkové zpracování dokumentů PostScript a XPS, dokonce i manipulovat s plátny, cestami a prvky glyfů a zpracovávat tvary vektorové grafiky a textové řetězce."
p3: "Řešení API pro Javu vám zde umožňuje převádět soubory takových formátů PDL, jako jsou PS, EPS a XPS, programově, ale může být užitečné vidět a vyzkoušet multiplatformní vývoj na těchto nativních rozhraních API. Zde je několik scénářů převodu, jako je EPS na obrázky, EPS na PDF, PostScript na PDF, PostScript na obrázky, XPS na obrázky a XPS na PDF"
---

{{<section feature1>}}
---
title: Převeďte EPS na obrázky pomocí C++.
h3: Kód C++ pro konverzi EPS na obrázky
item1: "Knihovna C++ umožňuje převod souborů Encapsulated PostScript (EPS) na obrázky na platformách Windows a Linux. Postup je:"
item2: "Použijte FileStream k vytvoření vstupního toku pro soubor EPS a také k vytvoření [*PsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.ps_document) objektu se vstupním tokem jako parametr. Pro nastavení specifická pro obrázky použijte [*ImageSaveOptions Class*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_save_options)."
item3: "Definujte typ a velikost obrázku pomocí [*ImageDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_device)."
item4: Uložte EPS jako obrázky s možnostmi uložení obrázku do pole polí bajtů, čímž se pro každé pole bajtů vytvoří nový výstupní proud souboru.
---


{{<section feature2>}}
---
title: Převod PostScriptu do PDF přes Java.
h3: C++ kód pro převod PostScript do PDF
item1: "Proces převodu PostScriptu do PDF je stejný jako u EPS na obrázky, kromě toho, že vývojáři použijí [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_save_options) k definování dalších nastavení, jako jsou AdditionalFontsFolder a SuppressError value atd. Navíc bude používat [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_device) z vytvořeného výstupního proudu."
---

{{<section feature3>}}
---
title: Převést XPS do PDF přes C++.
h3: C++ kód pro převod XPS do PDF
item1: "C++ XPS Processing API se zabývá převodem XPS na obrázky včetně BMP, JPG, TIFF, PNG a dalších, stejně jako převodem XPS do PDF na systémech Windows a Linux. Proces převodu XPS do PDF je:"
item2: Definujte výstupní tok a také definujte vstupní tok pro vstupní dokument XPS.
item3: "Předejte jej jako parametr do [*XpsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.xps_document) objektu."
item4: "Pomocí [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_save_options) zadejte možnosti uložení specifické pro PDF, jako je TextCompression, ImageCompression a JpegQualityLevel."
item5: "Vytvořte instanci [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_device) z dříve vytvořeného výstupního proudu."
item6: Nakonec převeďte dokument XPS jako PDF pomocí možností uložení PDF.
---
