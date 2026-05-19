---
title: "ImageSaveOptions クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.saving.ImageSaveOptions クラス。特定のオプションデータクラスです。画像の結果の解像度、スムージング、品質、フォーマット、およびページ設定などを管理するプロパティを提供します。詳細はドキュメント記事で確認できます。"
type: docs

url: /ja/java/com.aspose.html.saving/imagesaveoptions/
---
## ImageSaveOptions class

特定のオプションデータクラスです。画像の結果解像度、スムージング品質、フォーマット、ページ設定などを管理するプロパティを提供します。詳細はドキュメントの [article](https://docs.aspose.com/html/net/converting-between-formats/html-to-jpg/#save-options) をご参照ください。

```java
public class ImageSaveOptions : ImageRenderingOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ImageSaveOptions](imagesaveoptions/#constructor)() | `ImageSaveOptions` クラスの新しいインスタンスを初期化します。デフォルトの画像フォーマットとして Png が使用されます。 |
| [ImageSaveOptions](imagesaveoptions/#constructor_1)(ImageFormat) | 初期化に基づく画像フォーマット [`ImageFormat`](../../com.aspose.html.rendering.image/imageformat/) |

## プロパティ

| 名前 | 説明 |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
[getCompression]
[setCompression] Sets or gets Tagged Image File Format (TIFF) [`Compression`](../../com.aspose.html.rendering.image/compression/). By default this property is LZW. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) は、css プロパティ処理の構成に使用される [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) オブジェクトを取得します。 |
[getFormat]
[setFormat] Sets or gets [`ImageFormat`](../../com.aspose.html.rendering.image/imageformat/). By default this property is Png. |
| [horizontalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | 出力および内部（フィルタ処理中に使用される）画像の水平解像度を設定または取得します（単位はインチあたりピクセル）。デフォルトではこのプロパティは 300 dpi です。 |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) は、出力ページ設定の構成に使用されるページ設定オブジェクトを取得します。 |
| [getText](../../com.aspose.html.rendering.image/imagerenderingoptions/text/) は、テキストレンダリングの構成に使用される [`TextOptions`](../../com.aspose.html.rendering.image/textoptions/) オブジェクトを取得します。 |
[getUseAntialiasing]
[setUseAntialiasing] Specifies whether to use antialiasing. By default, antialiasing is enabled. |
| [verticalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | 出力および内部（フィルタ処理中に使用される）画像の垂直解像度を設定または取得します（単位はインチあたりピクセル）。デフォルトではこのプロパティは 300 dpi です。 |

## Remarks

完全なサンプルとデータファイルは [GitHub](https://github.com/aspose-html/Aspose.HTML-Documentation/tree/main/content/tests-net) からダウンロードできます。

## 例

```java
import Aspose.Html;
import com.aspose.html.converters;
import com.aspose.html.drawing;
import com.aspose.html.rendering.image;
import com.aspose.html.saving;
...
      // ソース HTML ファイルへのパスを準備します
      String documentPath = Path.Combine(DataDir, "nature.html");

      // 変換後のファイル保存用パスを準備する
      String savePath = Path.Combine(OutputDir, "nature-output-options.png");

      // ファイルから HTML ドキュメントを初期化します
      using var document = new HTMLDocument(documentPath);

      // ImageSaveOptions を初期化します
      var options = new ImageSaveOptions()
      {
        SmoothingMode = SmoothingMode.Default,
        HorizontalResolution = 100,
        VerticalResolution = 100,
        BackgroundColor = Color.Beige
      };

      // HTML を PNG に変換
      Converter.ConvertHTML(document, options, savePath);
```

### 関連項目

* class [ImageRenderingOptions](../../com.aspose.html.rendering.image/imagerenderingoptions/)
* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
