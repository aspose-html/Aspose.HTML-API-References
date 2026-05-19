---
title: "DocSaveOptions クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.saving.DocSaveOptions クラス。特定のオプションデータクラスです。プロパティを設定することで、解像度、ページサイズ、背景色などのレンダリング特性や、フォント埋め込みといったドキュメント固有のオプションを管理できます。詳細はドキュメント記事をご覧ください"
type: docs

url: /ja/java/com.aspose.html.saving/docsaveoptions/
---
## DocSaveOptions class

特定のオプションデータクラスです。プロパティを設定することで、解像度、ページサイズ、背景色などのレンダリング特性や、フォント埋め込みなどのドキュメント固有のオプションを管理できます。詳細はドキュメントの [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-docx/#save-options) をご覧ください。

```java
public class DocSaveOptions : DocRenderingOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [DocSaveOptions](docsaveoptions/)() | デフォルトコンストラクタ。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) は、css プロパティ処理の構成に使用される [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) オブジェクトを取得します。 |
[getDocumentFormat]
[setDocumentFormat] Gets or sets the file format of the output document. The default value is DOCX. |
[getFontEmbeddingRule]
[setFontEmbeddingRule] Gets or sets the font embedding rule. The default value is None. |
| [horizontalResolution](../../com.aspose.html.rendering/renderingoptions/horizontalresolution/) { get; set; } | 内部画像（フィルタ処理中に使用される）の水平解像度を設定または取得します。単位はインチあたりピクセルです。デフォルトではこのプロパティは 300 dpi です。 |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) は、出力ページ設定の構成に使用されるページ設定オブジェクトを取得します。 |
| [verticalResolution](../../com.aspose.html.rendering/renderingoptions/verticalresolution/) { get; set; } | 内部画像（フィルタ処理中に使用される）の垂直解像度を設定または取得します。単位はインチあたりピクセルです。デフォルトではこのプロパティは 300 dpi です。 |

## Remarks

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.drawing;
import com.aspose.html.saving;
import System;
...
 // ソース HTML ファイルへのパスを準備します
      String documentPath = Path.Combine(DataDir, "canvas.html");

      // 変換後のファイル保存用パスを準備する
      String savePath = Path.Combine(OutputDir, "canvas-output-options.docx");

      // ファイルから HTML ドキュメントを初期化します
      using var document = new HTMLDocument(documentPath);

      // DocSaveOptions を初期化します。ページサイズを 600x400 ピクセル、余白を設定します
      var options = new DocSaveOptions();
      options.PageSetup.AnyPage = new Page(new com.aspose.html.drawing.Size(600, 400), new Margin(10, 10, 10, 10));

      // HTML を DOCX に変換
      Converter.ConvertHTML(document, options, savePath);
```

*OutputDir - custom output folder path.

### 関連項目

* class [DocRenderingOptions](../../com.aspose.html.rendering.doc/docrenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
