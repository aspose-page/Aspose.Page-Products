---
title: Java XPS and Encapsulated PostScript Files Conversion
url: /java/conversion/
description: Convert PS, EPS, and XPS to PDF and Images including BMP, JPG, PNG, and TIFF using the Java library with the Aspose.Page PDL conversion functionality.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="PostScript and XPS Files Conversion Via Java" h2="Convert PostScript PS, EPS and XPS to PDF and Images including BMP, PNG, JPEG, TIFF  to build cross-platform Java applications." >}}

{{% blocks/products/pf/feature-page-summary %}}

If we define the PS and EPS files then PostScript (PS) is mainly used for printing purposes and saved in page description language having text, vector graphics and raster images. While EPS is mainly used for images and drawings. Java API can easily convert XPS and PostScript PS, Encapsulated PostScript EPS to PDF and images with high-fidelity and quick rendering. Programmers can easily integrate code as of their conversion requirement.


{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="PostScript to PDF Conversion" %}}

Converting Postscript to PDF documents, process is, Load PS or EPS file using [PsDocument class](https://apireference.aspose.com/page/java/com.aspose.eps/PsDocument). Set the PDF saving options as of requirement using [PdfSaveOptions class](https://apireference.aspose.com/page/java/com.aspose.eps.device/PdfSaveOptions). Use [FileOutputStream](https://docs.oracle.com/javase/7/docs/api/java/io/FileOutputStream.html) for output PDF file. Use [PdfDevice class](https://apireference.aspose.com/page/java/com.aspose.eps.device/PdfDevice) having FileOutputStream object as parameter. Finally call the [save method](https://apireference.aspose.com/page/java/com.aspose.eps/PsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) for saving into PDF file.

{{% blocks/products/pf/feature-page-code h3="Java Code to convert PS EPS to PDF" %}}

{{< gist "aspose-com-gists" "7804c7e1f9f1ded0fc3b504c0a74f611" "postscript-to-pdf-conversion.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ps-to-pdf eps-to-pdf" >}}

{{% blocks/products/pf/feature-page-section  h2="Convert PostScript to Images" %}}

As of API support to PostScript to images conversion, Process is, intialize input stream with PS source file and create [PsDocument](https://apireference.aspose.com/page/java/com.aspose.eps/psdocument) object with created PS input stream as parameter. Use [ImageSaveOptions](https://apireference.aspose.com/page/java/com.aspose.eps.device/imagesaveoptions) to specify AdditionalFontsFolder and SuppressError etc. Use [ImageDevice](https://apireference.aspose.com/page/java/com.aspose.eps.device/imagedevice) object for specifying image type and size if needed. Save PS/EPS file as and image with image save options as an array of arrays of bytes. One array of bytes for one page of input file.

{{% blocks/products/pf/feature-page-code h3="Java Code for PostScript to Images Conversion" %}}

{{< gist "aspose-com-gists" "7804c7e1f9f1ded0fc3b504c0a74f611" "postscript-to-images-conversion.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="ps-to-bmp ps-to-png ps-to-jpeg ps-to-tiff ps-to-gif eps-to-gif eps-to-tiff eps-to-jpeg eps-to-png eps-to-bmp" >}}

{{% blocks/products/pf/feature-page-section  h2="XPS to Images JPG, PNG, BMP Conversion" %}}

Jave API deals XPS format that is used for representing page layout. In any scenario, whenever there is need to convert XPS to images BMP, JPG, PNG, and TIFF programmatically, following code can easily be integrated within Java application. Conversion process is, use [XpsDocument class](https://apireference.aspose.com/page/java/com.aspose.xps/XpsDocument) to load the XPS document. Use the relevant image option class such as  [PngSaveOptions](https://apireference.aspose.com/page/java/com.aspose.xps.rendering/PngSaveOptions), [JpegSaveOptions](https://apireference.aspose.com/page/java/com.aspose.xps.rendering/JpegSaveOptions), [BmpSaveOptions](https://apireference.aspose.com/page/java/com.aspose.xps.rendering/BmpSaveOptions), [TiffSaveOptions](https://apireference.aspose.com/page/java/com.aspose.xps.rendering/TiffSaveOptions) for image additional settings. Create the [image device](https://apireference.aspose.com/page/java/com.aspose.xps.rendering/ImageDevice) class instance. Call the [XpsDocument.save](https://apireference.aspose.com/page/java/com.aspose.xps/XpsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) to save converted JPEG image into ImageDevice object and then use ImageDevice for saving the image as a JPG.

{{% blocks/products/pf/feature-page-code h3="Java Code for XPS to Image Conversion" %}}

{{< gist "aspose-com-gists" "7804c7e1f9f1ded0fc3b504c0a74f611" "xps-to-image-conversion.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xps-to-bmp xps-to-png xps-to-tiff xps-to-jpeg" >}}c

{{% blocks/products/pf/feature-page-section  h2="Convert XPS to PDF" %}}

Process of converting XPS to PDF documents programmatically is simple having high fidelity results among the input and output files. Process is load the file using XpsDocument class. Initialize [PdfSaveOptions class](https://apireference.aspose.com/page/java/com.aspose.xps.rendering/PdfDevice) object and 
create PdfDevice object for rendering and lastly save output PDF document.

{{% blocks/products/pf/feature-page-code h3="Java Code for XPS to PDF Conversion" %}}

{{< gist "aspose-com-gists" "36014fe18885c184d472ae34c0c29750" "XPS-to-PDF.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options pairs="xps-to-pdf" >}}