---
translation: true
template: /_templates/_conversion-cpp.md
title: PDL 轉換 API | C++
url: /cpp/conversion/
description: 使用帶有 Aspose.Page PDL 轉換功能的 C++ 庫將 PS、EPS 和 XPS 轉換為 PDF 和圖像，包括 BMP、JPG、PNG 和 TIFF。
family: page
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: 轉換 PS、EPS 和 XPS
h2: 適用於 C++ 的 PS、EPS 和 XPS 轉換器 API 解決方案。
---

{{<section overview>}}
---
p1: "每當需要以編程方式轉換 PostScript PS 和 Encapsulated PostScript EPS 文件以及 XPS 文檔時，Java API 都可以順利完成並轉換多個文件。對於 PS 和 EPS，API 支持 1-3 級 PostScript 運算符和大多數 EPS 標題註釋，以及轉換具有最大一致性的 PostScript 文檔，除了少數字體情況和 API 處理諸如 T​​ime New Roman 之類的字體。"
p2: "程序員可以輕鬆地使用它對 PostScript 和 XPS 文檔進行批處理，甚至可以操作畫布、路徑和字形元素以及處理矢量圖形和文本字符串。"
p3: "此處的 Java API 解決方案允許您以編程方式轉換諸如 PS、EPS 和 XPS 等 PDL 格式的文件，但您可能會發現查看和嘗試在這些原生 API 上開發的跨平台很有用。這裡有幾個轉換場景，例如 EPS 轉圖像、EPS 轉 PDF、PostScript 轉 PDF、PostScript 轉圖像、XPS 轉圖像和 XPS 轉 PDF"
---

{{<section feature1>}}
---
title: 通過 C++ 將 EPS 轉換為圖像。
h3: EPS 到圖像轉換的 C++ 代碼
item1: "C++ 庫允許在 Windows 和 Linux 平台上將 Encapsulated PostScript (EPS) 文件轉換為圖像。過程是："
item2: "使用 FileStream 為 EPS 文件創建輸入流以及創建具有輸入流的 [*PsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.ps_document) 對象作為參數。對於圖像特定設置，請使用 [*ImageSaveOptions Class*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_save_options)。"
item3: "使用 [*ImageDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_device) 定義圖像類型和大小。"
item4: 將 EPS 保存為帶有圖像保存選項的圖像到字節數組中，為每個字節數組創建一個新的文件輸出流。
---


{{<section feature2>}}
---
title: 通過 Java 將 PostScript 轉換為 PDF。
h3: PostScript 到 PDF 轉換的 C++ 代碼
item1: "PostScript轉PDF的過程和EPS轉Image的過程一樣，只是開發者會使用[*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_save_options) 來定義附加設置，例如 AdditionalFontsFolder 和 SuppressError 值等。此外，將使用 [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_device) 從創建的輸出流。"
---

{{<section feature3>}}
---
title: 通過 C++ 將 XPS 轉換為 PDF。
h3: XPS 到 PDF 轉換的 C++ 代碼
item1: "C++ XPS 處理 API 處理 XPS 到圖像的轉換，包括 BMP、JPG、TIFF、PNG 等，以及在基於 Windows 和 Linux 的系統上將 XPS 轉換為 PDF。 XPS轉PDF的過程是："
item2: 定義輸出流以及定義輸入 XPS 文檔的輸入流。
item3: "將其作為參數傳遞給 [*XpsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.xps_document) 對象。"
item4: "使用 [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_save_options) 指定 PDF 特定的保存選項，例如 TextCompression、ImageCompression 和 JpegQualityLevel。"
item5: "從之前創建的輸出流創建 [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_device) 的實例。"
item6: 最後使用 PDF 保存選項將 XPS 文檔轉換為 PDF。
---
