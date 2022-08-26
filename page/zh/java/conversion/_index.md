---
translation: true
template: /_templates/_conversion-java.md
title: PDL 转换 API | Java
url: /java/conversion/
description: 使用带有 Aspose.Page PDL 转换功能的 Java 库将 PS、EPS 和 XPS 转换为 PDF 和图像，包括 BMP、JPG、PNG 和 TIFF。
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: 转换 PS、EPS 和 XPS
h2: 适用于 Java 的 PS、EPS 和 XPS 转换器 API 解决方案
---

{{<section overview>}}
---
p1: "每当需要以编程方式转换 PostScript PS 和 Encapsulated PostScript EPS 文件以及 XPS 文档时，Java API 都可以顺利完成并转换多个文件。对于 PS 和 EPS，API 支持 1-3 级 PostScript 运算符和大多数 EPS 标题注释以及转换具有最大一致性的 PostScript 文档，除了少数字体情况和 API 处理诸如 Time New Roman 之类的字体。"
p2: "此外，对于 XPS 文件转换，API 可以添加或删除页面，处理画布、路径和字形元素，创建矢量图形、文本字符串，转换 XPS 大纲项等等。"
p3: "此处的 Java API 解决方案允许您以编程方式转换诸如 PS、EPS 和 XPS 等 PDL 格式的文件，但您可能会发现查看和尝试在这些原生 API 上开发的跨平台很有用。"
---

{{<section feature1>}}
---
title: 通过 Java 将 PostScript 转换为 PDF。
h3: "将 PS EPS 转换为 PDF 的 Java 代码"
item1: "要通过 Java API 将 PostScript PS 和 Encapsulated PostScript EPS 文件转换为 PDF，您需要执行以下步骤："
item2: "使用 [*PsDocument Class*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument) 加载 PS 或 EPS 文件。"
item3: "使用 [*PdfSaveOptions Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfSaveOptions) 设置 PDF 保存选项。"
item4: "使用 [*FileStream Class*](https://docs.oracle.com/javase/7/docs/api/java/io/FileOutputStream.html) 输出 PDF 文件。"
item5: "使用具有 FileOutputStream 对象作为参数的 [*PdfDevice Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfDevice)。"
item6: "调用 [*PsDocument.Save*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) 用于将文件保存为 PDF。"
---

{{<section feature2>}}
---
title: 通过 Java 将 PostScript 转换为图像。
h3: "PostScript 到图像转换的 Java 代码"
item1: "对于任何 EPS/PS PostScript 到图像的转换器应用程序，以下 Java 代码运行良好，因此请执行以下步骤："
item2: 使用 PS 源文件初始化输入流。
item3: "使用创建的 PS 输入流作为参数创建 [*PsDocument*](https://reference.aspose.com/page/java/com.aspose.eps/psdocument) 对象"
item4: "使用 [*ImageSaveOptions*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagesaveoptions) 指定 AdditionalFontsFolder 和 SuppressError 等。"
item5: "如果需要，使用 [*ImageDevice*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagedevice) 对象指定图像类型和大小。"
item6: 将 PS/EPS 文件另存为带有图像保存选项的图像作为字节数组的数组。输入文件的一页的一个字节数组。
---


{{<section feature3>}}
---
title: 通过 Java 将 XPS 转换为图像 JPG、PNG、BMP。
h3: XPS 到图像转换的 Java 代码
item1: "Java API 处理用于表示页面布局的 XPS 格式。在任何情况下，只要需要以编程方式将 XPS 转换为 BMP、JPG、PNG 和 TIFF 图像，都可以轻松地将以下代码集成到 Java 应用程序中。"
item2: "使用 [*XpsDocument 类*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument) 加载 XPS 文档。"
item3: "使用相关的图片选项类如[*PngSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PngSaveOptions)、[*JpegSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/JpegSaveOptions)，[*BmpSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/BmpSaveOptions) , [*TiffSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/TiffSaveOptions) 用于图像附加设置。"
item4: "创建 [*image device*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/ImageDevice) 类实例。"
item5: "调用 [*XpsDocument.save*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) 将转换后的 JPEG 图像保存到 ImageDevice 对象中，然后使用 ImageDevice 将图像保存为 JPG。"
---

{{<section feature4>}}
---
title: 通过 Java 将 XPS 转换为 PDF。
h3: XPS 到 PDF 转换的 Java 代码
item1: 以编程方式将 XPS 转换为 PDF 文档的过程很简单，在输入和输出文件之间具有高保真结果。
item2: "使用 XpsDocument 类加载文件。初始化 [*PdfSaveOptions class*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PdfDevice) 对象。"
item3: 创建用于渲染的 PdfDevice 对象，最后保存输出的 PDF 文档。
---


