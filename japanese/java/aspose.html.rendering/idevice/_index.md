---
title: "IDevice インターフェイス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.rendering.IDevice インターフェイス。パス、テキスト、画像などのグラフィック要素のカスタムレンダリングをサポートするメソッドとプロパティを定義します。"
type: docs

url: /ja/java/com.aspose.html.rendering/idevice/
---
## IDevice interface

パス、テキスト、画像などのグラフィック要素のカスタムレンダリングをサポートするメソッドとプロパティを定義します。

```java
public interface IDevice : IDisposable
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/idevice/graphiccontext/) グラフィックコンテキストを取得します。 |
| [getOptions](../../com.aspose.html.rendering/idevice/options/) レンダリングオプションを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [addRect](../../com.aspose.html.rendering/idevice/addrect/)(RectangleF) | 現在のパスに矩形を完全なサブパスとして追加します。 |
| [beginDocument](../../com.aspose.html.rendering/idevice/begindocument/)(Document) | ドキュメントのレンダリングを開始します。 |
| [beginElement](../../com.aspose.html.rendering/idevice/beginelement/)(Element, RectangleF) | 要素のレンダリングを開始します。 |
| [beginPage](../../com.aspose.html.rendering/idevice/beginpage/)(SizeF) | 新しいページのレンダリングを開始します。 |
| [clip](../../com.aspose.html.rendering/idevice/clip/)(FillRule) | 現在のクリッピングパスを現在のパスと交差させ、FillRule を使用して塗りつぶす領域を決定します。このメソッドは現在のパスを終了します。 |
| [closePath](../../com.aspose.html.rendering/idevice/closepath/)() | 現在の点からサブパスの開始点まで直線セグメントを追加して現在のサブパスを閉じます。現在のサブパスがすでに閉じている場合、\"ClosePath\" は何もしません。この演算子は現在のサブパスを終了します。現在のパスに別のセグメントを追加すると、新しいサブパスが開始されます。たとえ新しいセグメントが \"ClosePath\" メソッドで到達した終点から始まっても同様です。 |
| [cubicBezierTo](../../com.aspose.html.rendering/idevice/cubicbezierto/)(PointF, PointF, PointF) | 現在のパスに三次ベジエ曲線を追加します。曲線は現在の点から点 pt3 まで伸び、pt1 と pt2 をベジエ制御点として使用します。新しい現在の点は pt3 です。 |
| [drawImage](../../com.aspose.html.rendering/idevice/drawimage/)(byte[], WebImageFormat, RectangleF) | 指定された画像を描画します。 |
| [endDocument](../../com.aspose.html.rendering/idevice/enddocument/)() | ドキュメントのレンダリングを終了します。 |
| [endElement](../../com.aspose.html.rendering/idevice/endelement/)(Element) | 要素のレンダリングを終了します。 |
| [endPage](../../com.aspose.html.rendering/idevice/endpage/)() | 現在のページのレンダリングを終了します。 |
| [fill](../../com.aspose.html.rendering/idevice/fill/)(FillRule) | 現在のパスで囲まれた全領域を塗りつぶします。パスがいくつかの切断されたサブパスで構成されている場合、すべてのサブパスの内部をまとめて塗りつぶします。このメソッドは現在のパスを終了します。 |
| [fillText](../../com.aspose.html.rendering/idevice/filltext/)(String, PointF) | 指定された位置に指定されたテキスト文字列を塗りつぶします。 |
| [flush](../../com.aspose.html.rendering/idevice/flush/)() | すべてのデータを出力ストリームにフラッシュします。 |
| [lineTo](../../com.aspose.html.rendering/idevice/lineto/)(PointF) | 現在の点から点 (pt) までの直線セグメントを追加します。新しい現在の点は pt です。 |
| [moveTo](../../com.aspose.html.rendering/idevice/moveto/)(PointF) | 現在の点をパラメータ pt の座標へ移動させ、新しいサブパスを開始します。この際、接続線セグメントは省略されます。もし現在のパスにおける直前のパス構築メソッドが同じく \"MoveTo\" であった場合、新しい \"MoveTo\" がそれを上書きします。パス内に以前の \"MoveTo\" 操作の痕跡は残りません。 |
| [restoreGraphicContext](../../com.aspose.html.rendering/idevice/restoregraphiccontext/)() | スタックからポップして、グラフィックスコンテキスト全体を元の値に復元します。 |
| [saveGraphicContext](../../com.aspose.html.rendering/idevice/savegraphiccontext/)() | グラフィックスコンテキスト全体のコピーをスタックにプッシュします。 |
| [stroke](../../com.aspose.html.rendering/idevice/stroke/)() | 現在のパスに沿って線を描画します。描画された線はパス内の各直線または曲線セグメントに沿い、セグメントの中心に配置され、側面はそれに平行になります。パスの各サブパスは個別に扱われます。このメソッドは現在のパスを終了します。 |
| [strokeAndFill](../../com.aspose.html.rendering/idevice/strokeandfill/)(FillRule) | 現在のパスを描画および塗りつぶします。このメソッドは現在のパスを終了します。 |
| [strokeText](../../com.aspose.html.rendering/idevice/stroketext/)(String, PointF) | 指定された位置に指定されたテキスト文字列を描画します。 |

### 関連項目

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
