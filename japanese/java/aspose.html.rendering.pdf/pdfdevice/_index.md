---
title: "PdfDevice クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.rendering.pdf.PdfDevice クラス。PDF ドキュメントへのレンダリングを表します。"
type: docs

url: /ja/java/com.aspose.html.rendering.pdf/pdfdevice/
---
## PdfDevice class

PDF ドキュメントへのレンダリングを表します。

```java
public class PdfDevice : Device<PdfGraphicContext, PdfRenderingOptions>
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [PdfDevice](pdfdevice/#constructor)(ICreateStreamProvider) | `PdfDevice` クラスの新しいインスタンスを初期化します。 |
| [PdfDevice](pdfdevice/#constructor_4)(Stream) | `PdfDevice` クラスの新しいインスタンスを初期化します。 |
| [PdfDevice](pdfdevice/#constructor_5)(String) | `PdfDevice` クラスの新しいインスタンスを初期化します。 |
| [PdfDevice](pdfdevice/#constructor_1)(PdfRenderingOptions, ICreateStreamProvider) | レンダリングオプションとストリームプロバイダーにより `PdfDevice` クラスの新しいインスタンスを初期化します。 |
| [PdfDevice](pdfdevice/#constructor_2)(PdfRenderingOptions, Stream) | レンダリングオプションと出力ストリームにより `PdfDevice` クラスの新しいインスタンスを初期化します。 |
| [PdfDevice](pdfdevice/#constructor_3)(PdfRenderingOptions, String) | レンダリングオプションと出力ファイル名により `PdfDevice` クラスの新しいインスタンスを初期化します。 |

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
| class [PdfGraphicContext](../../com.aspose.html.rendering.pdf/pdfdevice.pdfgraphiccontext) | PdfDevice の現在のグラフィック制御パラメータを保持します。これらのパラメータは、グラフィック演算子が実行されるグローバルフレームワークを定義します。 |

### 関連項目

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [PdfGraphicContext](../pdfdevice.pdfgraphiccontext/)
* class [PdfRenderingOptions](../pdfrenderingoptions/)
* package [com.aspose.html.rendering.pdf](../../com.aspose.html.rendering.pdf/)
* package [Aspose.HTML](../../)
