---
translation: true
template: /_templates/_conversion-net.md
title: API de conversão PDL C# | .NET
url: /net/conversion/
description: Converta PS, EPS e XPS para PDF e Imagens incluindo BMP, JPG, PNG e TIFF usando a biblioteca .NET com a funcionalidade de conversão Aspose.Page PDL.
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: Converter PS, EPS e XPS
h2: Solução de API do conversor PS, EPS e XPS para .NET.
---

{{<section overview>}}
---
p1: "Sempre que houver necessidade de converter arquivos PostScript PS e PostScript EPS encapsulados, bem como documentos XPS programaticamente, a API .NET pode fazer isso sem problemas e converter vários arquivos. Para PS e EPS, a API suporta operadores PostScript de níveis 1-3 e a maioria dos comentários de cabeçalho EPS, bem como transforma documentos PostScript com conformidade máxima, com exceção de alguns casos de fontes e a API lida com fontes como Time New Roman."
p2: "Além disso, para a transformação de arquivos XPS, a API pode adicionar ou remover páginas, lidar com telas, caminhos e elementos de glifos, criar formas de gráficos vetoriais, cadeias de texto, converter itens de contorno XPS e muito mais."
p3: "A solução API para .NET aqui permite converter arquivos de formatos PDL como PS, EPS e XPS programaticamente, mas você pode achar útil ver e experimentar multiplataformas desenvolvidas nessas APIs nativas."
---

{{<section feature1>}}
---
title: Conversão de PostScript para PDF via C# .NET.
h3: "Código C# para conversão de PS EPS para PDF"
item1: "Para converter arquivos PostScript PS e Encapsulated PostScript EPS para PDF via .NET API, você precisa seguir os seguintes passos:"
item2: "Carregue o arquivo PS ou EPS usando [*PsDocument Class*](https://reference.aspose.com/page/net/aspose.page.eps/psdocument/)."
item3: "Defina o salvamento do PDF usando [*PdfSaveOptions Class*](https://reference.aspose.com/page/net/aspose.page.eps.device/pdfsaveoptions/)."
item4: "Use [*FileStream Class*](https://docs.microsoft.com/en-us/dotnet/api/system.io.filestream) para o arquivo PDF de saída."
item5: "[*PdfDevice Class*](https://reference.aspose.com/page/net/aspose.page.eps.device/pdfdevice/) inicializando com o objeto de fluxo de arquivos PDF de saída."
item6: "Ligue para [*PsDocument.Save*](https://reference.aspose.com/page/net/aspose.page.eps/psdocument/save/) para conversão de PDF."
---

{{<section feature2>}}
---
title: PostScript para conversão de imagens via C# .NET.
h3: "Código C# para conversão de PostScript para imagens"
item1: "Para qualquer aplicativo conversor EPS/PS PostScript para imagem, o código C# a seguir funciona bem, portanto, execute as próximas etapas:"
item2: Carregue o documento usando a classe PsDocument tendo como parâmetro o fluxo do arquivo de entrada.
item3: "Crie o objeto [*ImageSaveOptions Class*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/imagesaveoptions/) e inicialize-o com as configurações necessárias."
item4: Salve cada página de arquivo de entrada em uma imagem PNG, JPG, TIFF, BMP, etc.
---

{{<section feature3>}}
---
title: Converta XPS para imagens JPG, PNG, BMP via C# .NET.
h3: "Código C# para conversão de XPS para imagem"
item1: "A API .NET também suporta a conversão de XPS para imagens BMP, JPG, PNG, TIFF, etc., e fornece a classe XpsDocument para operações XPS. Para converter XPS em Imagem, siga os próximos passos:"
item2: Carregue o arquivo XPS do fluxo.
item3: "Inicialize as opções de salvamento de imagem relevantes, por exemplo, para **XPS para JPG** é [*JpegSaveOptions*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions/) e para **XPS para PNG** suas [*PngSaveOptions*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions/). Aqui está uma lista de todos os XPS to Image [*save options*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/)."
item4: Defina configurações relevantes como SmoothingMode, Resolution e PageNumbers etc. para renderização. Por fim, itere através de partições de documentos para salvá-los em imagens.
---
