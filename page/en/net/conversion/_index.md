---
translation: true
template: /_templates/_conversion-net.md
title: PDL Conversion API C# | .NET 
url: /net/conversion/
description: Convert PS, EPS, and XPS to PDF and Images including BMP, JPG, PNG, and TIFF using the .NET library with the Aspose.Page PDL conversion functionality.
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: Convert PS, EPS, and XPS
h2: PS, EPS, and XPS converter API Solution for .NET.
---

{{<section overview>}}
---
p1: "Whenever there is need to convert PostScript PS and Encapsulated PostScript EPS Files as well as XPS documents programatically, .NET API can do it smoothly and converts multiples files. For PS and EPS, API supports Levels 1-3 PostScript operators and the most of the EPS header comments as well as transforms PostScript documents having maximum conformity with an exception of few fonts cases and API deals such fonts as Time New Roman."
p2: "Moreover, for XPS files transformation, API can add or remove pages, deals with canvases, paths and glyphs elements, create vector graphics shapes, text strings, convert XPS outline items and more."
p3: "The API solution for .NET here lets you convert files of such PDL formats as PS, EPS, and XPS programmatically, but you may find useful to see and try cross-platform developed on these native APIs."
---

{{<section feature1>}}
---
title: PostScript to PDF Conversion via C# .NET.
h3: "C# Code for PS EPS to PDF Conversion"
item1: "To convert PostScript PS and Encapsulated PostScript EPS files to PDF via .NET API you need to take the next steps:"
item2: "Load PS or EPS file using [*PsDocument Class*](https://reference.aspose.com/page/net/aspose.page.eps/psdocument/). "
item3:  "Set the PDF saving using [*PdfSaveOptions Class*](https://reference.aspose.com/page/net/aspose.page.eps.device/pdfsaveoptions/)."
item4: "Use [*FileStream Class*](https://docs.microsoft.com/en-us/dotnet/api/system.io.filestream) for output PDF file."
item5: "[*PdfDevice Class*](https://reference.aspose.com/page/net/aspose.page.eps.device/pdfdevice/) by initializing with output PDF filestream object."
item6: "Call [*PsDocument.Save*](https://reference.aspose.com/page/net/aspose.page.eps/psdocument/save/) for PDF conversion."
---

{{<section feature2>}}
---
title: PostScript to Images Conversion via C# .NET.
h3: "C# Code for PostScript to Images Conversion"
item1: "For any EPS/PS PostScript to image converter application, the following C# code works well, so take the next steps:"
item2: Load document using PsDocument class having input file stream as a parameter. 
item3: "Create [*ImageSaveOptions Class*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/imagesaveoptions/) object and initialize it with the required settings."
item4: Save each input file page to an image PNG, JPG, TIFF, BMP, etc. 
---

{{<section feature3>}}
---
title: Convert XPS to Images JPG, PNG, BMP via C# .NET.
h3: "C# Code for XPS to Image Conversion"
item1: ".NET API also supports XPS Conversion to Images BMP, JPG, PNG, TIFF, etc., and provides XpsDocument Class for XPS operations. To convert XPS to Image take the next steps:"
item2: Load XPS file from the stream. 
item3: "Initialize the relevant image save options e.g for **XPS to JPG** it is [*JpegSaveOptions*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions/) and for **XPS to PNG** its [*PngSaveOptions*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions/). Here is list of all XPS to Image [*save options*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/)."
item4: Define relevant settings such as SmoothingMode, Resolution, and PageNumbers etc. for rendering. Finally iterate through document partitions to save them into images.
---
