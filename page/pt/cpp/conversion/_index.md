---
translation: true
template: /_templates/_conversion-cpp.md
title: API de conversão de PDL | C++
url: /cpp/conversion/
description: Converta PS, EPS e XPS para PDF e Imagens incluindo BMP, JPG, PNG e TIFF usando a biblioteca C++ com a funcionalidade de conversão Aspose.Page PDL.
family: page
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: Converter PS, EPS e XPS
h2: Solução de API do conversor PS, EPS e XPS para C++.
---

{{<section overview>}}
---
p1: "Sempre que houver necessidade de converter arquivos PostScript PS e Encapsulated PostScript EPS, bem como documentos XPS programaticamente, a API Java pode fazer isso sem problemas e converter vários arquivos. Para PS e EPS, a API suporta operadores PostScript de níveis 1-3 e a maioria dos comentários de cabeçalho EPS, bem como transforma documentos PostScript com conformidade máxima, com exceção de alguns casos de fontes e a API lida com fontes como Time New Roman."
p2: "Os programadores podem usá-lo facilmente para processamento em lote de documentos PostScript e XPS, até mesmo manipular telas, caminhos e elementos de glifos e manipular formas de gráficos vetoriais e strings de texto."
p3: "A solução de API para Java aqui permite converter arquivos de formatos PDL como PS, EPS e XPS programaticamente, mas você pode achar útil ver e experimentar a plataforma cruzada desenvolvida nessas APIs nativas. Aqui estão alguns cenários de conversão, como EPS para Imagens, EPS para PDF, PostScript para PDF, PostScript para Imagens, XPS para Imagens e XPS para PDF"
---

{{<section feature1>}}
---
title: Converta EPS para Imagens via C++.
h3: Código C++ para conversão de EPS para imagens
item1: "A biblioteca C++ permite converter arquivos Encapsulated PostScript (EPS) em imagens nas plataformas Windows e Linux. O processo é:"
item2: "Use FileStream para criar o fluxo de entrada para o arquivo EPS, bem como para criar o objeto [*PsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.ps_document) com fluxo de entrada como parâmetro. Para configurações específicas de Imagens, use a [*Classe ImageSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_save_options)."
item3: "Defina o tipo e o tamanho da imagem usando [*ImageDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_device)."
item4: Salve EPS como imagens com opções de salvamento de imagem em uma matriz de matrizes de bytes, criando para cada matriz de bytes um novo fluxo de saída de arquivo.
---


{{<section feature2>}}
---
title: Conversão de PostScript para PDF via Java.
h3: Código C++ para conversão de PostScript para PDF
item1: "O processo de conversão de PostScript para PDF é o mesmo de EPS para Imagens, exceto que os desenvolvedores usarão [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_save_options) para definir configurações adicionais, como AdditionalFontsFolder e valor SuppressError etc. Além disso, usará [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_device) do fluxo de saída criado."
---

{{<section feature3>}}
---
title: Converta XPS para PDF via C++.
h3: Código C++ para conversão de XPS para PDF
item1: "C++ XPS Processing API lida com a conversão de XPS para imagens, incluindo BMP, JPG, TIFF, PNG e muito mais, bem como a conversão de XPS para PDF em sistemas baseados em Windows e Linux. O processo de conversão de XPS para PDF é:"
item2: Defina o fluxo de saída, bem como o fluxo de entrada para o documento XPS de entrada.
item3: "Passe-o como parâmetro para o objeto [*XpsDocument Class*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.xps_document)."
item4: "Especifique as opções de salvamento específicas do PDF, como TextCompression, ImageCompression e JpegQualityLevel usando [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_save_options)."
item5: "Crie uma instância de [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_device) do fluxo de saída criado anteriormente."
item6: Por fim, converta o documento XPS como PDF com as opções de salvamento de PDF.
---
