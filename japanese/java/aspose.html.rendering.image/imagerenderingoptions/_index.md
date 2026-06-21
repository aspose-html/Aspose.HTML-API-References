---
title: "ImageRenderingOptions クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.rendering.image.ImageRenderingOptions クラス。ImageDevice のレンダリング オプションを表します。このオプションは、出力画像の形式、圧縮、解像度などを指定するために使用されます"
type: docs

url: /ja/java/com.aspose.html.rendering.image/imagerenderingoptions/
---
## ImageRenderingOptions class

[`ImageDevice`](../imagedevice/) 用のレンダリング オプションを表します。このオプションは、出力画像の形式、圧縮、解像度などを指定するために使用されます。

```java
public class ImageRenderingOptions : RenderingOptions
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ImageRenderingOptions](imagerenderingoptions/#constructor)() | `ImageRenderingOptions` クラスの新しいインスタンスを初期化します。デフォルトの画像形式として Png が使用されます。 |
| [ImageRenderingOptions](imagerenderingoptions/#constructor_1)(ImageFormat) | 指定された画像形式で `ImageRenderingOptions` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
[getBackgroundColor]
[setBackgroundColor] Gets or sets Color which will fill background of every page. Default value is Transparent. |
[getCompression]
[setCompression] Sets or gets Tagged Image File Format (TIFF) [`Compression`](../compression/). By default this property is LZW. |
| [getCss](../../com.aspose.html.rendering/renderingoptions/css/) CSS プロパティの処理設定に使用される [`CssOptions`](../../com.aspose.html.rendering/cssoptions/) オブジェクトを取得します。 |
[getFormat]
[setFormat] Sets or gets [`ImageFormat`](../imageformat/). By default this property is Png. |
| [horizontalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | 出力および内部（フィルタ処理中に使用される）画像の水平解像度をピクセル/インチで設定または取得します。デフォルトは 300 dpi です。 |
| [getPageSetup](../../com.aspose.html.rendering/renderingoptions/pagesetup/) 出力ページ設定の構成に使用されるページ設定オブジェクトを取得します。 |
| [getText](../../com.aspose.html.rendering.image/imagerenderingoptions/text/) テキストレンダリングの構成に使用される [`TextOptions`](../textoptions/) オブジェクトを取得します。 |
[getUseAntialiasing]
[setUseAntialiasing] Specifies whether to use antialiasing. By default, antialiasing is enabled. |
| [verticalResolution](../../com.aspose.html.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | 出力および内部（フィルタ処理中に使用される）画像の垂直解像度をピクセル/インチで設定または取得します。デフォルトは 300 dpi です。 |

### 関連項目

* class [RenderingOptions](../../com.aspose.html.rendering/renderingoptions/)
* package [com.aspose.html.rendering.image](../../com.aspose.html.rendering.image/)
* package [Aspose.HTML](../../)
