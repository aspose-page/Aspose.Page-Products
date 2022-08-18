---
translation: true
template: /_templates/_conversion-cpp.md
title: API di conversione PDL | C++
url: /cpp/conversion/
description: Converti PS, EPS e XPS in PDF e immagini inclusi BMP, JPG, PNG e TIFF utilizzando la libreria C++ con la funzionalità di conversione PDL di Aspose.Page.
family: page
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: Converti PS, EPS e XPS
h2: Soluzione API convertitore PS, EPS e XPS per C++.
---

{{<section overview>}}
---
p1: "Ogni volta che è necessario convertire file PostScript PS e Encapsulated PostScript EPS, nonché documenti XPS in modo programmatico, l'API Java può farlo senza problemi e converte più file. Per PS ed EPS, l'API supporta gli operatori PostScript di livello 1-3 e la maggior parte dei commenti di intestazione EPS, nonché trasforma i documenti PostScript con la massima conformità con l'eccezione di alcuni casi di font e API tratta font come Time New Roman."
p2: "I programmatori possono utilizzarlo facilmente per l'elaborazione in batch di documenti PostScript e XPS, persino manipolare tele, percorsi ed elementi glifi e gestire forme di grafica vettoriale e stringhe di testo."
p3: "La soluzione API per Java qui ti consente di convertire file di tali formati PDL come PS, EPS e XPS a livello di codice, ma potresti trovare utile vedere e provare multipiattaforma sviluppati su queste API native. Ecco alcuni scenari di conversione come EPS in immagini, EPS in PDF, PostScript in PDF, PostScript in immagini, XPS in immagini e XPS in PDF"
---

{{<section feature1>}}
---
title: Converti EPS in immagini tramite C++.
h3: Codice C++ per la conversione da EPS a immagini
item1: "La libreria C++ consente di convertire file Encapsulated PostScript (EPS) in immagini su piattaforme Windows e Linux. Il processo è:"
item2: "Utilizzare FileStream per creare il flusso di input per il file EPS e per creare un oggetto [*PsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.ps_document) con un flusso di input come parametro. Per le impostazioni specifiche delle immagini, utilizzare la [*ImageSaveOptions Class*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_save_options)."
item3: "Definisci il tipo e la dimensione dell'immagine utilizzando [*ImageDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_device)."
item4: Salva EPS come immagini con le opzioni di salvataggio dell'immagine in un array di array di byte creando per ogni array di byte un nuovo flusso di output di file.
---


{{<section feature2>}}
---
title: Conversione da PostScript a PDF tramite Java.
h3: Codice C++ per la conversione da PostScript a PDF
item1: "Il processo di conversione di PostScript in PDF è lo stesso di EPS in immagini, tranne per il fatto che gli sviluppatori utilizzeranno [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_save_options) per definire impostazioni aggiuntive come AdditionalFontsFolder e SuppressError value ecc. Inoltre, utilizzerà [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_device) dal flusso di output creato."
---

{{<section feature3>}}
---
title: Converti XPS in PDF tramite C++.
h3: Codice C++ per la conversione da XPS a PDF
item1: "L'API di elaborazione C++ XPS si occupa della conversione di XPS in immagini inclusi BMP, JPG, TIFF, PNG e altro, nonché della conversione da XPS a PDF su sistemi basati su Windows e Linux. Il processo di conversione da XPS a PDF è:"
item2: Definire il flusso di output e definire il flusso di input per il documento XPS di input.
item3: "Passalo come parametro all'oggetto [*XpsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.xps_document)."
item4: "Specificare le opzioni di salvataggio specifiche del PDF come TextCompression, ImageCompression e JpegQualityLevel utilizzando [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_save_options)."
item5: "Crea un'istanza di [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_device) dal flusso di output precedente creato."
item6: Infine converti il ​​documento XPS in PDF con le opzioni di salvataggio PDF.
---
