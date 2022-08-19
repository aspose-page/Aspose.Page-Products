---
translation: true
template: /_templates/_conversion-net.md
title: PDL 변환 API C# | .NET
url: /net/conversion/
description: Aspose.Page PDL 변환 기능이 있는 .NET 라이브러리를 사용하여 PS, EPS 및 XPS를 BMP, JPG, PNG 및 TIFF를 포함한 PDF 및 이미지로 변환합니다.
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: PS, EPS 및 XPS 변환
h2: .NET용 PS, EPS 및 XPS 변환기 API 솔루션.
---

{{<section overview>}}
---
p1: "PostScript PS 및 Encapsulated PostScript EPS 파일은 물론 XPS 문서를 프로그래밍 방식으로 변환해야 할 때마다 .NET API는 이를 원활하게 수행하고 여러 파일을 변환할 수 있습니다. PS 및 EPS의 경우 API는 레벨 1-3 PostScript 연산자와 대부분의 EPS 헤더 주석을 지원하며 일부 글꼴 케이스를 제외하고 최대 적합성을 갖는 PostScript 문서를 변환하고 API는 Time New Roman과 같은 글꼴을 취급합니다."
p2: "또한 XPS 파일 변환의 경우 API는 페이지 추가 또는 제거, 캔버스, 경로 및 글리프 요소 처리, 벡터 그래픽 모양, 텍스트 문자열 생성, XPS 개요 항목 변환 등을 수행할 수 있습니다."
p3: "여기 .NET용 API 솔루션을 사용하면 PS, EPS 및 XPS와 같은 PDL 형식의 파일을 프로그래밍 방식으로 변환할 수 있지만 이러한 기본 API에서 개발된 교차 플랫폼을 보고 시도하는 것이 유용할 수 있습니다."
---

{{<section feature1>}}
---
title: C# .NET을 통한 PostScript에서 PDF로의 변환.
h3: "PS EPS에서 PDF로의 변환을 위한 C# 코드"
item1: ".NET API를 통해 PostScript PS 및 Encapsulated PostScript EPS 파일을 PDF로 변환하려면 다음 단계를 수행해야 합니다."
item2: "[*PsDocument Class*](https://reference.aspose.com/page/net/aspose.page.eps/psdocument/)를 사용하여 PS 또는 EPS 파일을 로드합니다."
item3: "[*PdfSaveOptions Class*](https://reference.aspose.com/page/net/aspose.page.eps.device/pdfsaveoptions/)를 사용하여 PDF 저장을 설정합니다."
item4: "출력 PDF 파일에는 [*FileStream 클래스*](https://docs.microsoft.com/en-us/dotnet/api/system.io.filestream)를 사용합니다."
item5: "[*PdfDevice Class*](https://reference.aspose.com/page/net/aspose.page.eps.device/pdfdevice/) 출력 PDF 파일 스트림 개체로 초기화합니다."
item6: "PDF 변환을 위해 [*PsDocument.Save*](https://reference.aspose.com/page/net/aspose.page.eps/psdocument/save/)를 호출하십시오."
---

{{<section feature2>}}
---
title: C# .NET을 통한 PostScript에서 이미지로의 변환.
h3: "PostScript에서 이미지로의 변환을 위한 C# 코드"
item1: "EPS/PS PostScript-이미지 변환기 응용 프로그램의 경우 다음 C# 코드가 잘 작동하므로 다음 단계를 수행하십시오."
item2: 입력 파일 스트림을 매개변수로 하는 PsDocument 클래스를 사용하여 문서를 로드합니다.
item3: "[*ImageSaveOptions Class*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/imagesaveoptions/) 객체를 생성하고 필요한 설정으로 초기화합니다."
item4: 각 입력 파일 페이지를 이미지 PNG, JPG, TIFF, BMP 등으로 저장합니다.
---

{{<section feature3>}}
---
title: C# .NET을 통해 XPS를 이미지 JPG, PNG, BMP로 변환합니다.
h3: "XPS를 이미지로 변환하는 C# 코드"
item1: ".NET API는 또한 이미지 BMP, JPG, PNG, TIFF 등으로 XPS 변환을 지원하고 XPS 작업을 위한 XpsDocument 클래스를 제공합니다. XPS를 이미지로 변환하려면 다음 단계를 따르세요."
item2: 스트림에서 XPS 파일을 로드합니다.
item3: "관련 이미지 저장 옵션을 초기화합니다(예: **XPS에서 JPG로 **)는 [*JpegSaveOptions*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions/)입니다. **XPS에서 PNG**의 경우 [*PngSaveOptions*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions/). 다음은 이미지에 대한 모든 XPS의 목록입니다[*저장 옵션*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/)."
item4: 렌더링을 위해 SmoothingMode, Resolution, PageNumbers 등과 같은 관련 설정을 정의합니다. 마지막으로 문서 파티션을 반복하여 이미지에 저장합니다.
---
