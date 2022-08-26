---
translation: true
template: /_templates/_conversion-cpp.md
title: PDL Conversion API | C++
url: /cpp/conversion/
description: Konvertera PS, EPS och XPS till PDF och bilder inklusive BMP, JPG, PNG och TIFF med C++-biblioteket med Aspose.Page PDL-konverteringsfunktionen.
family: page
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: Konvertera PS, EPS och XPS
h2: PS, EPS och XPS omvandlar API-lösning för C++.
---

{{<section overview>}}
---
p1: "Närhelst det finns behov av att konvertera PostScript PS och Encapsulated PostScript EPS-filer såväl som XPS-dokument programmässigt, kan Java API göra det smidigt och konvertera flera filer. För PS och EPS stöder API nivåerna 1-3 PostScript-operatorer och de flesta av EPS-rubrikkommentarerna samt transformerar PostScript-dokument med maximal överensstämmelse med undantag för få typsnittsfall och API-avtal som typsnitt som Time New Roman."
p2: "Programmerare kan enkelt använda den för batchbearbetning av PostScript- och XPS-dokument, till och med manipulera dukar, banor och glyferelement och hantera vektorgrafikformer och textsträngar."
p3: "API-lösningen för Java här låter dig konvertera filer av sådana PDL-format som PS, EPS och XPS programmatiskt, men det kan vara användbart att se och prova plattformsoberoende utvecklade på dessa inbyggda API:er. Här är några scenarier för konvertering som EPS till bilder, EPS till PDF, PostScript till PDF, PostScript till bilder, XPS till bilder och XPS till PDF"
---

{{<section feature1>}}
---
title: Konvertera EPS till bilder via C++.
h3: C++-kod för konvertering av EPS till bilder
item1: "C++-biblioteket tillåter konvertering av Encapsulated PostScript-filer (EPS) till bilder på Windows- och Linux-plattformar. Processen är:"
item2: "Använd FileStream för att skapa indataströmmen för EPS-filen samt för att skapa [*PsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.ps_document) objekt med indataström som en parameter. För bildspecifika inställningar, använd [*ImageSaveOptions Class*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_save_options)."
item3: "Definiera bildtyp och storlek med [*ImageDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_device)."
item4: Spara EPS som bilder med bildsparalternativ till en uppsättning matriser av byte och skapar en ny filutmatningsström för varje bytematris.
---


{{<section feature2>}}
---
title: PostScript till PDF-konvertering via Java.
h3: C++-kod för PostScript till PDF-konvertering
item1: "Processen att konvertera PostScript till PDF är densamma som för EPS till bilder, förutom att utvecklare kommer att använda [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_save_options) för att definiera ytterligare inställningar såsom AdditionalFontsFolder och SuppressError-värde etc. Använder dessutom [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_device) från den skapade utströmmen."
---

{{<section feature3>}}
---
title: Konvertera XPS till PDF via C++.
h3: C++-kod för XPS till PDF-konvertering
item1: "C++ XPS Processing API handlar om konvertering av XPS till bilder inklusive BMP, JPG, TIFF, PNG och mer, samt XPS till PDF-konvertering på Windows och Linux-baserade system. Processen att konvertera XPS till PDF är:"
item2: Definiera utdataströmmen samt definiera indataströmmen för inmatat XPS-dokument.
item3: "Skicka den som parameter till [*XpsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.xps_document) Object."
item4: "Ange PDF-specifika sparalternativ som TextCompression, ImageCompression och JpegQualityLevel med [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_save_options)."
item5: "Skapa en instans av [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_device) från den skapade tidigare utdataströmmen."
item6: Konvertera slutligen XPS-dokument som PDF med PDF-sparalternativen.
---
