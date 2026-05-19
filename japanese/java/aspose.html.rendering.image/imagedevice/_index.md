---
title: "ImageDevice クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.rendering.image.ImageDevice クラス。jpeg、png、bmp、gif、tiff のラスタ形式へのレンダリングを表します。"
type: docs

url: /ja/java/com.aspose.html.rendering.image/imagedevice/
---
## ImageDevice class

ラスタ形式（jpeg、png、bmp、gif、tiff）へのレンダリングを表します。

```java
public class ImageDevice : Device<ImageGraphicContext, ImageRenderingOptions>
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)(ICreateStreamProvider) | `ImageDevice` クラスの新しいインスタンスを初期化します。 |
| [ImageDevice](imagedevice/#constructor_4)(Stream) | `ImageDevice` クラスの新しいインスタンスを初期化します。 |
| [ImageDevice](imagedevice/#constructor_5)(String) | `ImageDevice` クラスの新しいインスタンスを初期化します。 |
| [ImageDevice](imagedevice/#constructor_1)(ImageRenderingOptions, ICreateStreamProvider) | レンダリング オプションとストリーム プロバイダーで `ImageDevice` クラスの新しいインスタンスを初期化します。 |
| [ImageDevice](imagedevice/#constructor_2)(ImageRenderingOptions, Stream) | レンダリング オプションと出力ストリームで `ImageDevice` クラスの新しいインスタンスを初期化します。 |
| [ImageDevice](imagedevice/#constructor_3)(ImageRenderingOptions, String) | レンダリング オプションと出力ファイル名で `ImageDevice` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [addRect](../../com.aspose.html.rendering/device-2/addrect/)(RectangleF) |  |
| [beginDocument](../../com.aspose.html.rendering/device-2/begindocument/)(Document) |  |
| [beginElement](../../com.aspose.html.rendering/device-2/beginelement/)(Element, RectangleF) |  |
| [beginPage](../../com.aspose.html.rendering/device-2/beginpage/)(SizeF) |  |
| [clip](../../com.aspose.html.rendering/device-2/clip/)(FillRule) |  |
| [closePath](../../com.aspose.html.rendering/device-2/closepath/)() |  |
| [cubicBezierTo](../../com.aspose.html.rendering/device-2/cubicbezierto/)(PointF, PointF, PointF) |  |
| [dispose](../../com.aspose.html.rendering/device-2/dispose/)() |  |
| [drawImage](../../com.aspose.html.rendering/device-2/drawimage/)(byte[], WebImageFormat, RectangleF) |  |
| [endDocument](../../com.aspose.html.rendering/device-2/enddocument/)() |  |
| [endElement](../../com.aspose.html.rendering/device-2/endelement/)(Element) |  |
| [endPage](../../com.aspose.html.rendering/device-2/endpage/)() |  |
| [fill](../../com.aspose.html.rendering/device-2/fill/)(FillRule) |  |
| [fillText](../../com.aspose.html.rendering/device-2/filltext/)(String, PointF) |  |
| [flush](../../com.aspose.html.rendering/device-2/flush/)() |  |
| [lineTo](../../com.aspose.html.rendering/device-2/lineto/)(PointF) |  |
| [moveTo](../../com.aspose.html.rendering/device-2/moveto/)(PointF) |  |
| [restoreGraphicContext](../../com.aspose.html.rendering/device-2/restoregraphiccontext/)() |  |
| [saveGraphicContext](../../com.aspose.html.rendering/device-2/savegraphiccontext/)() |  |
| [stroke](../../com.aspose.html.rendering/device-2/stroke/)() |  |
| [strokeAndFill](../../com.aspose.html.rendering/device-2/strokeandfill/)(FillRule) |  |
| [strokeText](../../com.aspose.html.rendering/device-2/stroketext/)(String, PointF) |  |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| class [ImageGraphicContext](../../com.aspose.html.rendering.image/imagedevice.imagegraphiccontext) | `ImageDevice` の現在のグラフィック制御パラメータを保持します。これらのパラメータは、グラフィック演算子が実行されるグローバルフレームワークを定義します。 |

### 関連項目

* class [ImageGraphicContext](../imagedevice.imagegraphiccontext/)
* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [ImageRenderingOptions](../imagerenderingoptions/)
* package [com.aspose.html.rendering.image](../../com.aspose.html.rendering.image/)
* package [Aspose.HTML](../../)
