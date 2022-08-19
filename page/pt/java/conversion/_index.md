---
translation: true
template: /_templates/_conversion-java.md
title: API de conversão de PDL | Java
url: /java/conversion/
description: Converta PS, EPS e XPS para PDF e Imagens, incluindo BMP, JPG, PNG e TIFF usando a biblioteca Java com a funcionalidade de conversão Aspose.Page PDL.
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: Converter PS, EPS e XPS
h2: Solução de API do conversor PS, EPS e XPS para Java
---

{{<section overview>}}
---
p1: "Sempre que houver necessidade de converter arquivos PostScript PS e Encapsulated PostScript EPS, bem como documentos XPS programaticamente, a API Java pode fazer isso sem problemas e converter vários arquivos. Para PS e EPS, a API suporta operadores PostScript de níveis 1-3 e a maioria dos comentários de cabeçalho EPS, bem como transforma documentos PostScript com conformidade máxima, com exceção de alguns casos de fontes e a API lida com fontes como Time New Roman."
p2: "Além disso, para a transformação de arquivos XPS, a API pode adicionar ou remover páginas, lidar com telas, caminhos e elementos de glifos, criar formas de gráficos vetoriais, cadeias de texto, converter itens de contorno XPS e muito mais."
p3: "A solução de API para Java aqui permite converter arquivos de formatos PDL como PS, EPS e XPS programaticamente, mas você pode achar útil ver e experimentar a plataforma cruzada desenvolvida nessas APIs nativas."
---

{{<section feature1>}}
---
title: Conversão de PostScript para PDF via Java.
h3: "Código Java para converter PS EPS para PDF"
item1: "Para converter arquivos PostScript PS e Encapsulated PostScript EPS para PDF via API Java, você precisa seguir os seguintes passos:"
item2: "Carregue o arquivo PS ou EPS usando [*PsDocument Class*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument)."
item3: "Defina as opções de salvamento de PDF usando [*PdfSaveOptions Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfSaveOptions)."
item4: "Use [*FileStream Class*](https://docs.oracle.com/javase/7/docs/api/java/io/FileOutputStream.html) para o arquivo PDF de saída."
item5: "Use [*PdfDevice Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfDevice) tendo o objeto FileOutputStream como parâmetro."
item6: "Chame o [*PsDocument.Save*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) para salvar em PDF o arquivo."
---

{{<section feature2>}}
---
title: PostScript para conversão de imagens via Java.
h3: "Código Java para conversão de PostScript para imagens"
item1: "Para qualquer aplicativo conversor EPS/PS PostScript para imagem, o código Java a seguir funciona bem, portanto, execute as próximas etapas:"
item2: Inicialize o fluxo de entrada com o arquivo de origem PS.
item3: "Criar objeto [*PsDocument*](https://reference.aspose.com/page/java/com.aspose.eps/psdocument) com o fluxo de entrada PS criado como parâmetro"
item4: "Use [*ImageSaveOptions*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagesaveoptions) para especificar AdditionalFontsFolder e SuppressError etc."
item5: "Use o objeto [*ImageDevice*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagedevice) para especificar um tipo e tamanho de imagem, se necessário."
item6: Salve o arquivo PS/EPS como uma imagem com opções de salvamento de imagem como uma matriz de matrizes de bytes. Uma matriz de bytes para uma página de um arquivo de entrada.
---


{{<section feature3>}}
---
title: Converta XPS para imagens JPG, PNG, BMP via Java.
h3: Código Java para conversão de XPS em imagem
item1: "A API Java lida com o formato XPS que é usado para representar o layout da página. Em qualquer cenário, sempre que houver a necessidade de converter XPS em imagens BMP, JPG, PNG e TIFF programaticamente, o código a seguir pode ser facilmente integrado ao aplicativo Java."
item2: "Use [*XpsDocument class*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument) para carregar o documento XPS."
item3: "Use a classe de opção de imagem relevante, como [*PngSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PngSaveOptions), [*JpegSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/JpegSaveOptions), [*BmpSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/BmpSaveOptions) , [*TiffSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/TiffSaveOptions) para configurações adicionais de imagem."
item4: "Crie a instância da classe [*image device*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/ImageDevice)."
item5: "Chame o [*XpsDocument.save*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) para salvar a imagem JPEG convertida no objeto ImageDevice e, em seguida, use ImageDevice para salvar a imagem como JPG."
---

{{<section feature4>}}
---
title: Converta XPS para PDF via Java.
h3: Código Java para conversão de XPS para PDF
item1: O processo de conversão de documentos XPS para PDF programaticamente é simples, com resultados de alta fidelidade entre os arquivos de entrada e saída.
item2: "Carregue o arquivo usando a classe XpsDocument. Inicialize o objeto [*PdfSaveOptions class*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PdfDevice)."
item3: Crie o objeto PdfDevice para renderização e, por último, salve o documento PDF de saída.
---


