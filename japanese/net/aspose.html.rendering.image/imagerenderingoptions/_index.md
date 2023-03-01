---
title: Class ImageRenderingOptions
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Rendering.Image.ImageRenderingOptions クラス. のレンダリング オプションを表しますImageDevice.このオプションは出力画像フォーマット圧縮解像度などを指定するために使用されます.
type: docs
weight: 4330
url: /ja/net/aspose.html.rendering.image/imagerenderingoptions/
---
## ImageRenderingOptions class

のレンダリング オプションを表します[`ImageDevice`](../imagedevice/).このオプションは、出力画像フォーマット、圧縮、解像度などを指定するために使用されます.

```csharp
public class ImageRenderingOptions : RenderingOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [ImageRenderingOptions](imagerenderingoptions/#constructor)() | の新しいインスタンスを初期化します`ImageRenderingOptions`クラス;Pngデフォルトの画像フォーマットとして使用されます. |
| [ImageRenderingOptions](imagerenderingoptions/#constructor_1)(ImageFormat) | の新しいインスタンスを初期化します`ImageRenderingOptions`指定された画像形式のクラス. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BackgroundColor](../../aspose.html.rendering/renderingoptions/backgroundcolor/) { get; set; } | 取得または設定Colorすべてのページの背景を塗りつぶします。デフォルト値はTransparent. |
| [Compression](../../aspose.html.rendering.image/imagerenderingoptions/compression/) { get; set; } | タグ付き画像ファイル形式 (TIFF) を設定または取得します[`Compression`](../compression/).デフォルトでは、このプロパティはLZW. |
| [Css](../../aspose.html.rendering/renderingoptions/css/) { get; } | を取得します[`CssOptions`](../../aspose.html.rendering/cssoptions/) css プロパティ処理の構成に使用されるオブジェクト. |
| [Format](../../aspose.html.rendering.image/imagerenderingoptions/format/) { get; set; } | 設定または取得[`ImageFormat`](../imageformat/).デフォルトでは、このプロパティはPng. |
| override [HorizontalResolution](../../aspose.html.rendering.image/imagerenderingoptions/horizontalresolution/) { get; set; } | 出力および内部 (フィルター処理中に使用される) 画像の水平解像度を、1 インチあたりのピクセル数で設定または取得します。デフォルトでは、このプロパティは 300 dpi. です。 |
| [PageSetup](../../aspose.html.rendering/renderingoptions/pagesetup/) { get; } | 設定出力ページ セットに使用されるページ設定オブジェクトを取得します。 |
| [SmoothingMode](../../aspose.html.rendering.image/imagerenderingoptions/smoothingmode/) { get; set; } | この Graphics のレンダリング品質を取得または設定します。 |
| [Text](../../aspose.html.rendering.image/imagerenderingoptions/text/) { get; } | を取得します[`TextOptions`](../textoptions/)テキストレンダリングの設定に使用されるオブジェクト. |
| override [VerticalResolution](../../aspose.html.rendering.image/imagerenderingoptions/verticalresolution/) { get; set; } | 出力および内部 (フィルター処理中に使用される) イメージの垂直解像度を、1 インチあたりのピクセル数で設定または取得します。デフォルトでは、このプロパティは 300 dpi. です。 |

### 関連項目

* class [RenderingOptions](../../aspose.html.rendering/renderingoptions/)
* 名前空間 [Aspose.Html.Rendering.Image](../../aspose.html.rendering.image/)
* 組み立て [Aspose.HTML](../../)


