---
translation: true
template: /_templates/_conversion-cpp.md
title: Interfejs API konwersji PDL | C++
url: /cpp/conversion/
description: Konwertuj pliki PS, EPS i XPS na pliki PDF i obrazy, w tym BMP, JPG, PNG i TIFF, korzystając z biblioteki C++ z funkcją konwersji Aspose.Page PDL.
family: page
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: Konwertuj PS, EPS i XPS
h2: Rozwiązanie API konwertera PS, EPS i XPS dla C++.
---

{{<section overview>}}
---
p1: "Zawsze, gdy zachodzi potrzeba programowej konwersji plików PostScript PS i Encapsulated PostScript EPS, a także dokumentów XPS, Java API może to zrobić płynnie i konwertować wiele plików. W przypadku PS i EPS API obsługuje operatory PostScript poziomu 1-3 i większość komentarzy nagłówka EPS, a także przekształca dokumenty PostScript z maksymalną zgodnością z wyjątkiem kilku przypadków czcionek, a API obsługuje takie czcionki, jak Time New Roman."
p2: "Programiści mogą z łatwością używać go do przetwarzania wsadowego dokumentów PostScript i XPS, a nawet manipulować płótnami, ścieżkami i elementami glifów oraz obsługiwać kształty grafiki wektorowej i ciągi tekstowe."
p3: "Rozwiązanie API dla Javy umożliwia programową konwersję plików w takich formatach PDL, jak PS, EPS i XPS, ale może okazać się przydatne zobaczenie i wypróbowanie wieloplatformowości opracowanej na tych natywnych interfejsach API. Oto kilka scenariuszy konwersji, takich jak EPS na obrazy, EPS na PDF, PostScript na PDF, PostScript na obrazy, XPS na obrazy i XPS na PDF"
---

{{<section feature1>}}
---
title: Konwertuj EPS na obrazy za pomocą C++.
h3: Kod C++ do konwersji plików EPS na obrazy
item1: "Biblioteka C++ umożliwia konwersję plików Encapsulated PostScript (EPS) na obrazy na platformach Windows i Linux. Proces to:"
item2: "Użyj FileStream, aby utworzyć strumień wejściowy dla pliku EPS, a także utworzyć obiekt [*PsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.ps_document) ze strumieniem wejściowym jako parametr. W przypadku ustawień dotyczących obrazów użyj [*ImageSaveOptions Class*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_save_options)."
item3: "Zdefiniuj typ i rozmiar obrazu za pomocą [*ImageDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_device)."
item4: Zapisz EPS jako obrazy z opcjami zapisywania obrazu do tablicy tablic bajtów, tworząc dla każdej tablicy bajtów nowy strumień wyjściowy pliku.
---


{{<section feature2>}}
---
title: Konwersja PostScript do PDF przez Java.
h3: Kod C++ do konwersji PostScript na PDF
item1: "Proces konwersji PostScript do PDF jest taki sam jak EPS do obrazów, z wyjątkiem tego, że programiści będą używać [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_save_options), aby zdefiniować dodatkowe ustawienia, takie jak wartość AdditionalFontsFolder i SuppressError itp. Ponadto użyje [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_device) z utworzonego strumienia wyjściowego."
---

{{<section feature3>}}
---
title: Konwertuj XPS na PDF za pomocą C++.
h3: Kod C++ do konwersji XPS na PDF
item1: "C++ XPS Processing API zajmuje się konwersją XPS do obrazów, w tym BMP, JPG, TIFF, PNG i innych, a także konwersją XPS do PDF w systemach Windows i Linux. Proces konwersji XPS na PDF to:"
item2: Zdefiniuj strumień wyjściowy oraz strumień wejściowy dla wejściowego dokumentu XPS.
item3: "Przekaż go jako parametr do [*XpsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.xps_document) obiektu."
item4: "Określ opcje zapisywania plików PDF, takie jak TextCompression, ImageCompression i JpegQualityLevel, używając [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_save_options)."
item5: "Utwórz wystąpienie [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_device) z utworzonego wcześniej strumienia wyjściowego."
item6: Na koniec przekonwertuj dokument XPS na PDF z opcjami zapisywania PDF.
---
