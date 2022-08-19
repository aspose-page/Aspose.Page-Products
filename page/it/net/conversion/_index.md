---
translation: true
template: /_templates/_conversion-net.md
title: API di conversione PDL C# | .NET
url: /net/conversion/
description: Converti PS, EPS e XPS in PDF e immagini inclusi BMP, JPG, PNG e TIFF utilizzando la libreria .NET con la funzionalità di conversione PDL di Aspose.Page.
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: Converti PS, EPS e XPS
h2: Soluzione API convertitore PS, EPS e XPS per .NET.
---

{{<section overview>}}
---
p1: "Ogni volta che è necessario convertire in modo programmatico file PostScript PS e Encapsulated PostScript EPS, nonché documenti XPS, l'API .NET può farlo senza problemi e converte più file. Per PS ed EPS, l'API supporta gli operatori PostScript di livello 1-3 e la maggior parte dei commenti di intestazione EPS, nonché trasforma i documenti PostScript con la massima conformità con l'eccezione di alcuni casi di font e API tratta font come Time New Roman."
p2: "Inoltre, per la trasformazione dei file XPS, l'API può aggiungere o rimuovere pagine, gestire tele, percorsi ed elementi glifi, creare forme grafiche vettoriali, stringhe di testo, convertire elementi di struttura XPS e altro ancora."
p3: "La soluzione API per .NET qui ti consente di convertire file di tali formati PDL come PS, EPS e XPS a livello di codice, ma potresti trovare utile vedere e provare multipiattaforma sviluppati su queste API native."
---

{{<section feature1>}}
---
title: Conversione da PostScript a PDF tramite C# .NET.
h3: "Codice C# per la conversione da PS EPS a PDF"
item1: "Per convertire i file PostScript PS e Encapsulated PostScript EPS in PDF tramite l'API .NET è necessario eseguire i passaggi seguenti:"
item2: "Carica file PS o EPS utilizzando [*PsDocument Class*](https://reference.aspose.com/page/net/aspose.page.eps/psdocument/)."
item3: "Imposta il salvataggio del PDF utilizzando [*PdfSaveOptions Class*](https://reference.aspose.com/page/net/aspose.page.eps.device/pdfsaveoptions/)."
item4: "Utilizzare [*FileStream Class*](https://docs.microsoft.com/en-us/dotnet/api/system.io.filestream) per il file PDF di output."
item5: "[*PdfDevice Class*](https://reference.aspose.com/page/net/aspose.page.eps.device/pdfdevice/) inizializzando con l'oggetto filestream PDF di output."
item6: "Chiama [*PsDocument.Save*](https://reference.aspose.com/page/net/aspose.page.eps/psdocument/save/) per la conversione PDF."
---

{{<section feature2>}}
---
title: Conversione da PostScript a immagini tramite C# .NET.
h3: "Codice C# per la conversione da PostScript a immagini"
item1: "Per qualsiasi applicazione di conversione da EPS/PS PostScript a immagine, il seguente codice C# funziona bene, quindi procedi come segue:"
item2: Carica il documento utilizzando la classe PsDocument con flusso di file di input come parametro.
item3: "Crea un oggetto [*ImageSaveOptions Class*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/imagesaveoptions/) e inizializzalo con le impostazioni richieste."
item4: Salva ogni pagina del file di input in un'immagine PNG, JPG, TIFF, BMP, ecc.
---

{{<section feature3>}}
---
title: Converti XPS in immagini JPG, PNG, BMP tramite C# .NET.
h3: "Codice C# per la conversione da XPS a immagine"
item1: "L'API .NET supporta anche la conversione da XPS in immagini BMP, JPG, PNG, TIFF, ecc. e fornisce la classe XpsDocument per le operazioni XPS. Per convertire XPS in Immagine, procedi nel seguente modo:"
item2: Carica il file XPS dal flusso.
item3: "Inizializza le opzioni di salvataggio dell'immagine pertinenti, ad esempio da **XPS a JPG** è [*JpegSaveOptions*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions/) e per **XPS in PNG** è [*PngSaveOptions*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions/). Ecco l'elenco di tutti gli XPS nell'immagine [*opzioni di salvataggio*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/)."
item4: Definisci le impostazioni rilevanti come SmoothingMode, Resolution e PageNumbers ecc. per il rendering. Infine, scorrere le partizioni del documento per salvarle in immagini.
---
