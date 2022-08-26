---
translation: true
template: /_templates/_conversion-java.md
title: API di conversione PDL | Java
url: /java/conversion/
description: Converti PS, EPS e XPS in PDF e immagini inclusi BMP, JPG, PNG e TIFF utilizzando la libreria Java con la funzionalità di conversione PDL di Aspose.Page.
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: Converti PS, EPS e XPS
h2: Soluzione API convertitore PS, EPS e XPS per Java
---

{{<section overview>}}
---
p1: "Ogni volta che è necessario convertire file PostScript PS e Encapsulated PostScript EPS, nonché documenti XPS in modo programmatico, l'API Java può farlo senza problemi e converte più file. Per PS ed EPS, l'API supporta gli operatori PostScript di livello 1-3 e la maggior parte dei commenti di intestazione EPS, nonché trasforma i documenti PostScript con la massima conformità con l'eccezione di alcuni casi di font e API tratta font come Time New Roman."
p2: "Inoltre, per la trasformazione dei file XPS, l'API può aggiungere o rimuovere pagine, gestire tele, percorsi ed elementi glifi, creare forme grafiche vettoriali, stringhe di testo, convertire elementi di struttura XPS e altro ancora."
p3: "La soluzione API per Java qui ti consente di convertire file di tali formati PDL come PS, EPS e XPS a livello di codice, ma potresti trovare utile vedere e provare multipiattaforma sviluppati su queste API native."
---

{{<section feature1>}}
---
title: Conversione da PostScript a PDF tramite Java.
h3: "Codice Java per convertire PS EPS in PDF"
item1: "Per convertire i file PostScript PS e Encapsulated PostScript EPS in PDF tramite l'API Java è necessario eseguire i passaggi seguenti:"
item2: "Carica il file PS o EPS utilizzando [*PsDocument Class*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument)."
item3: "Impostare le opzioni di salvataggio del PDF utilizzando [*PdfSaveOptions Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfSaveOptions)."
item4: "Utilizzare [*FileStream Class*](https://docs.oracle.com/javase/7/docs/api/java/io/FileOutputStream.html) per il file PDF di output."
item5: "Utilizzare [*PdfDevice Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfDevice) con l'oggetto FileOutputStream come parametro."
item6: "Chiama il [*PsDocument.Save*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) per salvare in PDF il file."
---

{{<section feature2>}}
---
title: Conversione da PostScript a immagini tramite Java.
h3: "Codice Java per la conversione da PostScript a immagini"
item1: "Per qualsiasi applicazione di conversione da EPS/PS PostScript a immagine, il seguente codice Java funziona bene, quindi procedi come segue:"
item2: Inizializza il flusso di input con il file sorgente PS.
item3: "Crea un oggetto [*PsDocument*](https://reference.aspose.com/page/java/com.aspose.eps/psdocument) con il flusso di input PS creato come parametro"
item4: "Utilizzare [*ImageSaveOptions*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagesaveoptions) per specificare AdditionalFontsFolder e SuppressError ecc."
item5: "Utilizzare l'oggetto [*ImageDevice*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagedevice) per specificare un tipo e una dimensione dell'immagine, se necessario."
item6: Salva il file PS/EPS come e immagine con un'opzione di salvataggio dell'immagine come una matrice di array di byte. Un array di byte per una pagina di un file di input.
---


{{<section feature3>}}
---
title: Converti XPS in immagini JPG, PNG, BMP tramite Java.
h3: Codice Java per la conversione da XPS a immagine
item1: "L'API Java gestisce il formato XPS utilizzato per rappresentare il layout di pagina. In qualsiasi scenario, ogni volta che è necessario convertire XPS in immagini BMP, JPG, PNG e TIFF a livello di codice, il codice seguente può essere facilmente integrato nell'applicazione Java."
item2: "Utilizzare [*XpsDocument class*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument) per caricare il documento XPS."
item3: "Utilizzare la classe di opzioni dell'immagine pertinente come [*PngSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PngSaveOptions), [*JpegSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/JpegSaveOptions), [*BmpSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/BmpSaveOptions) , [*TiffSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/TiffSaveOptions) per le impostazioni aggiuntive dell'immagine."
item4: "Crea l'istanza della classe [*image device*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/ImageDevice)."
item5: "Chiama il [*XpsDocument.save*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) per salvare l'immagine JPEG convertita nell'oggetto ImageDevice, quindi utilizzare ImageDevice per salvare l'immagine come JPG."
---

{{<section feature4>}}
---
title: Converti XPS in PDF tramite Java.
h3: Codice Java per la conversione da XPS a PDF
item1: Il processo di conversione di documenti XPS in PDF a livello di codice è semplice con risultati ad alta fedeltà tra i file di input e di output.
item2: "Carica il file utilizzando la classe XpsDocument. Inizializza l'oggetto [*PdfSaveOptions class*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PdfDevice)."
item3: Crea l'oggetto PdfDevice per il rendering e infine salva il documento PDF di output.
---


