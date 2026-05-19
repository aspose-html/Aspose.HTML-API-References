---
title: "DeviceTGraphicContextTRenderingOptions クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.rendering.Device2TGraphicContextTRenderingOptions クラス。特定のレンダリングデバイスの実装のための基底クラスを表します。"
type: docs

url: /ja/java/com.aspose.html.rendering/device-2/
---
## Device&lt;TGraphicContext,TRenderingOptions&gt; class

特定のレンダリングデバイスの実装のための基底クラスを表します。

```java
public abstract class Device<TGraphicContext, TRenderingOptions> : Device, IDevice
    where TGraphicContext : GraphicContext, new()
    where TRenderingOptions : RenderingOptions
```

| Parameter | 説明 |
| --- | --- |
| TGraphicContext | 現在のグラフィック制御パラメータを保持するグラフィックコンテキスト |
| TRenderingOptions | レンダリングオプション |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) グラフィックコンテキストを取得します |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) レンダリングオプションを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [addRect](../../com.aspose.html.rendering/device-2/addrect/)(RectangleF) | 現在のパスに矩形を追加し、完全なサブパスとして扱います。 |
| [beginDocument](../../com.aspose.html.rendering/device-2/begindocument/)(Document) | ドキュメントのレンダリングを開始します。 |
| [beginElement](../../com.aspose.html.rendering/device-2/beginelement/)(Element, RectangleF) | ノードのレンダリングを開始します。 |
| [beginPage](../../com.aspose.html.rendering/device-2/beginpage/)(SizeF) | 新しいページのレンダリングを開始します。 |
| [clip](../../com.aspose.html.rendering/device-2/clip/)(FillRule) | FillRule を使用して塗りつぶす領域を決定し、現在のパスと交差させて現在のクリッピングパスを変更します。このメソッドは現在のパスを終了します。 |
| [closePath](../../com.aspose.html.rendering/device-2/closepath/)() | 現在の点からサブパスの開始点まで直線セグメントを追加して現在のサブパスを閉じます。現在のサブパスがすでに閉じている場合、\"ClosePath\" は何もしません。この演算子は現在のサブパスを終了させます。現在のパスに別のセグメントを追加すると、新しいサブパスが開始されます。たとえ新しいセグメントが \"ClosePath\" メソッドで到達した終点から始まっても同様です。 |
| [cubicBezierTo](../../com.aspose.html.rendering/device-2/cubicbezierto/)(PointF, PointF, PointF) | 現在のパスに3次ベジェ曲線を追加します。曲線は現在の点から点 pt2 まで伸び、pt1 と pt2 をベジェ制御点として使用します。新しい現在の点は pt3 です。 |
| [dispose](../../com.aspose.html.rendering/device-2/dispose/)() | アンマネージドリソースの解放、リリース、またはリセットに関連するアプリケーション定義のタスクを実行します。 |
| [drawImage](../../com.aspose.html.rendering/device-2/drawimage/)(byte[], WebImageFormat, RectangleF) | 指定された画像を描画します。 |
| [endDocument](../../com.aspose.html.rendering/device-2/enddocument/)() | ドキュメントのレンダリングを終了します。 |
| [endElement](../../com.aspose.html.rendering/device-2/endelement/)(Element) | ノードのレンダリングを終了します。 |
| [endPage](../../com.aspose.html.rendering/device-2/endpage/)() | 現在のページのレンダリングを終了します。 |
| [fill](../../com.aspose.html.rendering/device-2/fill/)(FillRule) | 現在のパスで囲まれた全領域を塗りつぶします。パスが複数の切れ離されたサブパスで構成されている場合、すべてのサブパスの内部をまとめて塗りつぶします。このメソッドは現在のパスを終了します。 |
| [fillText](../../com.aspose.html.rendering/device-2/filltext/)(String, PointF) | 指定された位置に指定されたテキスト文字列を塗りつぶします。 |
| [flush](../../com.aspose.html.rendering/device-2/flush/)() | すべてのデータを出力ストリームにフラッシュします。 |
| [lineTo](../../com.aspose.html.rendering/device-2/lineto/)(PointF) | 現在の点から点 (pt) までの直線セグメントを追加します。新しい現在の点は pt です。 |
| [moveTo](../../com.aspose.html.rendering/device-2/moveto/)(PointF) | 現在の点をパラメータ pt の座標へ移動させ、新しいサブパスを開始します。接続線は省略されます。もし現在のパスで前のパス構築メソッドも "MoveTo" だった場合、新しい "MoveTo" がそれを上書きし、以前の "MoveTo" 操作の痕跡はパスに残りません。 |
| [restoreGraphicContext](../../com.aspose.html.rendering/device-2/restoregraphiccontext/)() | スタックからポップして、グラフィックスコンテキスト全体を元の値に復元します。 |
| [saveGraphicContext](../../com.aspose.html.rendering/device-2/savegraphiccontext/)() | グラフィックスコンテキスト全体のコピーをスタックにプッシュします。 |
| [stroke](../../com.aspose.html.rendering/device-2/stroke/)() | 現在のパスに沿って線を描画します。描画された線はパスの各直線または曲線セグメントに沿い、セグメントの中心に配置され、側面はそれに平行になります。パスの各サブパスは個別に処理されます。このメソッドは現在のパスを終了します。 |
| [strokeAndFill](../../com.aspose.html.rendering/device-2/strokeandfill/)(FillRule) | 現在のパスを描画および塗りつぶします。このメソッドは現在のパスを終了します。 |
| [strokeText](../../com.aspose.html.rendering/device-2/stroketext/)(String, PointF) | 指定された位置に指定されたテキスト文字列を描画します。 |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| class [DeviceConfiguration&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2.deviceconfiguration-2) |  |
| enum [PageWritingStrategy&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2.pagewritingstrategy-2) | ページを出力ストリーム\ストリームに書き込むための戦略タイプを指定します。 |

### 関連項目

* class [Device](../device/)
* interface [IDevice](../idevice/)
* class [GraphicContext](../graphiccontext/)
* class [RenderingOptions](../renderingoptions/)
* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
