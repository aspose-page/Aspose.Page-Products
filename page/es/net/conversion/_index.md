---
translation: true
template: /_templates/_conversion-net.md
title: API de conversión de PDL C# | .NET
url: /net/conversion/
description: Convierta PS, EPS y XPS a PDF e imágenes, incluidos BMP, JPG, PNG y TIFF, utilizando la biblioteca .NET con la función de conversión PDL de Aspose.Page.
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: Convierte PS, EPS y XPS
h2: Solución API de conversión de PS, EPS y XPS para .NET.
---

{{<section overview>}}
---
p1: "Siempre que sea necesario convertir archivos PostScript PS y PostScript EPS encapsulados, así como documentos XPS programáticamente, la API .NET puede hacerlo sin problemas y convierte múltiples archivos. Para PS y EPS, la API admite operadores PostScript de niveles 1 a 3 y la mayoría de los comentarios de encabezado de EPS, además de transformar documentos PostScript con la máxima conformidad con la excepción de unos pocos casos de fuentes y la API trata fuentes como Time New Roman."
p2: "Además, para la transformación de archivos XPS, la API puede agregar o eliminar páginas, manejar lienzos, rutas y elementos de glifos, crear formas de gráficos vectoriales, cadenas de texto, convertir elementos de esquema XPS y más."
p3: "La solución API para .NET aquí le permite convertir archivos de formatos PDL como PS, EPS y XPS mediante programación, pero puede resultarle útil ver y probar el desarrollo multiplataforma en estas API nativas."
---

{{<section feature1>}}
---
title: Conversión de PostScript a PDF a través de C# .NET.
h3: "Código C# para la conversión de PS EPS a PDF"
item1: "Para convertir archivos PostScript PS y PostScript encapsulado EPS a PDF a través de la API de .NET, debe seguir los siguientes pasos:"
item2: "Cargue el archivo PS o EPS usando [*PsDocument Class*](https://reference.aspose.com/page/net/aspose.page.eps/psdocument/)."
item3: "Configure el guardado de PDF usando [*PdfSaveOptions Class*](https://reference.aspose.com/page/net/aspose.page.eps.device/pdfsaveoptions/)."
item4: "Use [*FileStream Class*](https://docs.microsoft.com/en-us/dotnet/api/system.io.filestream) para el archivo PDF de salida."
item5: "[*PdfDevice Class*](https://reference.aspose.com/page/net/aspose.page.eps.device/pdfdevice/) al inicializar con el objeto de secuencia de archivos PDF de salida."
item6: "Llame a [*PsDocument.Save*](https://reference.aspose.com/page/net/aspose.page.eps/psdocument/save/) para la conversión de PDF."
---

{{<section feature2>}}
---
title: Conversión de PostScript a Imágenes a través de C# .NET.
h3: "Código C# para la conversión de PostScript a imágenes"
item1: "Para cualquier aplicación de conversión de EPS/PS PostScript a imagen, el siguiente código C# funciona bien, así que siga los siguientes pasos:"
item2: Cargue el documento usando la clase PsDocument que tiene el flujo de archivo de entrada como parámetro.
item3: "Cree el objeto [*ImageSaveOptions Class*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/imagesaveoptions/) e inicialícelo con la configuración requerida."
item4: Guarde cada página del archivo de entrada en una imagen PNG, JPG, TIFF, BMP, etc.
---

{{<section feature3>}}
---
title: Convierta XPS a imágenes JPG, PNG, BMP a través de C# .NET.
h3: "Código C# para conversión de XPS a imagen"
item1: ".NET API también admite la conversión de XPS a imágenes BMP, JPG, PNG, TIFF, etc., y proporciona la clase XpsDocument para operaciones XPS. Para convertir XPS a imagen, siga los siguientes pasos:"
item2: Cargue el archivo XPS de la transmisión.
item3: "Inicialice las opciones de guardado de imágenes relevantes, por ejemplo, para **XPS a JPG** es [*JpegSaveOptions*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions/) y para **XPS a PNG** sus [*PngSaveOptions*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions/). Aquí hay una lista de todos los XPS a imagen [*opciones de guardado*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/)."
item4: Defina configuraciones relevantes como SmoothingMode, Resolution y PageNumbers, etc. para renderizar. Finalmente, recorra las particiones de documentos para guardarlas en imágenes.
---
