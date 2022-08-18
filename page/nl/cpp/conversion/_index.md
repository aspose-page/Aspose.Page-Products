---
translation: true
template: /_templates/_conversion-cpp.md
title: PDL-conversie-API | C++
url: /cpp/conversion/
description: Converteer PS, EPS en XPS naar PDF en afbeeldingen, inclusief BMP, JPG, PNG en TIFF met behulp van de C++-bibliotheek met de Aspose.Page PDL-conversiefunctionaliteit.
family: page
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: Converteer PS, EPS en XPS
h2: PS, EPS en XPS converter API-oplossing voor C++.
---

{{<section overview>}}
---
p1: "Wanneer PostScript PS en Encapsulated PostScript EPS-bestanden evenals XPS-documenten programmatisch moeten worden geconverteerd, kan Java API dit soepel doen en meerdere bestanden converteren. Voor PS en EPS ondersteunt API Levels 1-3 PostScript-operators en de meeste EPS-headeropmerkingen, en transformeert PostScript-documenten met maximale conformiteit, met uitzondering van enkele fonts en API-deals zoals fonts zoals Time New Roman."
p2: "Programmeurs kunnen het gemakkelijk gebruiken voor batchverwerking van PostScript- en XPS-documenten, zelfs canvassen, paden en glyphs-elementen manipuleren en vectorafbeeldingen en tekstreeksen verwerken."
p3: "Met de API-oplossing voor Java hier kunt u bestanden van PDL-indelingen zoals PS, EPS en XPS programmatisch converteren, maar het kan nuttig zijn om platformonafhankelijke ontwikkelde op deze native API's te bekijken en uit te proberen. Hier zijn enkele scenario's van conversie, zoals EPS naar afbeeldingen, EPS naar PDF, PostScript naar PDF, PostScript naar afbeeldingen, XPS naar afbeeldingen en XPS naar PDF"
---

{{<section feature1>}}
---
title: Converteer EPS naar afbeeldingen via C++.
h3: C++-code voor conversie van EPS naar afbeeldingen
item1: "Met de C++-bibliotheek kunnen Encapsulated PostScript-bestanden (EPS) worden geconverteerd naar afbeeldingen op Windows- en Linux-platforms. Het proces is:"
item2: "Gebruik FileStream om de invoerstroom voor het EPS-bestand te maken en om [*PsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.ps_document) object met invoerstroom te maken als parameter. Gebruik voor afbeeldingenspecifieke instellingen de [*ImageSaveOptions Class*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_save_options)."
item3: "Definieer het afbeeldingstype en de grootte met behulp van [*ImageDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_device)."
item4: Sla EPS op als afbeeldingen met opties voor het opslaan van afbeeldingen in een array van arrays van bytes en creëer voor elke bytes-array een nieuwe bestandsuitvoerstroom.
---


{{<section feature2>}}
---
title: PostScript naar PDF-conversie via Java.
h3: C++-code voor conversie van PostScript naar PDF
item1: "Het proces van het converteren van PostScript naar PDF is hetzelfde als van EPS naar afbeeldingen, behalve dat ontwikkelaars [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device) zullen gebruiken .pdf_save_options) om aanvullende instellingen te definiëren, zoals de waarde AdditionalFontsFolder en SuppressError enz. Bovendien zal [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_device) uit de gemaakte uitvoerstroom."
---

{{<section feature3>}}
---
title: Converteer XPS naar PDF via C++.
h3: C++-code voor XPS naar PDF-conversie
item1: "C++ XPS Processing API behandelt de conversie van XPS naar afbeeldingen, waaronder BMP, JPG, TIFF, PNG en meer, evenals XPS naar PDF-conversie op Windows- en Linux-gebaseerde systemen. Het proces van het converteren van XPS naar PDF is:"
item2: Definieer de uitvoerstroom en definieer de invoerstroom voor het XPS-invoerdocument.
item3: "Geef het door als parameter aan [*XpsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.xps_document) Object."
item4: "Specificeer de PDF-specifieke opslagopties zoals TextCompression, ImageCompression en JpegQualityLevel met behulp van [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_save_options)."
item5: "Maak een instantie van [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_device) van de eerder gemaakte uitvoerstroom."
item6: Converteer ten slotte XPS-document als PDF met de PDF-opslagopties.
---
