---
translation: true
template: /_templates/_conversion-java.md
title: PDL 轉換 API | Java
url: /java/conversion/
description: 使用帶有 Aspose.Page PDL 轉換功能的 Java 庫將 PS、EPS 和 XPS 轉換為 PDF 和圖像，包括 BMP、JPG、PNG 和 TIFF。
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: 轉換 PS、EPS 和 XPS
h2: 適用於 Java 的 PS、EPS 和 XPS 轉換器 API 解決方案
---

{{<section overview>}}
---
p1: "每當需要以編程方式轉換 PostScript PS 和 Encapsulated PostScript EPS 文件以及 XPS 文檔時，Java API 都可以順利完成並轉換多個文件。對於 PS 和 EPS，API 支持 1-3 級 PostScript 運算符和大多數 EPS 標題註釋，以及轉換具有最大一致性的 PostScript 文檔，除了少數字體情況和 API 處理諸如 T​​ime New Roman 之類的字體。"
p2: "此外，對於 XPS 文件轉換，API 可以添加或刪除頁面，處理畫布、路徑和字形元素，創建矢量圖形、文本字符串，轉換 XPS 大綱項等等。"
p3: "此處的 Java API 解決方案允許您以編程方式轉換諸如 PS、EPS 和 XPS 等 PDL 格式的文件，但您可能會發現查看和嘗試在這些原生 API 上開發的跨平台很有用。"
---

{{<section feature1>}}
---
title: 通過 Java 將 PostScript 轉換為 PDF。
h3: "將 PS EPS 轉換為 PDF 的 Java 代碼"
item1: "要通過 Java API 將 PostScript PS 和 Encapsulated PostScript EPS 文件轉換為 PDF，您需要執行以下步驟："
item2: "使用 [*PsDocument Class*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument) 加載 PS 或 EPS 文件。"
item3: "使用 [*PdfSaveOptions Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfSaveOptions) 設置 PDF 保存選項。"
item4: "使用 [*FileStream Class*](https://docs.oracle.com/javase/7/docs/api/java/io/FileOutputStream.html) 輸出 PDF 文件。"
item5: "使用具有 FileOutputStream 對像作為參數的 [*PdfDevice Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfDevice)。"
item6: "調用 [*PsDocument.Save*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) 用於將文件保存為 PDF。"
---

{{<section feature2>}}
---
title: 通過 Java 將 PostScript 轉換為圖像。
h3: "PostScript 到圖像轉換的 Java 代碼"
item1: "對於任何 EPS/PS PostScript 到圖像的轉換器應用程序，以下 Java 代碼運行良好，因此請執行以下步驟："
item2: 使用 PS 源文件初始化輸入流。
item3: "使用創建的 PS 輸入流作為參數創建 [*PsDocument*](https://reference.aspose.com/page/java/com.aspose.eps/psdocument) 對象"
item4: "使用 [*ImageSaveOptions*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagesaveoptions) 指定 AdditionalFontsFolder 和 SuppressError 等。"
item5: "如果需要，使用 [*ImageDevice*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagedevice) 對象指定圖像類型和大小。"
item6: 將 PS/EPS 文件另存為帶有圖像保存選項的圖像作為字節數組的數組。輸入文件的一頁的一個字節數組。
---


{{<section feature3>}}
---
title: 通過 Java 將 XPS 轉換為圖像 JPG、PNG、BMP。
h3: XPS 到圖像轉換的 Java 代碼
item1: "Java API 處理用於表示頁面佈局的 XPS 格式。在任何情況下，只要需要以編程方式將 XPS 轉換為 BMP、JPG、PNG 和 TIFF 圖像，都可以輕鬆地將以下代碼集成到 Java 應用程序中。"
item2: "使用 [*XpsDocument 類*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument) 加載 XPS 文檔。"
item3: "使用相關的圖片選項類如[*PngSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PngSaveOptions)、[*JpegSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/JpegSaveOptions)，[*BmpSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/BmpSaveOptions) , [*TiffSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/TiffSaveOptions) 用於圖像附加設置。"
item4: "創建 [*image device*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/ImageDevice) 類實例。"
item5: "調用 [*XpsDocument.save*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) 將轉換後的 JPEG 圖像保存到 ImageDevice 對像中，然後使用 ImageDevice 將圖像保存為 JPG。"
---

{{<section feature4>}}
---
title: 通過 Java 將 XPS 轉換為 PDF。
h3: XPS 到 PDF 轉換的 Java 代碼
item1: 以編程方式將 XPS 轉換為 PDF 文檔的過程很簡單，在輸入和輸出文件之間具有高保真結果。
item2: "使用 XpsDocument 類加載文件。初始化 [*PdfSaveOptions class*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PdfDevice) 對象。"
item3: 創建用於渲染的 PdfDevice 對象，最後保存輸出的 PDF 文檔。
---


