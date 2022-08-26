---
translation: true
template: /_templates/_conversion-net.md
title: PDL Conversion API C# | .NET
url: /net/conversion/
description: Konvertera PS, EPS och XPS till PDF och bilder inklusive BMP, JPG, PNG och TIFF med hjälp av .NET-biblioteket med Aspose.Page PDL-konverteringsfunktionen.
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: Konvertera PS, EPS och XPS
h2: PS, EPS och XPS omvandlar API-lösning för .NET.
---

{{<section overview>}}
---
p1: "Närhelst det finns behov av att konvertera PostScript PS och Encapsulated PostScript EPS-filer samt XPS-dokument programmässigt, kan .NET API göra det smidigt och konvertera flera filer. För PS och EPS stöder API nivåerna 1-3 PostScript-operatorer och de flesta av EPS-rubrikkommentarerna samt transformerar PostScript-dokument med maximal överensstämmelse med undantag för få typsnittsfall och API-avtal som typsnitt som Time New Roman."
p2: "Dessutom, för transformation av XPS-filer kan API lägga till eller ta bort sidor, hantera dukar, banor och glyferelement, skapa vektorgrafikformer, textsträngar, konvertera XPS-konturobjekt och mer."
p3: "API-lösningen för .NET här låter dig konvertera filer av sådana PDL-format som PS, EPS och XPS programmatiskt, men det kan vara användbart att se och prova plattformsoberoende utvecklade på dessa inbyggda API:er."
---

{{<section feature1>}}
---
title: PostScript till PDF-konvertering via C# .NET.
h3: "C#-kod för PS EPS till PDF-konvertering"
item1: "För att konvertera PostScript PS och Encapsulated PostScript EPS-filer till PDF via .NET API måste du ta följande steg:"
item2: "Ladda PS- eller EPS-fil med [*PsDocument Class*](https://reference.aspose.com/page/net/aspose.page.eps/psdocument/)."
item3: "Ställ in PDF-sparandet med [*PdfSaveOptions Class*](https://reference.aspose.com/page/net/aspose.page.eps.device/pdfsaveoptions/)."
item4: "Använd [*FileStream Class*](https://docs.microsoft.com/en-us/dotnet/api/system.io.filestream) för utmatning av PDF-fil."
item5: "[*PdfDevice Class*](https://reference.aspose.com/page/net/aspose.page.eps.device/pdfdevice/) genom att initiera med utdata-PDF-filströmsobjekt."
item6: "Ring [*PsDocument.Save*](https://reference.aspose.com/page/net/aspose.page.eps/psdocument/save/) för PDF-konvertering."
---

{{<section feature2>}}
---
title: PostScript till bildkonvertering via C# .NET.
h3: "C#-kod för konvertering av PostScript till bilder"
item1: "För alla EPS/PS PostScript till bildkonverteringsprogram fungerar följande C#-kod bra, så ta nästa steg:"
item2: Ladda dokument med PsDocument-klassen med indatafilström som parameter.
item3: "Skapa [*ImageSaveOptions Class*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/imagesaveoptions/) objekt och initiera det med de nödvändiga inställningarna."
item4: Spara varje indatafilsida till en bild PNG, JPG, TIFF, BMP, etc.
---

{{<section feature3>}}
---
title: Konvertera XPS till bilder JPG, PNG, BMP via C# .NET.
h3: "C#-kod för konvertering av XPS till bild"
item1: ".NET API stöder även XPS-konvertering till bilder BMP, JPG, PNG, TIFF, etc., och tillhandahåller XpsDocument Class för XPS-operationer. För att konvertera XPS till Image, ta följande steg:"
item2: Ladda XPS-fil från strömmen.
item3: "Initiera de relevanta bildsparalternativen, t.ex. för **XPS till JPG** det är [*JpegSaveOptions*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions/) och för **XPS till PNG** dess [*PngSaveOptions*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions/). Här är en lista över alla XPS till bild [*spara alternativ*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/)."
item4: Definiera relevanta inställningar som SmoothingMode, Resolution och Page Numbers etc. för rendering. Äntligen iterera genom dokumentpartitioner för att spara dem i bilder.
---
