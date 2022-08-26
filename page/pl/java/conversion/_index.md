---
translation: true
template: /_templates/_conversion-java.md
title: Interfejs API konwersji PDL | Java
url: /java/conversion/
description: Konwertuj pliki PS, EPS i XPS na pliki PDF i obrazy, w tym BMP, JPG, PNG i TIFF, korzystając z biblioteki Java z funkcją konwersji Aspose.Page PDL.
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: Konwertuj PS, EPS i XPS
h2: Konwerter PS, EPS i XPS Rozwiązanie API dla Java
---

{{<section overview>}}
---
p1: "Zawsze, gdy zachodzi potrzeba programowej konwersji plików PostScript PS i Encapsulated PostScript EPS, a także dokumentów XPS, Java API może to zrobić płynnie i konwertować wiele plików. W przypadku PS i EPS API obsługuje operatory PostScript poziomu 1-3 i większość komentarzy nagłówka EPS, a także przekształca dokumenty PostScript z maksymalną zgodnością z wyjątkiem kilku przypadków czcionek, a API obsługuje takie czcionki, jak Time New Roman."
p2: "Co więcej, w przypadku transformacji plików XPS, API może dodawać lub usuwać strony, radzić sobie z elementami kanwy, ścieżek i glifów, tworzyć kształty grafiki wektorowej, ciągi tekstowe, konwertować elementy konturu XPS i nie tylko."
p3: "Rozwiązanie API dla Javy umożliwia programową konwersję plików w takich formatach PDL, jak PS, EPS i XPS, ale przydatne może być obejrzenie i wypróbowanie wieloplatformowych rozwiązań opracowanych na tych natywnych interfejsach API."
---

{{<section feature1>}}
---
title: Konwersja PostScript do PDF przez Java.
h3: "Kod Java do konwersji PS EPS na PDF"
item1: "Aby przekonwertować pliki PostScript PS i Encapsulated PostScript EPS do formatu PDF za pośrednictwem interfejsu Java API, należy wykonać następujące kroki:"
item2: "Załaduj plik PS lub EPS przy użyciu [*PsDocument Class*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument)."
item3: "Ustaw opcje zapisywania PDF za pomocą [*PdfSaveOptions Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfSaveOptions)."
item4: "Użyj [*FileStream Class*](https://docs.oracle.com/javase/7/docs/api/java/io/FileOutputStream.html) dla wyjściowego pliku PDF."
item5: "Użyj [*PdfDevice Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfDevice) z obiektem FileOutputStream jako parametrem."
item6: "Wywołaj [*PsDocument.Save*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) do zapisania pliku w formacie PDF."
---

{{<section feature2>}}
---
title: Konwersja PostScript do obrazów za pomocą języka Java.
h3: "Kod Java do konwersji PostScript na obrazy"
item1: "W przypadku dowolnej aplikacji konwertującej pliki EPS/PS PostScript na obraz następujący kod Java działa dobrze, więc wykonaj następujące kroki:"
item2: Zainicjuj strumień wejściowy za pomocą pliku źródłowego PS.
item3: "Utwórz obiekt [*PsDocument*](https://reference.aspose.com/page/java/com.aspose.eps/psdocument) z utworzonym strumieniem wejściowym PS jako parametrem"
item4: "Użyj [*ImageSaveOptions*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagesaveoptions), aby określić AdditionalFontsFolder i SuppressError itp."
item5: "W razie potrzeby użyj obiektu [*ImageDevice*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagedevice) do określenia typu i rozmiaru obrazu."
item6: Zapisz plik PS/EPS jako i obraz z opcjami zapisywania obrazu jako tablica tablic bajtów. Jedna tablica bajtów na jedną stronę pliku wejściowego.
---


{{<section feature3>}}
---
title: Konwertuj XPS na obrazy JPG, PNG, BMP za pomocą Javy.
h3: Kod Java dla konwersji XPS na obraz
item1: "Java API obsługuje format XPS używany do reprezentowania układu strony. W każdym przypadku, gdy zachodzi potrzeba programowej konwersji XPS na obrazy BMP, JPG, PNG i TIFF, poniższy kod można łatwo zintegrować z aplikacją Java."
item2: "Użyj [*XpsDocument class*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument), aby załadować dokument XPS."
item3: "Użyj odpowiedniej klasy opcji obrazu, takiej jak [*PngSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PngSaveOptions), [*JpegSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/JpegSaveOptions), [*BmpSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/BmpSaveOptions) , [*TiffSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/TiffSaveOptions) dla dodatkowych ustawień obrazu."
item4: "Utwórz instancję klasy [*image device*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/ImageDevice)."
item5: "Wywołaj [*XpsDocument.save*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-), aby zapisać przekonwertowany obraz JPEG do obiektu ImageDevice, a następnie użyć ImageDevice do zapisania obrazu jako JPG."
---

{{<section feature4>}}
---
title: Konwertuj XPS na PDF za pomocą Javy.
h3: Kod Java do konwersji XPS na PDF
item1: Proces programowej konwersji dokumentów XPS na PDF jest prosty i zapewnia wysoką wierność wyników między plikami wejściowymi i wyjściowymi.
item2: "Załaduj plik za pomocą klasy XpsDocument. Zainicjuj obiekt [*PdfSaveOptions class*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PdfDevice)."
item3: Utwórz obiekt PdfDevice do renderowania i na koniec zapisz wyjściowy dokument PDF.
---


