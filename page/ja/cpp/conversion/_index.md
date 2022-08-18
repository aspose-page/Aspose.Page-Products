---
translation: true
template: /_templates/_conversion-cpp.md
title: PDL 変換 API | C++
url: /cpp/conversion/
description: Aspose.Page PDL 変換機能を備えた C++ ライブラリを使用して、PS、EPS、および XPS を BMP、JPG、PNG、および TIFF を含む PDF および画像に変換します。
family: page
platformtag: cpp
feature: conversion
---

{{<section banner>}}
---
h1: PS、EPS、および XPS を変換する
h2: C++ 用の PS、EPS、および XPS コンバーター API ソリューション。
---

{{<section overview>}}
---
p1: "PostScript PS および Encapsulated PostScript EPS ファイル、XPS ドキュメントをプログラムで変換する必要がある場合はいつでも、Java API を使用するとスムーズに変換でき、複数のファイルを変換できます。 PS および EPS の場合、API はレベル 1 ～ 3 の PostScript オペレーターとほとんどの EPS ヘッダー コメントをサポートし、いくつかのフォント ケースを除いて最大限の適合性を持つ PostScript ドキュメントを変換し、API は Time New Roman などのフォントを扱います。"
p2: "プログラマーは、PostScript および XPS ドキュメントのバッチ処理に簡単に使用でき、キャンバス、パス、グリフ要素を操作したり、ベクター グラフィックスの形状やテキスト文字列を処理したりすることもできます。"
p3: "ここにある Java の API ソリューションを使用すると、PS、EPS、XPS などの PDL 形式のファイルをプログラムで変換できますが、これらのネイティブ API で開発されたクロスプラットフォームを確認して試すことが役立つ場合があります。 EPS から画像、EPS から PDF、PostScript から PDF、PostScript から画像、XPS から画像、XPS から PDF などの変換シナリオをいくつか示します。"
---

{{<section feature1>}}
---
title: EPS を C++ 経由で画像に変換します。
h3: EPS から画像への変換用の C++ コード
item1: "C++ ライブラリを使用すると、Windows および Linux プラットフォームで Encapsulated PostScript (EPS) ファイルを画像に変換できます。プロセスは次のとおりです。"
item2: "FileStream を使用して、EPS ファイルの入力ストリームを作成し、入力ストリームを持つ [*PsDocument クラス*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.ps_document) オブジェクトを作成します。パラメータとして。イメージ固有の設定については、[*ImageSaveOptions クラス*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_save_options) を使用します。"
item3: "[*ImageDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.image_device) を使用して、イメージのタイプとサイズを定義します。"
item4: バイト配列ごとに新しいファイル出力ストリームを作成するバイト配列の配列への画像保存オプションを使用して、EPS を画像として保存します。
---


{{<section feature2>}}
---
title: Java による PostScript から PDF への変換。
h3: PostScript から PDF への変換用の C++ コード
item1: "PostScript を PDF に変換するプロセスは、EPS を画像に変換するプロセスと同じですが、開発者が [*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device) を使用する点が異なります。 .pdf_save_options) を使用して、AdditionalFontsFolder や SuppressError 値などの追加設定を定義します。さらに、[*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.e_p_s.device.pdf_device) 作成された出力ストリームから。"
---

{{<section feature3>}}
---
title: C++ 経由で XPS を PDF に変換します。
h3: XPS から PDF への変換用の C++ コード
item1: "C++ XPS Processing API は、XPS から BMP、JPG、TIFF、PNG などの画像への変換、および Windows および Linux ベースのシステムでの XPS から PDF への変換を処理します。 XPS を PDF に変換するプロセスは次のとおりです。"
item2: 出力ストリームを定義し、入力 XPS ドキュメントの入力ストリームを定義します。
item3: "[*XpsDocument クラス*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.xps_document) オブジェクトにパラメーターとして渡します。"
item4: "[*PdfSaveOptions*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_save_options) を使用して、TextCompression、ImageCompression、JpegQualityLevel などの PDF 固有の保存オプションを指定します。"
item5: "以前に作成した出力ストリームから [*PdfDevice*](https://reference.aspose.com/page/cpp/class/aspose.page.x_p_s.presentation.pdf.pdf_device) のインスタンスを作成します。"
item6: 最後に、PDF 保存オプションを使用して XPS ドキュメントを PDF として変換します。
---
