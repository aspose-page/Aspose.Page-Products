---
translation: true
template: /_templates/_conversion-cpp.md
title: PDL-Konvertierungs-API | C++
url: /cpp/conversion/
description: Konvertieren Sie PS, EPS und XPS in PDF und Bilder, einschließlich BMP, JPG, PNG und TIFF, indem Sie die C++-Bibliothek mit der Aspose.Page PDL-Konvertierungsfunktion verwenden.
family: page
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: Konvertieren Sie PS, EPS und XPS
h2: PS-, EPS- und XPS-Konverter-API-Lösung für C++.
---

{{<section overview>}}
---
p1: "Wann immer es erforderlich ist, PostScript PS- und Encapsulated PostScript EPS-Dateien sowie XPS-Dokumente programmgesteuert zu konvertieren, kann die Java-API dies reibungslos tun und mehrere Dateien konvertieren. Für PS und EPS unterstützt die API die PostScript-Operatoren der Ebenen 1–3 und die meisten EPS-Header-Kommentare und transformiert PostScript-Dokumente mit maximaler Konformität, mit Ausnahme weniger Schriftarten, und die API behandelt Schriftarten wie Time New Roman."
p2: "Programmierer können es problemlos für die Stapelverarbeitung von PostScript- und XPS-Dokumenten verwenden, sogar Leinwände, Pfade und Glyphenelemente bearbeiten und Vektorgrafikformen und Textzeichenfolgen verarbeiten."
p3: "Mit der API-Lösung für Java hier können Sie Dateien solcher PDL-Formate wie PS, EPS und XPS programmgesteuert konvertieren, aber es kann hilfreich sein, plattformübergreifende Entwicklungen auf diesen nativen APIs zu sehen und auszuprobieren. Hier sind einige Konvertierungsszenarien wie EPS in Bilder, EPS in PDF, PostScript in PDF, PostScript in Bilder, XPS in Bilder und XPS in PDF"
---

{{<section feature1>}}
---
title: Konvertieren Sie EPS in Bilder über C++.
h3: C++-Code für die Umwandlung von EPS in Bilder
item1: "Die C++-Bibliothek ermöglicht das Konvertieren von Encapsulated PostScript (EPS)-Dateien in Bilder auf Windows- und Linux-Plattformen. Der Prozess ist:"
item2: "Verwenden Sie FileStream zum Erstellen des Eingabestreams für die EPS-Datei sowie zum Erstellen des [*PsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.ps_document)-Objekts mit Eingabestream als Parameter. Verwenden Sie für bildspezifische Einstellungen die [*ImageSaveOptions-Klasse*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_save_options)."
item3: "Definieren Sie den Bildtyp und die Größe mit [*ImageDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_device)."
item4: Speichern Sie EPS als Bilder mit Bildspeicheroptionen in einem Array von Byte-Arrays, wodurch für jedes Byte-Array ein neuer Dateiausgabestrom erstellt wird.
---


{{<section feature2>}}
---
title: Konvertierung von PostScript in PDF über Java.
h3: C++-Code für die Umwandlung von PostScript in PDF
item1: "Der Vorgang zum Konvertieren von PostScript in PDF ist der gleiche wie von EPS in Bilder, außer dass Entwickler [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_save_options), um zusätzliche Einstellungen wie AdditionalFontsFolder und SuppressError-Wert usw. zu definieren. Außerdem wird [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_device) aus dem erstellten Ausgabestream."
---

{{<section feature3>}}
---
title: Konvertieren Sie XPS in PDF über C++.
h3: C++-Code für die Umwandlung von XPS in PDF
item1: "Die C++ XPS-Verarbeitungs-API behandelt die Konvertierung von XPS in Bilder, einschließlich BMP, JPG, TIFF, PNG und mehr, sowie die Konvertierung von XPS in PDF auf Windows- und Linux-basierten Systemen. Der Vorgang zum Konvertieren von XPS in PDF ist:"
item2: Definieren Sie den Ausgabestream sowie den Eingabestream für das XPS-Eingabedokument.
item3: "Übergeben Sie es als Parameter an das Objekt [*XpsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.xps_document)."
item4: "Geben Sie die PDF-spezifischen Speicheroptionen wie TextCompression, ImageCompression und JpegQualityLevel mit [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_save_options) an."
item5: "Erstellen Sie eine Instanz von [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_device) aus dem zuvor erstellten Ausgabestream."
item6: Konvertieren Sie schließlich das XPS-Dokument als PDF mit den PDF-Speicheroptionen.
---
