---
translation: true
template: /_templates/_conversion-java.md
title: PDL-Konvertierungs-API | Java
url: /java/conversion/
description: Konvertieren Sie PS, EPS und XPS in PDF und Bilder, einschließlich BMP, JPG, PNG und TIFF, indem Sie die Java-Bibliothek mit der Aspose.Page PDL-Konvertierungsfunktion verwenden.
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: Konvertieren Sie PS, EPS und XPS
h2: PS-, EPS- und XPS-Konverter-API-Lösung für Java
---

{{<section overview>}}
---
p1: "Wann immer es erforderlich ist, PostScript PS- und Encapsulated PostScript EPS-Dateien sowie XPS-Dokumente programmgesteuert zu konvertieren, kann die Java-API dies reibungslos tun und mehrere Dateien konvertieren. Für PS und EPS unterstützt die API die PostScript-Operatoren der Ebenen 1–3 und die meisten EPS-Header-Kommentare und transformiert PostScript-Dokumente mit maximaler Konformität, mit Ausnahme weniger Schriftarten, und die API behandelt Schriftarten wie Time New Roman."
p2: "Darüber hinaus kann die API für die Transformation von XPS-Dateien Seiten hinzufügen oder entfernen, mit Leinwänden, Pfaden und Glyphenelementen umgehen, Vektorgrafiken, Textzeichenfolgen erstellen, XPS-Gliederungselemente konvertieren und vieles mehr."
p3: "Mit der API-Lösung für Java hier können Sie Dateien in PDL-Formaten wie PS, EPS und XPS programmgesteuert konvertieren, aber es kann hilfreich sein, plattformübergreifende Entwicklungen auf diesen nativen APIs zu sehen und auszuprobieren."
---

{{<section feature1>}}
---
title: Konvertierung von PostScript in PDF über Java.
h3: "Java-Code zum Konvertieren von PS EPS in PDF"
item1: "Um PostScript PS- und Encapsulated PostScript EPS-Dateien über die Java-API in PDF zu konvertieren, müssen Sie die folgenden Schritte ausführen:"
item2: "Laden Sie die PS- oder EPS-Datei mit [*PsDocument Class*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument)."
item3: "Legen Sie die PDF-Speicheroptionen mit [*PdfSaveOptions Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfSaveOptions) fest."
item4: "Verwenden Sie [*FileStream Class*](https://docs.oracle.com/javase/7/docs/api/java/io/FileOutputStream.html) für die PDF-Ausgabedatei."
item5: "Verwenden Sie [*PdfDevice Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfDevice) mit dem FileOutputStream-Objekt als Parameter."
item6: "Rufen Sie [*PsDocument.Save*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) zum Speichern der Datei im PDF-Format."
---

{{<section feature2>}}
---
title: Umwandlung von PostScript in Bilder über Java.
h3: "Java-Code für die Umwandlung von PostScript in Bilder"
item1: "Für jede EPS/PS-PostScript-zu-Bild-Konvertierungsanwendung funktioniert der folgende Java-Code gut, also unternehmen Sie die nächsten Schritte:"
item2: Eingabestrom mit PS-Quelldatei initialisieren.
item3: "Erstellen Sie das Objekt [*PsDocument*](https://reference.aspose.com/page/java/com.aspose.eps/psdocument) mit dem erstellten PS-Eingabestream als Parameter"
item4: "Verwenden Sie [*ImageSaveOptions*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagesaveoptions), um AdditionalFontsFolder und SuppressError usw. anzugeben."
item5: "Verwenden Sie das Objekt [*ImageDevice*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagedevice) zum Angeben eines Bildtyps und einer Bildgröße, falls erforderlich."
item6: PS/EPS-Datei speichern als und Bild mit Bildspeicheroptionen als Array von Byte-Arrays. Ein Array von Bytes für eine Seite einer Eingabedatei.
---


{{<section feature3>}}
---
title: Konvertieren Sie XPS in Bilder JPG, PNG, BMP über Java.
h3: Java-Code für die XPS-zu-Bild-Konvertierung
item1: "Die Java-API befasst sich mit dem XPS-Format, das zur Darstellung des Seitenlayouts verwendet wird. Wann immer es notwendig ist, XPS programmatisch in BMP-, JPG-, PNG- und TIFF-Bilder zu konvertieren, kann der folgende Code einfach in die Java-Anwendung integriert werden."
item2: "Verwenden Sie [*XpsDocument-Klasse*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument), um das XPS-Dokument zu laden."
item3: "Verwenden Sie die relevante Bildoptionsklasse wie [*PngSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PngSaveOptions), [*JpegSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/JpegSaveOptions), [*BmpSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/BmpSaveOptions) , [*TiffSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/TiffSaveOptions) für zusätzliche Bildeinstellungen."
item4: "Erstellen Sie die Klasseninstanz [*Bildgerät*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/ImageDevice)."
item5: "Rufen Sie [*XpsDocument.save*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-), um das konvertierte JPEG-Bild im ImageDevice-Objekt zu speichern, und verwenden Sie dann ImageDevice, um das Bild als JPG zu speichern."
---

{{<section feature4>}}
---
title: Konvertieren Sie XPS in PDF über Java.
h3: Java-Code für die Umwandlung von XPS in PDF
item1: Der Prozess der programmgesteuerten Konvertierung von XPS- in PDF-Dokumente ist einfach und bietet High-Fidelity-Ergebnisse zwischen den Eingabe- und Ausgabedateien.
item2: "Laden Sie die Datei mithilfe der XpsDocument-Klasse. Initialisieren Sie das Objekt [*PdfSaveOptions-Klasse*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PdfDevice)."
item3: Erstellen Sie ein PdfDevice-Objekt zum Rendern und speichern Sie zuletzt das ausgegebene PDF-Dokument.
---


