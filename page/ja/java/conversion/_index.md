---
translation: true
template: /_templates/_conversion-java.md
title: PDL 変換 API | Java
url: /java/conversion/
description: Aspose.Page PDL 変換機能を備えた Java ライブラリを使用して、PS、EPS、および XPS を BMP、JPG、PNG、および TIFF を含む PDF および画像に変換します。
family: page
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: PS、EPS、および XPS を変換する
h2: PS、EPS、および XPS コンバーター Java 用 API ソリューション
---

{{<section overview>}}
---
p1: "PostScript PS および Encapsulated PostScript EPS ファイル、XPS ドキュメントをプログラムで変換する必要がある場合はいつでも、Java API を使用するとスムーズに変換でき、複数のファイルを変換できます。 PS および EPS の場合、API はレベル 1 ～ 3 の PostScript オペレーターとほとんどの EPS ヘッダー コメントをサポートし、いくつかのフォント ケースを除いて最大限の適合性を持つ PostScript ドキュメントを変換し、API は Time New Roman などのフォントを扱います。"
p2: "さらに、XPS ファイル変換の場合、API はページの追加または削除、キャンバス、パス、およびグリフ要素の処理、ベクター グラフィックス形状の作成、テキスト文字列の作成、XPS アウトライン アイテムの変換などを行うことができます。"
p3: "ここにある Java の API ソリューションを使用すると、PS、EPS、XPS などの PDL 形式のファイルをプログラムで変換できますが、これらのネイティブ API で開発されたクロスプラットフォームを確認して試すことが役立つ場合があります。"
---

{{<section feature1>}}
---
title: Java による PostScript から PDF への変換。
h3: "PS EPS を PDF に変換する Java コード"
item1: "PostScript PS および Encapsulated PostScript EPS ファイルを Java API 経由で PDF に変換するには、次の手順を実行する必要があります。"
item2: "[*PsDocument クラス*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument) を使用して PS または EPS ファイルを読み込みます。"
item3: "[*PdfSaveOptions Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfSaveOptions) を使用して PDF 保存オプションを設定します。"
item4: "出力PDFファイルには[*FileStream Class*](https://docs.oracle.com/javase/7/docs/api/java/io/FileOutputStream.html)を使用します。"
item5: "FileOutputStream オブジェクトをパラメーターとして持つ [*PdfDevice Class*](https://reference.aspose.com/page/java/com.aspose.eps.device/PdfDevice) を使用します。"
item6: "[*PsDocument.Save*](https://reference.aspose.com/page/java/com.aspose.eps/PsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) ファイルを PDF に保存します。"
---

{{<section feature2>}}
---
title: Java による PostScript から画像への変換。
h3: "PostScript から画像への変換用の Java コード"
item1: "EPS/PS PostScript から画像へのコンバーター アプリケーションでは、次の Java コードが適切に機能するため、次の手順を実行します。"
item2: PS ソース ファイルで入力ストリームを初期化します。
item3: "作成された PS 入力ストリームをパラメータとして [*PsDocument*](https://reference.aspose.com/page/java/com.aspose.eps/psdocument) オブジェクトを作成します。"
item4: "[*ImageSaveOptions*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagesaveoptions) を使用して、AdditionalFontsFolder や SuppressError などを指定します。"
item5: "[*ImageDevice*](https://reference.aspose.com/page/java/com.aspose.eps.device/imagedevice) オブジェクトを使用して、必要に応じてイメージのタイプとサイズを指定します。"
item6: PS/EPS ファイルを次の名前で保存し、イメージをバイト配列の配列としてイメージ保存オプションで保存します。入力ファイルの 1 ページの 1 つのバイト配列。
---


{{<section feature3>}}
---
title: XPS を Java 経由で画像 JPG、PNG、BMP に変換します。
h3: XPS から画像への変換用の Java コード
item1: "Java API は、ページ レイアウトを表すために使用される XPS 形式を扱います。どのようなシナリオでも、プログラムで XPS を画像 BMP、JPG、PNG、および TIFF に変換する必要がある場合はいつでも、次のコードを Java アプリケーション内に簡単に統合できます。"
item2: "[*XpsDocument クラス*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument) を使用して、XPS ドキュメントを読み込みます。"
item3: "[*PngSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PngSaveOptions)、[*JpegSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/JpegSaveOptions)、[*BmpSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/BmpSaveOptions) 、[*TiffSaveOptions*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/TiffSaveOptions) で画像の追加設定を行います。"
item4: "[*イメージ デバイス*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/ImageDevice) クラス インスタンスを作成します。"
item5: "[*XpsDocument.save*](https://reference.aspose.com/page/java/com.aspose.xps/XpsDocument#save-com.aspose.page.Device-com.aspose.page.SaveOptions-) 変換された JPEG 画像を ImageDevice オブジェクトに保存し、次に ImageDevice を使用して画像を JPG として保存します。"
---

{{<section feature4>}}
---
title: Java 経由で XPS を PDF に変換します。
h3: XPS から PDF への変換用の Java コード
item1: プログラムで XPS を PDF ドキュメントに変換するプロセスは簡単で、入力ファイルと出力ファイル間で忠実度の高い結果が得られます。
item2: "XpsDocument クラスを使用してファイルを読み込みます。 [*PdfSaveOptions クラス*](https://reference.aspose.com/page/java/com.aspose.xps.rendering/PdfDevice) オブジェクトを初期化します。"
item3: レンダリング用の PdfDevice オブジェクトを作成し、最後に出力 PDF ドキュメントを保存します。
---


