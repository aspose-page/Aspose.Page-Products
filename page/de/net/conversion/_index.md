---
translation: true
template: /_templates/_conversion-net.md
title: PDL-Konvertierungs-API C# | .NET
url: /net/conversion/
description: Konvertieren Sie PS, EPS und XPS in PDF und Bilder, einschließlich BMP, JPG, PNG und TIFF, indem Sie die .NET-Bibliothek mit der Aspose.Page PDL-Konvertierungsfunktion verwenden.
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: Konvertieren Sie PS, EPS und XPS
h2: PS-, EPS- und XPS-Konverter-API-Lösung für .NET.
---

{{<section overview>}}
---
p1: "Wann immer es erforderlich ist, PostScript PS- und Encapsulated PostScript EPS-Dateien sowie XPS-Dokumente programmgesteuert zu konvertieren, kann die .NET-API dies reibungslos tun und mehrere Dateien konvertieren. Für PS und EPS unterstützt die API die PostScript-Operatoren der Ebenen 1–3 und die meisten EPS-Header-Kommentare und transformiert PostScript-Dokumente mit maximaler Konformität mit Ausnahme einiger Schriftartenfälle, und die API behandelt Schriftarten wie Time New Roman."
p2: "Darüber hinaus kann die API für die Transformation von XPS-Dateien Seiten hinzufügen oder entfernen, mit Leinwänden, Pfaden und Glyphenelementen umgehen, Vektorgrafiken, Textzeichenfolgen erstellen, XPS-Gliederungselemente konvertieren und vieles mehr."
p3: "Mit der API-Lösung für .NET hier können Sie Dateien solcher PDL-Formate wie PS, EPS und XPS programmgesteuert konvertieren, aber es kann hilfreich sein, plattformübergreifende Entwicklungen auf diesen nativen APIs zu sehen und auszuprobieren."
---

{{<section feature1>}}
---
title: Konvertierung von PostScript in PDF über C# .NET.
h3: "C#-Code für die Umwandlung von PS EPS in PDF"
item1: "Um PostScript PS- und Encapsulated PostScript EPS-Dateien über die .NET-API in PDF zu konvertieren, müssen Sie die folgenden Schritte ausführen:"
item2: "Laden Sie die PS- oder EPS-Datei mit [*PsDocument Class*](https://reference.aspose.com/page/net/aspose.page.eps/psdocument/)."
item3: "Stellen Sie die PDF-Speicherung mit [*PdfSaveOptions Class*](https://reference.aspose.com/page/net/aspose.page.eps.device/pdfsaveoptions/) ein."
item4: "Verwenden Sie [*FileStream Class*](https://docs.microsoft.com/en-us/dotnet/api/system.io.filestream) für die PDF-Ausgabedatei."
item5: "[*PdfDevice Class*](https://reference.aspose.com/page/net/aspose.page.eps.device/pdfdevice/) durch Initialisierung mit Ausgabe-PDF-Filestream-Objekt."
item6: "Rufen Sie [*PsDocument.Save*](https://reference.aspose.com/page/net/aspose.page.eps/psdocument/save/) für die PDF-Konvertierung auf."
---

{{<section feature2>}}
---
title: Umwandlung von PostScript in Bilder über C# .NET.
h3: "C#-Code für die Umwandlung von PostScript in Bilder"
item1: "Für jede EPS/PS-PostScript-zu-Bild-Konvertierungsanwendung funktioniert der folgende C#-Code gut, also führen Sie die nächsten Schritte aus:"
item2: Laden Sie das Dokument mithilfe der PsDocument-Klasse mit dem Eingabedateistream als Parameter.
item3: "Erstellen Sie das Objekt [*ImageSaveOptions Class*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/imagesaveoptions/) und initialisieren Sie es mit den erforderlichen Einstellungen."
item4: Speichern Sie jede Eingabedateiseite als Bild PNG, JPG, TIFF, BMP usw.
---

{{<section feature3>}}
---
title: Konvertieren Sie XPS in Bilder JPG, PNG, BMP über C# .NET.
h3: "C#-Code für die XPS-zu-Bild-Konvertierung"
item1: "Die .NET-API unterstützt auch die XPS-Konvertierung in Bilder BMP, JPG, PNG, TIFF usw. und stellt die XpsDocument-Klasse für XPS-Operationen bereit. Führen Sie die folgenden Schritte aus, um XPS in Image umzuwandeln:"
item2: XPS-Datei aus dem Stream laden.
item3: "Initialisieren Sie die relevanten Bildspeicheroptionen, z. B. für **XPS zu JPG** ist es [*JpegSaveOptions*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions/) und für **XPS zu PNG** seine [*PngSaveOptions*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions/). Hier ist eine Liste aller XPS-zu-Bilder [*Speicheroptionen*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/)."
item4: Definieren Sie relevante Einstellungen wie SmoothingMode, Resolution und PageNumbers etc. für das Rendern. Durchlaufen Sie schließlich Dokumentpartitionen, um sie in Bildern zu speichern.
---
