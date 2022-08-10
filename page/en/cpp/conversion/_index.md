---
title: PDL Conversion via C++ API
url: /cpp/conversion/
description: Convert PS, EPS, and XPS to PDF and Images including BMP, JPG, PNG, and TIFF using the C++ library with the Aspose.Page PDL conversion functionality.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="XPS and PostScript Files Conversion Via C++" h2="Convert EPS, PS and XPS to Images and PDF within any C++ based applications." >}}

{{% blocks/products/pf/feature-page-summary %}}

C++ library facilitates the rendering of the PostScript PS and Encapsulated PostScript EPS and XPS files. Programmers can easily use it for batch processing of PostScript and XPS documents, even manipulate canvases, paths and glyphs elements and handle vector graphics shapes and text strings. Here are few scenarios of conversion such as **EPS to Images**, **EPS to PDF**, **PostScript to PDF**, **PostScript to Images**, **XPS to Images** and **XPS to PDF**
 
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Convert EPS to Images" %}}


C++ library allows to convert Encapsulated PostScript (EPS) file to images on Windows and Linux platform. Process is 
Using FileStream create the input stream for EPS file as well as create [PsDocument class](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.ps_document) object having input stream as parameter. For Images specific settings, use the [ImageSaveOptions class](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_save_options). Define image type and size using [ImageDevice](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_device). Save EPS as images with image save options to an array of arrays of bytes creating for every bytes array a new file output stream.

{{% blocks/products/pf/feature-page-code h3="C++ Code for EPS to Images Conversion" %}}

{{< gist "aspose-com-gists" "e1af0e06639806637acbe94be7b2c76a" "convert-eps-to-images.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="eps-to-bmp eps-to-jpeg eps-to-png eps-to-tiff" >}}

{{% blocks/products/pf/feature-page-section  h2="PostScript to PDF Conversion" %}}


Process of converting PostScript to PDF is same as of EPS to Images, except that developers will use [PdfSaveOptions](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_save_options) to define additional settings such as AdditionalFontsFolder and SuppressError value etc. Moreover, will use [PdfDevice](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_device) from created output stream. 


{{% blocks/products/pf/feature-page-code h3="C++ Code for PostScript to PDF Conversion" %}}

{{< gist "aspose-com-gists" "e1af0e06639806637acbe94be7b2c76a" "convert-postscript-to-pdf.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ps-to-pdf eps-to-pdf" >}}

{{% blocks/products/pf/feature-page-section  h2="Convert XPS to PDF" %}}

C++ XPS Processing API deals with conversion of XPS to Images including BMP, JPG, TIFF, PNG and more, as well as XPS to PDF conversion on Windows and Linux based systems. Process of converting XPS to PDF is, define output stream. As well as define input stream for input XPS document and pass as parameter to [XpsDocument class](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.xps_document) Object. 
Specify the PDF specific save options such as TextCompression, ImageCompression and JpegQualityLevel using [PdfSaveOptions](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_save_options). Create an instance of [PdfDevice](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_device) from created earlier output stream. Finally convert XPS document as PDF with PDF save options.

{{% blocks/products/pf/feature-page-code h3="C++ Code for XPS to PDF Conversion" %}}

{{< gist "aspose-com-gists" "e1af0e06639806637acbe94be7b2c76a" "convert-xps-to-pdf.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xps-to-bmp xps-to-png xps-to-tiff xps-to-jpeg" >}}