---
translation: true
template: /_templates/_conversion-java.md
title: PDL Conversion API | Java
url: /java/conversion/
description: Convert PS, EPS, and XPS to PDF and Images including BMP, JPG, PNG, and TIFF using the Java library with the Aspose.Page PDL conversion functionality.
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: Convert PS, EPS, and XPS
h2: PS, EPS, and XPS converter API Solution for Java
---

{{<section overview>}}
---
p1: "Whenever there is need to convert PostScript PS and Encapsulated PostScript EPS Files as well as XPS documents programatically, Java API can do it smoothly and converts multiples files. For PS and EPS, API supports Levels 1-3 PostScript operators and the most of the EPS header comments as well as transforms PostScript documents having maximum conformity with an exception of few fonts cases and API deals such fonts as Time New Roman."
p2: "Moreover, for XPS files transformation, API can add or remove pages, deals with canvases, paths and glyphs elements, create vector graphics shapes, text strings, convert XPS outline items and more."
p3: "The API solution for Java here lets you convert files of such PDL formats as PS, EPS, and XPS programmatically, but you may find useful to see and try cross-platform developed on these native APIs."
---

{{<section feature1>}}
---
title: PostScript to PDF Conversion via Java.
h3: "Java Code to convert PS EPS to PDF"
item1: "To convert PostScript PS and Encapsulated PostScript EPS files to PDF via Java API you need to take the next steps:"
item2: "Load PS or EPS file using [*PsDocument Class*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument). "
item3:  "Set the PDF saving options using [*PdfSaveOptions Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfSaveOptions)."
item4: "Use [*FileStream Class*](https://docs.oracle.com/javase/7/docs/api/java/io/FileOutputStream.html) for output PDF file."
item5: "Use [*PdfDevice Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfDevice) having FileOutputStream object as parameter."
item6: "Call the [*PsDocument.Save*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) for saving into PDF the file."
---

{{<section feature2>}}
---
title: PostScript to Images Conversion via Java.
h3: "Java Code for PostScript to Images Conversion"
item1: "For any EPS/PS PostScript to image converter application, the following Java code works well, so take the next steps:"
item2: Initialize  input stream with PS source file. 
item3: "Create [*PsDocument*](https://reference.aspose.com/page/java/com.aspose.eps/psdocument) object with created PS input stream as a parameter"
item4: "Use [*ImageSaveOptions*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagesaveoptions) to specify AdditionalFontsFolder and SuppressError etc."
item5: "Use [*ImageDevice*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagedevice) object for specifying an image type and size if needed."
item6:  Save PS/EPS file as and image with an image save options as an array of arrays of bytes. One array of bytes for one page of an input file.
---


{{<section feature3>}}
---
title: Convert XPS to Images JPG, PNG, BMP via Java.
h3: Java Code for XPS to Image Conversion
item1: "Java API deals XPS format that is used for representing page layout. In any scenario, whenever there is a need to convert XPS to images BMP, JPG, PNG, and TIFF programmatically, the following code can easily be integrated within the Java application."
item2: "Use [*XpsDocument class*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument) to load the XPS document."
item3: "Use the relevant image option class such as  [*PngSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PngSaveOptions), [*JpegSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/JpegSaveOptions), [*BmpSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/BmpSaveOptions), [*TiffSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/TiffSaveOptions) for image additional settings."
item4: "Create the [*image device*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/ImageDevice) Class instance."
item5: "Call the [*XpsDocument.save*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) to save the converted JPEG image into ImageDevice object and then use ImageDevice for saving the image as a JPG."
---

{{<section feature4>}}
---
title: Convert XPS to PDF via Java.
h3: Java Code for XPS to PDF Conversion
item1: The process of converting XPS to PDF documents programmatically is simple having high fidelity results among the input and output files.
item2: "Load the file using XpsDocument class. Initialize [*PdfSaveOptions class*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PdfDevice) object."
item3: Create PdfDevice object for rendering and lastly save the output PDF document.
---


