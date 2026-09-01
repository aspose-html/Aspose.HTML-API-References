---
title: "XpsDevice クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.rendering.xps.XpsDevice クラス。XPS ドキュメントへのレンダリングを表します。"
type: docs

url: /ja/java/com.aspose.html.rendering.xps/xpsdevice/
---
## XpsDevice class

XPS ドキュメントへのレンダリングを表します。

```java
public class XpsDevice : Device<XpsGraphicContext, XpsRenderingOptions>
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [XpsDevice](xpsdevice/#constructor)(ICreateStreamProvider) | `XpsDevice` クラスの新しいインスタンスを初期化します。 |
| [XpsDevice](xpsdevice/#constructor_4)(Stream) | `XpsDevice` クラスの新しいインスタンスを初期化します。 |
| [XpsDevice](xpsdevice/#constructor_5)(String) | `XpsDevice` クラスの新しいインスタンスを初期化します。 |
| [XpsDevice](xpsdevice/#constructor_1)(XpsRenderingOptions, ICreateStreamProvider) | レンダリング オプションとストリーム プロバイダーによって `XpsDevice` クラスの新しいインスタンスを初期化します。 |
| [XpsDevice](xpsdevice/#constructor_2)(XpsRenderingOptions, Stream) | レンダリング オプションと出力ストリームによって `XpsDevice` クラスの新しいインスタンスを初期化します。 |
| [XpsDevice](xpsdevice/#constructor_3)(XpsRenderingOptions, String) | レンダリング オプションと出力ファイル名によって `XpsDevice` クラスの新しいインスタンスを初期化します。 |

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
| class [XpsGraphicContext](../../com.aspose.html.rendering.xps/xpsdevice.xpsgraphiccontext) | XpsDevice の現在のグラフィック制御パラメータを保持します。これらのパラメータは、グラフィック演算子が実行されるグローバルフレームワークを定義します。 |

### 関連項目

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [XpsGraphicContext](../xpsdevice.xpsgraphiccontext/)
* class [XpsRenderingOptions](../xpsrenderingoptions/)
* package [com.aspose.html.rendering.xps](../../com.aspose.html.rendering.xps/)
* package [Aspose.HTML](../../)
