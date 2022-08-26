---
translation: true
template: /_templates/_conversion-java.md
title: PDL Conversion API | Java
url: /java/conversion/
description: Konvertera PS, EPS och XPS till PDF och bilder inklusive BMP, JPG, PNG och TIFF med hjälp av Java-biblioteket med Aspose.Page PDL-konverteringsfunktionen.
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: Konvertera PS, EPS och XPS
h2: PS, EPS och XPS omvandlar API-lösning för Java
---

{{<section overview>}}
---
p1: "Närhelst det finns behov av att konvertera PostScript PS och Encapsulated PostScript EPS-filer såväl som XPS-dokument programmässigt, kan Java API göra det smidigt och konvertera flera filer. För PS och EPS stöder API nivåerna 1-3 PostScript-operatorer och de flesta av EPS-rubrikkommentarerna samt transformerar PostScript-dokument med maximal överensstämmelse med undantag för få typsnittsfall och API-avtal som typsnitt som Time New Roman."
p2: "Dessutom, för transformation av XPS-filer kan API lägga till eller ta bort sidor, hantera dukar, banor och glyferelement, skapa vektorgrafikformer, textsträngar, konvertera XPS-konturobjekt och mer."
p3: "API-lösningen för Java här låter dig konvertera filer av sådana PDL-format som PS, EPS och XPS programmatiskt, men det kan vara användbart att se och prova plattformsoberoende utvecklade på dessa inbyggda API:er."
---

{{<section feature1>}}
---
title: PostScript till PDF-konvertering via Java.
h3: "Java-kod för att konvertera PS EPS till PDF"
item1: "För att konvertera PostScript PS och Encapsulated PostScript EPS-filer till PDF via Java API måste du ta följande steg:"
item2: "Ladda PS- eller EPS-fil med [*PsDocument Class*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument)."
item3: "Ställ in PDF-sparalternativ med [*PdfSaveOptions Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfSaveOptions)."
item4: "Använd [*FileStream Class*](https://docs.oracle.com/javase/7/docs/api/java/io/FileOutputStream.html) för utmatning av PDF-fil."
item5: "Använd [*PdfDevice Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfDevice) med FileOutputStream-objektet som parameter."
item6: "Ring [*PsDocument.Save*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) för att spara filen i PDF."
---

{{<section feature2>}}
---
title: PostScript till bildkonvertering via Java.
h3: "Java-kod för PostScript till bildkonvertering"
item1: "För alla EPS/PS PostScript till bildkonverteringsprogram fungerar följande Java-kod bra, så ta nästa steg:"
item2: Initiera indataström med PS-källfil.
item3: "Skapa [*PsDocument*](https://reference.aspose.com/page/java/com.aspose.eps/psdocument) objekt med skapad PS-indataström som en parameter"
item4: "Använd [*ImageSaveOptions*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagesaveoptions) för att ange AdditionalFontsFolder och SuppressError etc."
item5: "Använd objektet [*ImageDevice*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagedevice) för att ange en bildtyp och storlek om det behövs."
item6: Spara PS/EPS-fil som och bild med ett bildsparalternativ som en array av arrayer av byte. En array av byte för en sida i en indatafil.
---


{{<section feature3>}}
---
title: Konvertera XPS till bilder JPG, PNG, BMP via Java.
h3: Java-kod för konvertering av XPS till bild
item1: "Java API erbjuder XPS-format som används för att representera sidlayout. I vilket scenario som helst, närhelst det finns ett behov av att konvertera XPS till bilder BMP, JPG, PNG och TIFF programmatiskt, kan följande kod enkelt integreras i Java-applikationen."
item2: "Använd [*XpsDocument class*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument) för att ladda XPS-dokumentet."
item3: "Använd den relevanta bildalternativsklassen som [*PngSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PngSaveOptions), [*JpegSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/JpegSaveOptions), [*BmpSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/BmpSaveOptions) , [*TiffSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/TiffSaveOptions) för ytterligare bildinställningar."
item4: "Skapa klassinstansen [*bildenhet*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/ImageDevice)."
item5: "Ring [*XpsDocument.save*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) för att spara den konverterade JPEG-bilden i ImageDevice-objekt och använd sedan ImageDevice för att spara bilden som en JPG."
---

{{<section feature4>}}
---
title: Konvertera XPS till PDF via Java.
h3: Java-kod för XPS till PDF-konvertering
item1: Processen att konvertera XPS till PDF-dokument programmatiskt är enkel och har högtrogna resultat bland in- och utdatafilerna.
item2: "Ladda filen med XpsDocument-klassen. Initiera [*PdfSaveOptions class*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PdfDevice) objekt."
item3: Skapa PdfDevice-objekt för rendering och spara slutligen PDF-dokumentet.
---


