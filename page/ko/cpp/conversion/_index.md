---
translation: true
template: /_templates/_conversion-cpp.md
title: PDL 변환 API | C++
url: /cpp/conversion/
description: Aspose.Page PDL 변환 기능이 있는 C++ 라이브러리를 사용하여 PS, EPS 및 XPS를 BMP, JPG, PNG 및 TIFF를 포함한 PDF 및 이미지로 변환합니다.
family: page
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: PS, EPS 및 XPS 변환
h2: C++용 PS, EPS 및 XPS 변환기 API 솔루션.
---

{{<section overview>}}
---
p1: "PostScript PS 및 Encapsulated PostScript EPS 파일 및 XPS 문서를 프로그래밍 방식으로 변환해야 할 때마다 Java API는 이를 원활하게 수행하고 여러 파일을 변환할 수 있습니다. PS 및 EPS의 경우 API는 레벨 1-3 PostScript 연산자와 대부분의 EPS 헤더 주석을 지원하며 일부 글꼴의 경우를 제외하고 최대 적합성을 갖는 PostScript 문서를 변환하고 API는 Time New Roman과 같은 글꼴을 취급합니다."
p2: "프로그래머는 PostScript 및 XPS 문서의 일괄 처리에 쉽게 사용할 수 있으며 캔버스, 경로 및 글리프 요소를 조작하고 벡터 그래픽 모양 및 텍스트 문자열을 처리할 수도 있습니다."
p3: "여기에서 Java용 API 솔루션을 사용하면 PS, EPS 및 XPS와 같은 PDL 형식의 파일을 프로그래밍 방식으로 변환할 수 있지만 이러한 기본 API에서 개발된 교차 플랫폼을 보고 시도하는 것이 유용할 수 있습니다. 다음은 EPS를 이미지로, EPS를 PDF로, PostScript를 PDF로, PostScript를 이미지로, XPS를 이미지로, XPS를 PDF로 변환하는 몇 가지 시나리오입니다."
---

{{<section feature1>}}
---
title: C++를 통해 EPS를 이미지로 변환합니다.
h3: EPS에서 이미지로의 변환을 위한 C++ 코드
item1: "C++ 라이브러리를 사용하면 EPS(Encapsulated PostScript) 파일을 Windows 및 Linux 플랫폼에서 이미지로 변환할 수 있습니다. 프로세스는 다음과 같습니다."
item2: "FileStream을 사용하여 EPS 파일에 대한 입력 스트림을 생성하고 입력 스트림이 있는 [*PsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.ps_document) 객체를 생성합니다. 매개변수로. 이미지 관련 설정의 경우 [*ImageSaveOptions Class*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_save_options)를 사용하세요."
item3: "[*ImageDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_device)를 사용하여 이미지 유형과 크기를 정의합니다."
item4: 모든 바이트 배열에 대해 새 파일 출력 스트림을 생성하는 바이트 배열 배열에 이미지 저장 옵션을 사용하여 EPS를 이미지로 저장합니다.
---


{{<section feature2>}}
---
title: Java를 통한 PostScript에서 PDF로의 변환.
h3: PostScript에서 PDF로의 변환을 위한 C++ 코드
item1: "PostScript를 PDF로 변환하는 프로세스는 EPS에서 이미지로 변환하는 과정과 동일하지만 개발자는 [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device)를 사용하여 AdditionalFontsFolder 및 SuppressError 값 등과 같은 추가 설정을 정의합니다. 또한 생성된 출력 스트림에서 [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_device)를 사용합니다."
---

{{<section feature3>}}
---
title: C++를 통해 XPS를 PDF로 변환합니다.
h3: XPS에서 PDF로의 변환을 위한 C++ 코드
item1: "C++ XPS 처리 API는 Windows 및 Linux 기반 시스템에서 XPS를 BMP, JPG, TIFF, PNG 등을 포함한 이미지로 변환하고 XPS에서 PDF로 변환하는 작업을 처리합니다. XPS를 PDF로 변환하는 과정은 다음과 같습니다."
item2: 출력 스트림을 정의하고 입력 XPS 문서에 대한 입력 스트림을 정의합니다.
item3: "[*XpsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.xps_document) 개체에 매개변수로 전달합니다."
item4: "[*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_save_options)를 사용하여 TextCompression, ImageCompression 및 JpegQualityLevel과 같은 PDF 특정 저장 옵션을 지정합니다."
item5: "생성된 이전 출력 스트림에서 [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_device)의 인스턴스를 생성합니다."
item6: 마지막으로 PDF 저장 옵션을 사용하여 XPS 문서를 PDF로 변환합니다.
---
