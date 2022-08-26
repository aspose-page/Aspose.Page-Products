---
translation: true
template: /_templates/_conversion-java.md
title: PDL-conversie-API | Java
url: /java/conversion/
description: Converteer PS, EPS en XPS naar PDF en afbeeldingen, inclusief BMP, JPG, PNG en TIFF met behulp van de Java-bibliotheek met de Aspose.Page PDL-conversiefunctionaliteit.
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: Converteer PS, EPS en XPS
h2: PS, EPS en XPS converter API-oplossing voor Java
---

{{<section overview>}}
---
p1: "Wanneer het nodig is om PostScript PS en Encapsulated PostScript EPS-bestanden evenals XPS-documenten programmatisch te converteren, kan Java API dit soepel doen en meerdere bestanden converteren. Voor PS en EPS ondersteunt API Levels 1-3 PostScript-operators en de meeste EPS-headeropmerkingen, en transformeert PostScript-documenten met maximale conformiteit, met uitzondering van enkele fonts en API-deals zoals fonts zoals Time New Roman."
p2: "Bovendien kan API voor de transformatie van XPS-bestanden pagina's toevoegen of verwijderen, canvassen, paden en glyphs-elementen behandelen, vectorafbeeldingsvormen, tekststrings maken, XPS-overzichtsitems converteren en meer."
p3: "Met de API-oplossing voor Java hier kunt u bestanden van PDL-indelingen zoals PS, EPS en XPS programmatisch converteren, maar het kan nuttig zijn om platformonafhankelijke ontwikkelde op deze native API's te bekijken en uit te proberen."
---

{{<section feature1>}}
---
title: PostScript naar PDF-conversie via Java.
h3: "Java-code om PS EPS naar PDF te converteren"
item1: "Om PostScript PS- en Encapsulated PostScript EPS-bestanden via Java API naar PDF te converteren, moet u de volgende stappen uitvoeren:"
item2: "Laad PS- of EPS-bestand met [*PsDocument Class*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument)."
item3: "Stel de PDF-opslagopties in met [*PdfSaveOptions Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfSaveOptions)."
item4: "Gebruik [*FileStream Class*](https://docs.oracle.com/javase/7/docs/api/java/io/FileOutputStream.html) voor het PDF-uitvoerbestand."
item5: "Gebruik [*PdfDevice Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfDevice) met het FileOutputStream-object als parameter."
item6: "Bel de [*PsDocument.Save*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) om het bestand in PDF op te slaan."
---

{{<section feature2>}}
---
title: PostScript naar afbeeldingen conversie via Java.
h3: "Java-code voor conversie van PostScript naar afbeeldingen"
item1: "Voor elke EPS/PS PostScript-naar-beeldconversietoepassing werkt de volgende Java-code goed, dus neem de volgende stappen:"
item2: Initialiseer de invoerstroom met het PS-bronbestand.
item3: "Creëer [*PsDocument*](https://reference.aspose.com/page/java/com.aspose.eps/psdocument) object met aangemaakte PS-invoerstroom als parameter"
item4: "Gebruik [*ImageSaveOptions*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagesaveoptions) om AdditionalFontsFolder en SuppressError etc. op te geven."
item5: "Gebruik het object [*ImageDevice*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagedevice) om zo nodig een afbeeldingstype en -grootte op te geven."
item6: Bewaar PS/EPS-bestand als en afbeelding met opties voor het opslaan van afbeeldingen als een array van arrays van bytes. Eén array van bytes voor één pagina van een invoerbestand.
---


{{<section feature3>}}
---
title: Converteer XPS naar afbeeldingen JPG, PNG, BMP via Java.
h3: Java-code voor XPS-naar-beeldconversie
item1: "Java API behandelt XPS-indeling die wordt gebruikt voor het weergeven van paginalay-out. In elk scenario, wanneer het nodig is om XPS programmatisch naar afbeeldingen BMP, JPG, PNG en TIFF te converteren, kan de volgende code eenvoudig worden geïntegreerd in de Java-toepassing."
item2: "Gebruik [*XpsDocument class*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument) om het XPS-document te laden."
item3: "Gebruik de relevante afbeeldingsoptieklasse zoals [*PngSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PngSaveOptions), [*JpegSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/JpegSaveOptions), [*BmpSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/BmpSaveOptions) , [*TiffSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/TiffSaveOptions) voor aanvullende instellingen voor afbeeldingen."
item4: "Maak de [*image device*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/ImageDevice) Class-instantie."
item5: "Bel de [*XpsDocument.save*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) om de geconverteerde JPEG-afbeelding op te slaan in het ImageDevice-object en vervolgens ImageDevice te gebruiken om de afbeelding op te slaan als een JPG."
---

{{<section feature4>}}
---
title: Converteer XPS naar PDF via Java.
h3: Java-code voor XPS naar PDF-conversie
item1: Het proces van het programmatisch converteren van XPS naar PDF-documenten is eenvoudig met high-fidelity-resultaten tussen de invoer- en uitvoerbestanden.
item2: "Laad het bestand met de XpsDocument-klasse. Initialiseer [*PdfSaveOptions class*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PdfDevice) object."
item3: Maak een PdfDevice-object voor weergave en sla ten slotte het PDF-uitvoerdocument op.
---


