---
translation: true
template: /_templates/_conversion-net.md
title: Interfejs API konwersji PDL C# | .NET
url: /net/conversion/
description: Konwertuj pliki PS, EPS i XPS na pliki PDF i obrazy, w tym BMP, JPG, PNG i TIFF, korzystając z biblioteki .NET z funkcją konwersji Aspose.Page PDL.
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: Konwertuj PS, EPS i XPS
h2: Rozwiązanie API konwertera PS, EPS i XPS dla platformy .NET.
---

{{<section overview>}}
---
p1: "Ilekroć zachodzi potrzeba programowej konwersji plików PostScript PS i Encapsulated PostScript EPS, a także dokumentów XPS, .NET API może to zrobić płynnie i konwertować wiele plików. W przypadku PS i EPS API obsługuje operatory PostScript poziomu 1-3 i większość komentarzy nagłówka EPS, a także przekształca dokumenty PostScript z maksymalną zgodnością z wyjątkiem kilku przypadków czcionek, a API obsługuje takie czcionki, jak Time New Roman."
p2: "Co więcej, w przypadku transformacji plików XPS, API może dodawać lub usuwać strony, radzić sobie z elementami kanwy, ścieżek i glifów, tworzyć kształty grafiki wektorowej, ciągi tekstowe, konwertować elementy konturu XPS i nie tylko."
p3: "Rozwiązanie API dla platformy .NET umożliwia programową konwersję plików w takich formatach PDL, jak PS, EPS i XPS, ale przydatne może być obejrzenie i wypróbowanie wieloplatformowych rozwiązań opracowanych na tych natywnych interfejsach API."
---

{{<section feature1>}}
---
title: Konwersja PostScript do PDF za pośrednictwem C# .NET.
h3: "Kod C# do konwersji PS EPS na PDF"
item1: "Aby przekonwertować pliki PostScript PS i Encapsulated PostScript EPS do formatu PDF za pośrednictwem interfejsu .NET API, należy wykonać następujące kroki:"
item2: "Załaduj plik PS lub EPS za pomocą [*PsDocument Class*](https://reference.aspose.com/page/net/aspose.page.eps/psdocument/)."
item3: "Ustaw zapisywanie PDF za pomocą [*PdfSaveOptions Class*](https://reference.aspose.com/page/net/aspose.page.eps.device/pdfsaveoptions/)."
item4: "Użyj [*FileStream Class*](https://docs.microsoft.com/en-us/dotnet/api/system.io.filestream) dla wyjściowego pliku PDF."
item5: "[*PdfDevice Class*](https://reference.aspose.com/page/net/aspose.page.eps.device/pdfdevice/) przez inicjowanie za pomocą wyjściowego obiektu strumienia plików PDF."
item6: "Zadzwoń do [*PsDocument.Save*](https://reference.aspose.com/page/net/aspose.page.eps/psdocument/save/) w celu konwersji PDF."
---

{{<section feature2>}}
---
title: Konwersja PostScript do obrazów za pośrednictwem C# .NET.
h3: "Kod C# do konwersji PostScript na obrazy"
item1: "W przypadku dowolnej aplikacji konwertującej pliki EPS/PS PostScript na obraz następujący kod C# działa dobrze, więc wykonaj następujące kroki:"
item2: Załaduj dokument przy użyciu klasy PsDocument posiadającej strumień pliku wejściowego jako parametr.
item3: "Utwórz obiekt [*ImageSaveOptions Class*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/imagesaveoptions/) i zainicjuj go z wymaganymi ustawieniami."
item4: Zapisz każdą stronę pliku wejściowego w obrazie PNG, JPG, TIFF, BMP itp.
---

{{<section feature3>}}
---
title: Konwertuj XPS na obrazy JPG, PNG, BMP za pomocą C# .NET.
h3: "Kod C# dla konwersji XPS na obraz"
item1: "Interfejs .NET API obsługuje również konwersję XPS do obrazów BMP, JPG, PNG, TIFF itp. oraz zapewnia klasę XpsDocument dla operacji XPS. Aby przekonwertować XPS na obraz, wykonaj następujące kroki:"
item2: Załaduj plik XPS ze strumienia.
item3: "Zainicjuj odpowiednie opcje zapisywania obrazu, np. dla **XPS do JPG** jest to [*JpegSaveOptions*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions/) a dla **XPS do PNG** jego [*PngSaveOptions*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions/). Oto lista wszystkich XPS do obrazu [*opcje zapisywania*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/)."
item4: Zdefiniuj odpowiednie ustawienia, takie jak SmoothingMode, Resolution i PageNumbers itp. do renderowania. Na koniec przejdź przez partycje dokumentów, aby zapisać je w obrazach.
---
