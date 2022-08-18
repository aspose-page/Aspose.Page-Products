---
translation: true
template: /_templates/_conversion-cpp.md
title: PDL Conversion API | C++
url: /cpp/conversion/
description: Convert PS, EPS, and XPS to PDF and Images including BMP, JPG, PNG, and TIFF using the C++ library with the Aspose.Page PDL conversion functionality.
family: page
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: Convert PS, EPS, and XPS
h2: PS, EPS, and XPS converter API Solution for C++.
---

{{<section overview>}}
---
p1: "Whenever there is need to convert PostScript PS and Encapsulated PostScript EPS Files as well as XPS documents programatically, Java API can do it smoothly and converts multiples files. For PS and EPS, API supports Levels 1-3 PostScript operators and the most of the EPS header comments as well as transforms PostScript documents having maximum conformity with an exception of few fonts cases and API deals such fonts as Time New Roman."
p2: "Programmers can easily use it for batch processing of PostScript and XPS documents, even manipulate canvases, paths and glyphs elements and handle vector graphics shapes and text strings."
p3: "The API solution for Java here lets you convert files of such PDL formats as PS, EPS, and XPS programmatically, but you may find useful to see and try cross-platform developed on these native APIs. Here are few scenarios of conversion such as EPS to Images, EPS to PDF, PostScript to PDF, PostScript to Images, XPS to Images and XPS to PDF"
---

{{<section feature1>}}
---
title: Convert EPS to Images via C++.
h3: C++ Code for EPS to Images Conversion
item1: "C++ library allows converting Encapsulated PostScript (EPS) files to images on Windows and Linux platforms. The process is:"
item2: "Use FileStream to create the input stream for EPS file as well as to create [*PsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.ps_document) object having input stream as a parameter. For Images specific settings, use the [*ImageSaveOptions Class*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_save_options)."
item3:  "Define the image type and size using [*ImageDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_device)."
item4: Save EPS as images with image save options to an array of arrays of bytes creating for every bytes array a new file output stream.
---


{{<section feature2>}}
---
title: PostScript to PDF Conversion via Java.
h3: C++ Code for PostScript to PDF Conversion
item1: "The process of converting PostScript to PDF is the same as of EPS to Images, except that developers will use [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_save_options) to define additional settings such as AdditionalFontsFolder and SuppressError value etc. Moreover, will use [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_device) from the created output stream."
---

{{<section feature3>}}
---
title: Convert XPS to PDF via C++.
h3: C++ Code for XPS to PDF Conversion
item1: "C++ XPS Processing API deals with the conversion of XPS to Images including BMP, JPG, TIFF, PNG, and more, as well as XPS to PDF conversion on Windows and Linux-based systems. The process of converting XPS to PDF is:"
item2: Define the output stream as well as define the input stream for input XPS document.
item3: "Pass it as parameter to [*XpsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.xps_document) Object."
item4: "Specify the PDF specific save options such as TextCompression, ImageCompression and JpegQualityLevel using [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_save_options)."
item5: "Create an instance of [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_device) from the created earlier output stream."
item6: Finally convert XPS document as PDF with the PDF save options.
---
