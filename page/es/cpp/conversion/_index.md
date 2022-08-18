---
translation: true
template: /_templates/_conversion-cpp.md
title: API de conversión de PDL | C++
url: /cpp/conversion/
description: Convierta PS, EPS y XPS a PDF e imágenes, incluidos BMP, JPG, PNG y TIFF, utilizando la biblioteca C++ con la función de conversión PDL de Aspose.Page.
family: page
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: Convierte PS, EPS y XPS
h2: Solución API de conversión de PS, EPS y XPS para C++.
---

{{<section overview>}}
---
p1: "Siempre que sea necesario convertir archivos PostScript PS y PostScript EPS encapsulados, así como documentos XPS programáticamente, la API de Java puede hacerlo sin problemas y convertir múltiples archivos. Para PS y EPS, la API admite operadores PostScript de niveles 1 a 3 y la mayoría de los comentarios de encabezado de EPS, además de transformar documentos PostScript con la máxima conformidad con la excepción de unos pocos casos de fuentes y la API trata fuentes como Time New Roman."
p2: "Los programadores pueden usarlo fácilmente para el procesamiento por lotes de documentos PostScript y XPS, incluso manipular elementos de lienzos, rutas y glifos y manejar formas de gráficos vectoriales y cadenas de texto."
p3: "La solución API para Java aquí le permite convertir archivos de formatos PDL como PS, EPS y XPS mediante programación, pero puede resultarle útil ver y probar el desarrollo multiplataforma en estas API nativas. Aquí hay algunos escenarios de conversión como EPS a imágenes, EPS a PDF, PostScript a PDF, PostScript a imágenes, XPS a imágenes y XPS a PDF."
---

{{<section feature1>}}
---
title: Convierta EPS a imágenes a través de C++.
h3: Código C++ para conversión de EPS a imágenes
item1: "La biblioteca C++ permite convertir archivos PostScript encapsulado (EPS) en imágenes en plataformas Windows y Linux. El proceso es:"
item2: "Use FileStream para crear el flujo de entrada para el archivo EPS, así como para crear el objeto [*PsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.ps_document) que tiene un flujo de entrada como parámetro. Para la configuración específica de imágenes, use [*ImageSaveOptions Class*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_save_options)."
item3: "Defina el tipo y el tamaño de la imagen mediante [*ImageDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_device)."
item4: Guarde EPS como imágenes con opciones para guardar imágenes en una matriz de matrices de bytes creando para cada matriz de bytes una nueva secuencia de salida de archivos.
---


{{<section feature2>}}
---
title: Conversión de PostScript a PDF a través de Java.
h3: Código C++ para la conversión de PostScript a PDF
item1: "El proceso de conversión de PostScript a PDF es el mismo que el de EPS a imágenes, excepto que los desarrolladores usarán [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_save_options) para definir configuraciones adicionales como AdditionalFontsFolder y SuppressError value, etc. Además, utilizará [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_device) del flujo de salida creado."
---

{{<section feature3>}}
---
title: Convierte XPS a PDF a través de C++.
h3: Código C++ para conversión de XPS a PDF
item1: "La API de procesamiento de XPS de C++ se ocupa de la conversión de XPS a imágenes, incluidos BMP, JPG, TIFF, PNG y más, así como la conversión de XPS a PDF en sistemas basados ​​en Windows y Linux. El proceso de conversión de XPS a PDF es:"
item2: Defina el flujo de salida y defina el flujo de entrada para el documento XPS de entrada.
item3: "Páselo como parámetro al objeto [*XpsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.xps_document)."
item4: "Especifique las opciones de guardado específicas de PDF, como TextCompression, ImageCompression y JpegQualityLevel usando [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_save_options)."
item5: "Cree una instancia de [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_device) a partir del flujo de salida creado anteriormente."
item6: Finalmente, convierta el documento XPS a PDF con las opciones de guardado de PDF.
---
