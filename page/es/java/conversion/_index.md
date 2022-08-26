---
translation: true
template: /_templates/_conversion-java.md
title: API de conversión de PDL | Java
url: /java/conversion/
description: Convierta PS, EPS y XPS a PDF e imágenes, incluidos BMP, JPG, PNG y TIFF, utilizando la biblioteca Java con la función de conversión PDL de Aspose.Page.
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: Convierte PS, EPS y XPS
h2: Solución API de conversión de PS, EPS y XPS para Java
---

{{<section overview>}}
---
p1: "Siempre que sea necesario convertir archivos PostScript PS y PostScript EPS encapsulados, así como documentos XPS programáticamente, la API de Java puede hacerlo sin problemas y convertir múltiples archivos. Para PS y EPS, la API admite operadores PostScript de niveles 1 a 3 y la mayoría de los comentarios de encabezado de EPS, así como también transforma documentos PostScript con la máxima conformidad con la excepción de algunos casos de fuentes y la API trata fuentes como Time New Roman."
p2: "Además, para la transformación de archivos XPS, la API puede agregar o eliminar páginas, manejar lienzos, rutas y elementos de glifos, crear formas de gráficos vectoriales, cadenas de texto, convertir elementos de esquema XPS y más."
p3: "La solución de API para Java aquí le permite convertir archivos de formatos PDL como PS, EPS y XPS mediante programación, pero puede resultarle útil ver y probar el desarrollo multiplataforma en estas API nativas."
---

{{<section feature1>}}
---
title: Conversión de PostScript a PDF a través de Java.
h3: "Código Java para convertir PS EPS a PDF"
item1: "Para convertir archivos PostScript PS y PostScript encapsulado EPS a PDF a través de la API de Java, debe seguir los siguientes pasos:"
item2: "Cargue el archivo PS o EPS usando [*PsDocument Class*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument)."
item3: "Configure las opciones de guardado de PDF usando [*PdfSaveOptions Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfSaveOptions)."
item4: "Use [*FileStream Class*](https://docs.oracle.com/javase/7/docs/api/java/io/FileOutputStream.html) para el archivo PDF de salida."
item5: "Utilice [*PdfDevice Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfDevice) con el objeto FileOutputStream como parámetro."
item6: "Llame a [*PsDocument.Save*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) para guardar en PDF el archivo."
---

{{<section feature2>}}
---
title: Conversión de PostScript a Imágenes a través de Java.
h3: "Código Java para conversión de PostScript a imágenes"
item1: "Para cualquier aplicación de conversión de EPS/PS PostScript a imagen, el siguiente código Java funciona bien, así que siga los siguientes pasos:"
item2: Inicialice el flujo de entrada con el archivo fuente PS.
item3: "Cree el objeto [*PsDocument*](https://reference.aspose.com/page/java/com.aspose.eps/psdocument) con el flujo de entrada PS creado como parámetro"
item4: "Use [*ImageSaveOptions*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagesaveoptions) para especificar AdditionalFontsFolder y SuppressError, etc."
item5: "Use el objeto [*ImageDevice*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagedevice) para especificar un tipo y tamaño de imagen si es necesario."
item6: Guarde el archivo PS/EPS como una imagen con las opciones de guardado de una imagen como una matriz de matrices de bytes. Una matriz de bytes para una página de un archivo de entrada.
---


{{<section feature3>}}
---
title: Convierta XPS a imágenes JPG, PNG, BMP a través de Java.
h3: Código Java para conversión de XPS a imagen
item1: "La API de Java trata el formato XPS que se utiliza para representar el diseño de la página. En cualquier escenario, siempre que sea necesario convertir XPS a imágenes BMP, JPG, PNG y TIFF mediante programación, el siguiente código se puede integrar fácilmente en la aplicación Java."
item2: "Use [*XpsDocument class*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument) para cargar el documento XPS."
item3: "Utilice la clase de opción de imagen relevante, como [*PngSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PngSaveOptions), [*JpegSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/JpegSaveOptions), [*BmpSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/BmpSaveOptions) , [*TiffSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/TiffSaveOptions) para configuraciones adicionales de imagen."
item4: "Cree la instancia de clase [*dispositivo de imagen*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/ImageDevice)."
item5: "Llame al [*XpsDocument.save*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) para guardar la imagen JPEG convertida en un objeto ImageDevice y luego use ImageDevice para guardar la imagen como JPG."
---

{{<section feature4>}}
---
title: Convierta XPS a PDF a través de Java.
h3: Código Java para la conversión de XPS a PDF
item1: El proceso de convertir documentos XPS a PDF mediante programación es simple y tiene resultados de alta fidelidad entre los archivos de entrada y salida.
item2: "Cargue el archivo usando la clase XpsDocument. Inicialice el objeto [*PdfSaveOptions class*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PdfDevice)."
item3: Cree el objeto PdfDevice para renderizar y, por último, guarde el documento PDF de salida.
---


