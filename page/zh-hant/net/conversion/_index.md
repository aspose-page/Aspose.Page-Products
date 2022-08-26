---
translation: true
template: /_templates/_conversion-net.md
title: PDL 轉換 API C# | .NET
url: /net/conversion/
description: 使用具有 Aspose.Page PDL 轉換功能的 .NET 庫將 PS、EPS 和 XPS 轉換為 PDF 和圖像，包括 BMP、JPG、PNG 和 TIFF。
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: 轉換 PS、EPS 和 XPS
h2: 適用於 .NET 的 PS、EPS 和 XPS 轉換器 API 解決方案。
---

{{<section overview>}}
---
p1: "每當需要以編程方式轉換 PostScript PS 和 Encapsulated PostScript EPS 文件以及 XPS 文檔時，.NET API 可以順利完成並轉換多個文件。對於 PS 和 EPS，API 支持 1-3 級 PostScript 運算符和大多數 EPS 標題註釋，以及轉換具有最大一致性的 PostScript 文檔，除了少數字體情況和 API 處理諸如 T​​ime New Roman 之類的字體。"
p2: "此外，對於 XPS 文件轉換，API 可以添加或刪除頁面，處理畫布、路徑和字形元素，創建矢量圖形、文本字符串，轉換 XPS 大綱項等等。"
p3: "此處的 .NET API 解決方案允許您以編程方式轉換諸如 PS、EPS 和 XPS 等 PDL 格式的文件，但您可能會發現查看和嘗試在這些本機 API 上開發的跨平台很有用。"
---

{{<section feature1>}}
---
title: 通過 C# .NET 將 PostScript 轉換為 PDF。
h3: "PS EPS 到 PDF 轉換的 C# 代碼"
item1: "要通過 .NET API 將 PostScript PS 和 Encapsulated PostScript EPS 文件轉換為 PDF，您需要執行以下步驟："
item2: "使用 [*PsDocument Class*](https://reference.aspose.com/page/net/aspose.page.eps/psdocument/) 加載 PS 或 EPS 文件。"
item3: "使用 [*PdfSaveOptions Class*](https://reference.aspose.com/page/net/aspose.page.eps.device/pdfsaveoptions/) 設置 PDF 保存。"
item4: "使用 [*FileStream Class*](https://docs.microsoft.com/en-us/dotnet/api/system.io.filestream) 輸出 PDF 文件。"
item5: "[*PdfDevice Class*](https://reference.aspose.com/page/net/aspose.page.eps.device/pdfdevice/) 通過使用輸出 PDF 文件流對象進行初始化。"
item6: "調用 [*PsDocument.Save*](https://reference.aspose.com/page/net/aspose.page.eps/psdocument/save/) 進行 PDF 轉換。"
---

{{<section feature2>}}
---
title: 通過 C# .NET 將 PostScript 轉換為圖像。
h3: "PostScript 到圖像轉換的 C# 代碼"
item1: "對於任何 EPS/PS PostScript 到圖像轉換器應用程序，以下 C# 代碼運行良好，因此請執行以下步驟："
item2: 使用具有輸入文件流作為參數的 PsDocument 類加載文檔。
item3: "創建 [*ImageSaveOptions Class*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/imagesaveoptions/) 對象並使用所需的設置對其進行初始化。"
item4: 將每個輸入文件頁面保存為圖像 PNG、JPG、TIFF、BMP 等。
---

{{<section feature3>}}
---
title: 通過 C# .NET 將 XPS 轉換為圖像 JPG、PNG、BMP。
h3: "XPS 到圖像轉換的 C# 代碼"
item1: ".NET API 還支持XPS 轉換為圖片BMP、JPG、PNG、TIFF 等，並提供XpsDocument 類進行XPS 操作。要將 XPS 轉換為圖像，請執行以下步驟："
item2: 從流中加載 XPS 文件。
item3: "初始化相關的圖像保存選項，例如 **XPS to JPG** 它是 [*JpegSaveOptions*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions/)對於 **XPS 到 PNG**，它的 [*PngSaveOptions*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions/)。這是所有 XPS 到圖像的列表 [*保存選項*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/)。"
item4: 定義渲染的相關設置，如 SmoothingMode、Resolution 和 PageNumbers 等。最後遍歷文檔分區以將它們保存到圖像中。
---
