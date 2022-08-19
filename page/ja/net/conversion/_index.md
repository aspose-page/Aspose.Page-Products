---
translation: true
template: /_templates/_conversion-net.md
title: PDL 変換 API C# | .NET
url: /net/conversion/
description: Aspose.Page PDL 変換機能を備えた .NET ライブラリを使用して、PS、EPS、および XPS を BMP、JPG、PNG、および TIFF を含む PDF および画像に変換します。
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: PS、EPS、および XPS を変換する
h2: .NET 用の PS、EPS、および XPS コンバーター API ソリューション。
---

{{<section overview>}}
---
p1: "PostScript PS および Encapsulated PostScript EPS ファイルと XPS ドキュメントをプログラムで変換する必要がある場合はいつでも、.NET API でスムーズに変換でき、複数のファイルを変換できます。 PS および EPS の場合、API はレベル 1 ～ 3 の PostScript オペレーターとほとんどの EPS ヘッダー コメントをサポートし、いくつかのフォント ケースを除いて最大限の適合性を持つ PostScript ドキュメントを変換し、API は Time New Roman などのフォントを扱います。"
p2: "さらに、XPS ファイル変換の場合、API はページの追加または削除、キャンバス、パス、およびグリフ要素の処理、ベクター グラフィックス形状の作成、テキスト文字列の作成、XPS アウトライン アイテムの変換などを行うことができます。"
p3: "ここにある .NET の API ソリューションを使用すると、PS、EPS、XPS などの PDL 形式のファイルをプログラムで変換できますが、これらのネイティブ API で開発されたクロスプラットフォームを確認して試すと役立つ場合があります。"
---

{{<section feature1>}}
---
title: C# .NET による PostScript から PDF への変換。
h3: "PS EPS から PDF への変換用の C# コード"
item1: "PostScript PS および Encapsulated PostScript EPS ファイルを .NET API 経由で PDF に変換するには、次の手順を実行する必要があります。"
item2: "[*PsDocument クラス*](https://reference.aspose.com/page/net/aspose.page.eps/psdocument/) を使用して PS または EPS ファイルを読み込みます。"
item3: "[*PdfSaveOptions クラス*](https://reference.aspose.com/page/net/aspose.page.eps.device/pdfsaveoptions/)を使用して PDF 保存を設定します。"
item4: "出力 PDF ファイルには [*FileStream Class*](https://docs.microsoft.com/en-us/dotnet/api/system.io.filestream) を使用します。"
item5: "[*PdfDevice クラス*](https://reference.aspose.com/page/net/aspose.page.eps.device/pdfdevice/) 出力 PDF ファイルストリーム オブジェクトで初期化することにより。"
item6: "[*PsDocument.Save*](https://reference.aspose.com/page/net/aspose.page.eps/psdocument/save/) を呼び出して PDF に変換します。"
---

{{<section feature2>}}
---
title: C# .NET による PostScript から画像への変換。
h3: "PostScript から画像への変換用の C# コード"
item1: "EPS/PS PostScript から画像へのコンバーター アプリケーションでは、次の C# コードが適切に機能するため、次の手順を実行します。"
item2: 入力ファイル ストリームをパラメーターとして持つ PsDocument クラスを使用してドキュメントを読み込みます。
item3: "[*ImageSaveOptions Class*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/imagesaveoptions/) オブジェクトを作成し、必要な設定で初期化します。"
item4: 各入力ファイル ページを画像 PNG、JPG、TIFF、BMP などに保存します。
---

{{<section feature3>}}
---
title: XPS を C# .NET 経由で画像 JPG、PNG、BMP に変換します。
h3: "XPS から画像への変換用の C# コード"
item1: ".NET API は、画像 BMP、JPG、PNG、TIFF などへの XPS 変換もサポートし、XPS 操作用の XpsDocument クラスを提供します。 XPS を画像に変換するには、次の手順を実行します。"
item2: ストリームから XPS ファイルを読み込みます。
item3: "関連する画像保存オプションを初期化します。たとえば、**XPS から JPG** の場合は [*JpegSaveOptions*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions/) です。 **XPS から PNG** の場合は、その [*PngSaveOptions*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/jpegsaveoptions/)。すべての XPS to Image [*保存オプション*](https://reference.aspose.com/page/net/aspose.page.xps.presentation.image/) のリストを次に示します。"
item4: SmoothingMode、Resolution、PageNumbers など、レンダリングに関連する設定を定義します。最後に、ドキュメント パーティションを反復処理して、それらを画像に保存します。
---
