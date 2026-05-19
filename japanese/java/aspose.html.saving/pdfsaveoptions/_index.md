---
title: "PdfSaveOptions クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.saving.PdfSaveOptions クラス。特定のデータクラスは、変換結果を管理するためのいくつかのプロパティを提供します。例えば PageSetup はページの特性を指定します。ドキュメント記事を参照してください"
type: docs

url: /ja/java/com.aspose.html.saving/pdfsaveoptions/
---
## PdfSaveOptions class

特定のデータクラスは、変換結果を管理するためのいくつかのプロパティを提供します。例えば [`PageSetup`](../../com.aspose.html.rendering/pagesetup/) はページの特性を指定します。ドキュメントの [記事](https://docs.aspose.com/html/net/converting-between-formats/html-to-pdf/#convert-html-to-pdf-using-pdfsaveoptions) を参照してください。

```java
public class PdfSaveOptions : PdfRenderingOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | デフォルトコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) は、css プロパティ処理の構成に使用される [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) オブジェクトを取得します。 |
| [getDocumentInfo](../../com.aspose.html.rendering.pdf/pdfrenderingoptions/documentinfo/) は、出力 PDF ドキュメントに関する情報を含みます。 |
[getEncryption]
[setEncryption] Gets or sets a encryption details. If not set, then no encryption will be performed. |
[getFormFieldBehaviour]
[setFormFieldBehaviour] Specifies the behavior of form fields in the output PDF document. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | 内部画像（フィルタ処理中に使用される）の水平解像度を設定または取得します。単位はインチあたりピクセルです。デフォルトではこのプロパティは 300 dpi です。 |
[getIsTaggedPdf]
[setIsTaggedPdf] Creates a tag structure if `true`. |
[getJpegQuality]
[setJpegQuality] Specifies the quality of JPEG compression for images (if JPEG compression is used). Default is 95. |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) は、出力ページ設定の構成に使用されるページ設定オブジェクトを取得します。 |
| [verticalResolution](../../com.aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | 内部画像（フィルタ処理中に使用される）の垂直解像度を設定または取得します。単位はインチあたりピクセルです。デフォルトではこのプロパティは 300 dpi です。 |

## Remarks

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) で見つけることができます。

## 例

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.saving;
import System;
...
 	 // ソース HTML ファイルへのパスを準備します
      String documentPath = Path.Combine(DataDir, "drawing.html");

      // 変換後のファイル保存用パスを準備する
      String savePath = Path.Combine(OutputDir, "drawing-options.pdf");

      // ファイルから HTML ドキュメントを初期化します
      using var document = new HTMLDocument(documentPath);

      // PdfSaveOptions を初期化します。ページサイズ 600x300 ピクセル、余白を設定し、
      // 解像度を設定し、背景色を AliceBlue に変更します。
      var options = new PdfSaveOptions()
      {         
        HorizontalResolution = 200,
        VerticalResolution = 200,
        BackgroundColor = Color.AliceBlue,
        JpegQuality = 100
      };
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(600, 300), new Margin(20, 10, 10, 10));      

      // HTML を PDF に変換
      Converter.ConvertHTML(document, options, savePath);
```

### 関連項目

* class [PdfRenderingOptions](../../com.aspose.html.rendering.pdf/pdfrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
