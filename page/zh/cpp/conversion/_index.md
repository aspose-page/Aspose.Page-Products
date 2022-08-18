---
translation: true
template: /_templates/_conversion-cpp.md
title: PDL 转换 API | C++
url: /cpp/conversion/
description: 使用带有 Aspose.Page PDL 转换功能的 C++ 库将 PS、EPS 和 XPS 转换为 PDF 和图像，包括 BMP、JPG、PNG 和 TIFF。
family: page
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: 转换 PS、EPS 和 XPS
h2: 适用于 C++ 的 PS、EPS 和 XPS 转换器 API 解决方案。
---

{{<section overview>}}
---
p1: "每当需要以编程方式转换 PostScript PS 和 Encapsulated PostScript EPS 文件以及 XPS 文档时，Java API 都可以顺利完成并转换多个文件。对于 PS 和 EPS，API 支持 1-3 级 PostScript 运算符和大多数 EPS 标题注释以及转换具有最大一致性的 PostScript 文档，除了少数字体情况和 API 处理诸如 Time New Roman 之类的字体。"
p2: "程序员可以轻松地使用它对 PostScript 和 XPS 文档进行批处理，甚至可以操作画布、路径和字形元素以及处理矢量图形和文本字符串。"
p3: "此处的 Java API 解决方案允许您以编程方式转换诸如 PS、EPS 和 XPS 等 PDL 格式的文件，但您可能会发现查看和尝试在这些原生 API 上开发的跨平台很有用。这里有几个转换场景，例如 EPS 转图像、EPS 转 PDF、PostScript 转 PDF、PostScript 转图像、XPS 转图像和 XPS 转 PDF"
---

{{<section feature1>}}
---
title: 通过 C++ 将 EPS 转换为图像。
h3: EPS 到图像转换的 C++ 代码
item1: "C++ 库允许在 Windows 和 Linux 平台上将 Encapsulated PostScript (EPS) 文件转换为图像。过程是："
item2: "使用 FileStream 为 EPS 文件创建输入流以及创建具有输入流的 [*PsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.ps_document) 对象作为参数。对于图像特定设置，请使用 [*ImageSaveOptions Class*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_save_options)。"
item3: "使用 [*ImageDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_device) 定义图像类型和大小。"
item4: 将 EPS 保存为带有图像保存选项的图像到字节数组中，为每个字节数组创建一个新的文件输出流。
---


{{<section feature2>}}
---
title: 通过 Java 将 PostScript 转换为 PDF。
h3: PostScript 到 PDF 转换的 C++ 代码
item1: "PostScript转PDF的过程和EPS转Image的过程一样，只是开发者会使用[*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_save_options) 来定义附加设置，例如 AdditionalFontsFolder 和 SuppressError 值等。此外，将使用 [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_device) 从创建的输出流。"
---

{{<section feature3>}}
---
title: 通过 C++ 将 XPS 转换为 PDF。
h3: XPS 到 PDF 转换的 C++ 代码
item1: "C++ XPS 处理 API 处理 XPS 到图像的转换，包括 BMP、JPG、TIFF、PNG 等，以及在基于 Windows 和 Linux 的系统上将 XPS 转换为 PDF。 XPS转PDF的过程是："
item2: 定义输出流以及定义输入 XPS 文档的输入流。
item3: "将其作为参数传递给 [*XpsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.xps_document) 对象。"
item4: "使用 [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_save_options) 指定 PDF 特定的保存选项，例如 TextCompression、ImageCompression 和 JpegQualityLevel。"
item5: "从之前创建的输出流创建 [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_device) 的实例。"
item6: 最后使用 PDF 保存选项将 XPS 文档转换为 PDF。
---
