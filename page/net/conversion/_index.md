---
title: C# Encapsulated PostScript and XPS Files Conversion
url: /net/conversion/
description: Convert PS, EPS and XPS to PDF and Images including BMP, JPG, PNG, TIFF with few lines of C# code via .NET library.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="XPS and PostScript Files Conversion Via C#" h2="Convert PS, EPS and XPS to PDF and BMP, PNG, JPEG, TIFF Images to build cross-platform .NET applications." >}}

{{% blocks/products/pf/feature-page-summary %}}

Whenever there is need to convert PostScript PS and Encapsulated PostScript EPS Files as well as XPS documents programatically, .NET API can do it smoothly and converts multiples files. For PS and EPS, API supports Levels 1-3 PostScript operators and the most of the EPS header comments as well as transforms PostScript documents having maximum conformity with an exception of few fonts cases and API deals such fonts as Time New Roman.

Moreover, for XPS files transformation, API can add or remove pages, deals with canvases, paths and glyphs elements, create vector graphics shapes, text strings, convert XPS outline items and more.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Convert PostScript to PDF" %}}

To convert PostScript PS and Encapsulated PostScript EPS files to PDF, Process is, load PS or EPS file using [PsDocument class](https://apireference.aspose.com/page/net/aspose.page.eps/psdocument). Set PDF options using [PdfSaveOptions class](https://apireference.aspose.com/page/net/aspose.page.eps.device/pdfsaveoptions). Use [FileStream class](https://docs.microsoft.com/en-us/dotnet/api/system.io.filestream) for output PDF file. Use [PdfDevice class](https://apireference.aspose.com/page/net/aspose.page.eps.device/pdfdevice) by intializing with output PDF filestream object. And finally call [PsDocument.Save](https://apireference.aspose.com/page/net/aspose.page.eps/psdocument/methods/save) for PDF conversion.

{{% blocks/products/pf/feature-page-code h3="C# Code for PS EPS to PDF Conversion" %}}

{{< gist "aspose-com-gists" "f573befec15bcb9a5374a6dbeeefcab0" "convert-postscript-to-pdf.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ps-to-pdf eps-to-pdf xps-to-pdf" >}}

{{% blocks/products/pf/feature-page-section  h2="PostScript to Images Conversion" %}}

For any EPS/PS PostScript to image converter application, following code works well. Process is, Load document using PsDocument class having input file stream as parameter. Create [ImageSaveOptions class](https://apireference.aspose.com/page/net/aspose.page.xps.presentation.image/imagesaveoptions) object and intialize it with required settings. Finally save each input file page to an image PNG, JPG, TIFF, BMP etc.


{{% blocks/products/pf/feature-page-code h3="C# Code for PostScript to Images Conversion" %}}

{{< gist "aspose-com-gists" "f573befec15bcb9a5374a6dbeeefcab0" "convert-postscript-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ps-to-bmp ps-to-png ps-to-jpeg ps-to-tiff ps-to-gif eps-to-gif eps-to-tiff eps-to-jpeg eps-to-png eps-to-bmp" >}}

{{% blocks/products/pf/feature-page-section  h2="Convert XPS to Images JPG, PNG, BMP" %}}

.NET API also supports XPS Conversion to Images BMP, JPG, PNG, TIFF etc. and provides [XpsDocument class](https://apireference.aspose.com/page/net/aspose.page.xps/xpsdocument) for XPS operations. To convert **XPS to Image**, Process is, Load XPS file from stream. Intialize the relevant image save options e.g for **XPS to JPG** it is [JpegSaveOptions](https://apireference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions) and for **XPS to PNG** its [PngSaveOptions](https://apireference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions). Here is list of all XPS to Image [save options](https://apireference.aspose.com/page/net/aspose.page.xps.presentation.image). Define relevant settings such as SmoothingMode, Resolution, and PageNumbers etc for rendering. Finally iterate through document partitions to save into images.

{{% blocks/products/pf/feature-page-code h3="C# Code for XPS to Image Conversion" %}}

{{< gist "aspose-com-gists" "f573befec15bcb9a5374a6dbeeefcab0" "convert-xps-to-image.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xps-to-bmp xps-to-png xps-to-tiff xps-to-jpeg" >}}