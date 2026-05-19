---
title: "PdfRenderingOptions クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.rendering.pdf.PdfRenderingOptions クラス。PdfDevice のレンダリングオプションを表します。"
type: docs

url: /ja/java/com.aspose.html.rendering.pdf/pdfrenderingoptions/
---
## PdfRenderingOptions class

[`PdfDevice`](../pdfdevice/) のレンダリングオプションを表します。

```java
public class PdfRenderingOptions : RenderingOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfRenderingOptions](pdfrenderingoptions/)() | `PdfRenderingOptions` クラスの新しいインスタンスを初期化します。 |

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

### 関連項目

* class [RenderingOptions](../../com.aspose.html.rendering/renderingoptions/)
* package [com.aspose.html.rendering.pdf](../../com.aspose.html.rendering.pdf/)
* package [Aspose.HTML](../../)
