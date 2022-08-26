---
translation: true
template: /_templates/_conversion-java.md
title: PDL 변환 API | Java
url: /java/conversion/
description: Aspose.Page PDL 변환 기능이 있는 Java 라이브러리를 사용하여 PS, EPS 및 XPS를 BMP, JPG, PNG 및 TIFF를 포함한 PDF 및 이미지로 변환합니다.
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: PS, EPS 및 XPS 변환
h2: Java용 PS, EPS 및 XPS 변환기 API 솔루션
---

{{<section overview>}}
---
p1: "PostScript PS 및 Encapsulated PostScript EPS 파일 및 XPS 문서를 프로그래밍 방식으로 변환해야 할 때마다 Java API는 이를 원활하게 수행하고 여러 파일을 변환할 수 있습니다. PS 및 EPS의 경우 API는 레벨 1-3 PostScript 연산자와 대부분의 EPS 헤더 주석을 지원하며 일부 글꼴 케이스와 API가 Time New Roman과 같은 글꼴을 취급하는 것을 제외하고 최대한 일치하는 PostScript 문서를 변환합니다."
p2: "또한 XPS 파일 변환의 경우 API는 페이지 추가 또는 제거, 캔버스, 경로 및 글리프 요소 처리, 벡터 그래픽 모양, 텍스트 문자열 생성, XPS 개요 항목 변환 등을 수행할 수 있습니다."
p3: "여기에서 Java용 API 솔루션을 사용하면 PS, EPS 및 XPS와 같은 PDL 형식의 파일을 프로그래밍 방식으로 변환할 수 있지만 이러한 기본 API에서 개발된 교차 플랫폼을 보고 시도하는 것이 유용할 수 있습니다."
---

{{<section feature1>}}
---
title: Java를 통한 PostScript에서 PDF로의 변환.
h3: "PS EPS를 PDF로 변환하는 Java 코드"
item1: "Java API를 통해 PostScript PS 및 Encapsulated PostScript EPS 파일을 PDF로 변환하려면 다음 단계를 수행해야 합니다."
item2: "[*PsDocument Class*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument)를 사용하여 PS 또는 EPS 파일을 로드합니다."
item3: "[*PdfSaveOptions Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfSaveOptions)를 사용하여 PDF 저장 옵션을 설정합니다."
item4: "출력 PDF 파일은 [*FileStream Class*](https://docs.oracle.com/javase/7/docs/api/java/io/FileOutputStream.html)를 사용하십시오."
item5: "FileOutputStream 객체를 파라미터로 갖는 [*PdfDevice Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfDevice)를 사용합니다."
item6: "[*PsDocument.Save*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) 파일을 PDF로 저장합니다."
---

{{<section feature2>}}
---
title: Java를 통한 PostScript에서 이미지로의 변환.
h3: "PostScript에서 이미지로의 변환을 위한 Java 코드"
item1: "EPS/PS PostScript-이미지 변환기 응용 프로그램의 경우 다음 Java 코드가 잘 작동하므로 다음 단계를 수행하십시오."
item2: PS 소스 파일로 입력 스트림을 초기화합니다.
item3: "생성된 PS 입력 스트림을 매개변수로 사용하여 [*PsDocument*](https://reference.aspose.com/page/java/com.aspose.eps/psdocument) 객체 생성"
item4: "[*ImageSaveOptions*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagesaveoptions)를 사용하여 AdditionalFontsFolder 및 SuppressError 등을 지정합니다."
item5: "필요한 경우 이미지 유형 및 크기를 지정하기 위해 [*ImageDevice*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagedevice) 개체를 사용합니다."
item6: PS/EPS 파일을 바이트 배열로 저장하고 이미지 저장 옵션이 있는 이미지를 저장합니다. 입력 파일의 한 페이지에 대한 하나의 바이트 배열입니다.
---


{{<section feature3>}}
---
title: Java를 통해 XPS를 이미지 JPG, PNG, BMP로 변환합니다.
h3: XPS를 이미지로 변환하는 Java 코드
item1: "Java API는 페이지 레이아웃을 나타내는 데 사용되는 XPS 형식을 다룹니다. 어떤 시나리오에서든 XPS를 프로그래밍 방식으로 이미지 BMP, JPG, PNG 및 TIFF로 변환해야 할 때마다 다음 코드를 Java 애플리케이션에 쉽게 통합할 수 있습니다."
item2: "[*XpsDocument 클래스*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument)를 사용하여 XPS 문서를 로드합니다."
item3: "[*PngSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PngSaveOptions), [*JpegSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/JpegSaveOptions) 와 같은 관련 이미지 옵션 클래스를 사용합니다, [*BmpSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/BmpSaveOptions) , 이미지 추가 설정은 [*TiffSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/TiffSaveOptions)를 참조하세요."
item4: "[*이미지 장치*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/ImageDevice) 클래스 인스턴스를 만듭니다."
item5: "[*XpsDocument.save*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) 변환된 JPEG 이미지를 ImageDevice 객체에 저장한 다음 ImageDevice를 사용하여 이미지를 JPG로 저장합니다."
---

{{<section feature4>}}
---
title: Java를 통해 XPS를 PDF로 변환합니다.
h3: XPS에서 PDF로의 변환을 위한 Java 코드
item1: 프로그래밍 방식으로 XPS를 PDF 문서로 변환하는 프로세스는 입력 및 출력 파일 간에 높은 충실도 결과를 갖는 간단합니다.
item2: "XpsDocument 클래스를 사용하여 파일을 로드합니다. [*PdfSaveOptions class*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PdfDevice) 개체를 초기화합니다."
item3: 렌더링을 위한 PdfDevice 개체를 만들고 마지막으로 출력 PDF 문서를 저장합니다.
---


