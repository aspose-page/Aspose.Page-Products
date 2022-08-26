---
translation: true
template: /_templates/_conversion-net.md
title: PDL 转换 API C# | .NET
url: /net/conversion/
description: 使用具有 Aspose.Page PDL 转换功能的 .NET 库将 PS、EPS 和 XPS 转换为 PDF 和图像，包括 BMP、JPG、PNG 和 TIFF。
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: 转换 PS、EPS 和 XPS
h2: 适用于 .NET 的 PS、EPS 和 XPS 转换器 API 解决方案。
---

{{<section overview>}}
---
p1: "每当需要以编程方式转换 PostScript PS 和 Encapsulated PostScript EPS 文件以及 XPS 文档时，.NET API 可以顺利完成并转换多个文件。对于 PS 和 EPS，API 支持 1-3 级 PostScript 运算符和大多数 EPS 标题注释，以及转换具有最大一致性的 PostScript 文档，除了少数字体情况和 API 处理诸如 Time New Roman 之类的字体。"
p2: "此外，对于 XPS 文件转换，API 可以添加或删除页面，处理画布、路径和字形元素，创建矢量图形、文本字符串，转换 XPS 大纲项等等。"
p3: "此处的 .NET API 解决方案允许您以编程方式转换诸如 PS、EPS 和 XPS 等 PDL 格式的文件，但您可能会发现查看和尝试在这些本机 API 上开发的跨平台很有用。"
---

{{<section feature1>}}
---
title: 通过 C# .NET 将 PostScript 转换为 PDF。
h3: "PS EPS 到 PDF 转换的 C# 代码"
item1: "要通过 .NET API 将 PostScript PS 和 Encapsulated PostScript EPS 文件转换为 PDF，您需要执行以下步骤："
item2: "使用 [*PsDocument Class*](https://reference.aspose.com/page/net/aspose.page.eps/psdocument/) 加载 PS 或 EPS 文件。"
item3: "使用 [*PdfSaveOptions Class*](https://reference.aspose.com/page/net/aspose.page.eps.device/pdfsaveoptions/) 设置 PDF 保存。"
item4: "使用 [*FileStream Class*](https://docs.microsoft.com/en-us/dotnet/api/system.io.filestream) 输出 PDF 文件。"
item5: "[*PdfDevice Class*](https://reference.aspose.com/page/net/aspose.page.eps.device/pdfdevice/) 通过使用输出 PDF 文件流对象进行初始化。"
item6: "调用 [*PsDocument.Save*](https://reference.aspose.com/page/net/aspose.page.eps/psdocument/save/) 进行 PDF 转换。"
---

{{<section feature2>}}
---
title: 通过 C# .NET 将 PostScript 转换为图像。
h3: "PostScript 到图像转换的 C# 代码"
item1: "对于任何 EPS/PS PostScript 到图像转换器应用程序，以下 C# 代码运行良好，因此请执行以下步骤："
item2: 使用具有输入文件流作为参数的 PsDocument 类加载文档。
item3: "创建 [*ImageSaveOptions Class*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/imagesaveoptions/) 对象并使用所需的设置对其进行初始化。"
item4: 将每个输入文件页面保存为图像 PNG、JPG、TIFF、BMP 等。
---

{{<section feature3>}}
---
title: 通过 C# .NET 将 XPS 转换为图像 JPG、PNG、BMP。
h3: "XPS 到图像转换的 C# 代码"
item1: ".NET API 还支持XPS 转换为图片BMP、JPG、PNG、TIFF 等，并提供XpsDocument 类进行XPS 操作。要将 XPS 转换为图像，请执行以下步骤："
item2: 从流中加载 XPS 文件。
item3: "初始化相关的图像保存选项，例如 **XPS to JPG** 它是 [*JpegSaveOptions*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions/)对于 **XPS 到 PNG**，它的 [*PngSaveOptions*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions/)。这是所有 XPS 到图像的列表 [*保存选项*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/)。"
item4: 定义渲染的相关设置，如 SmoothingMode、Resolution 和 PageNumbers 等。最后遍历文档分区以将它们保存到图像中。
---
