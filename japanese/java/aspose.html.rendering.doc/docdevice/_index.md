---
title: "DocDevice クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.rendering.doc.DocDevice クラス。DOCX ドキュメントへのレンダリングを表します"
type: docs

url: /ja/java/com.aspose.html.rendering.doc/docdevice/
---
## DocDevice class

DOCX ドキュメントへのレンダリングを表します。

```java
public class DocDevice : Device<DocGraphicContext, DocRenderingOptions>
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [DocDevice](docdevice/#constructor)(ICreateStreamProvider) | `DocDevice` クラスの新しいインスタンスを初期化します。 |
| [DocDevice](docdevice/#constructor_4)(Stream) | 出力ストリームによって `DocDevice` クラスの新しいインスタンスを初期化します。 |
| [DocDevice](docdevice/#constructor_5)(String) | 出力ファイル名によって `DocDevice` クラスの新しいインスタンスを初期化します。 |
| [DocDevice](docdevice/#constructor_1)(DocRenderingOptions, ICreateStreamProvider) | レンダリングオプションとストリームプロバイダーによって `DocDevice` クラスの新しいインスタンスを初期化します。 |
| [DocDevice](docdevice/#constructor_2)(DocRenderingOptions, Stream) | レンダリングオプションと出力ストリームによって `DocDevice` クラスの新しいインスタンスを初期化します。 |
| [DocDevice](docdevice/#constructor_3)(DocRenderingOptions, String) | レンダリングオプションと出力ファイル名によって `DocDevice` クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [addRect](../../com.aspose.html.rendering.doc/docdevice/addrect/)(RectangleF) | 現在のパスに矩形を完全なサブパスとして追加します。 |
| [beginDocument](../../com.aspose.html.rendering.doc/docdevice/begindocument/)(Document) | ドキュメントのレンダリングを開始します。 |
| [beginElement](../../com.aspose.html.rendering.doc/docdevice/beginelement/)(Element, RectangleF) | HTML ノードのレンダリングを開始します。 |
| [beginPage](../../com.aspose.html.rendering.doc/docdevice/beginpage/)(SizeF) | 新しいページのレンダリングを開始します。 |
| [clip](../../com.aspose.html.rendering.doc/docdevice/clip/)(FillRule) | FillMode ルールを使用して塗りつぶす領域を決定し、現在のパスと交差させて現在のクリッピングパスを変更します。このメソッドは現在のパスを終了します。 |
| [closePath](../../com.aspose.html.rendering.doc/docdevice/closepath/)() | 現在の点からサブパスの開始点まで直線セグメントを追加して現在のサブパスを閉じます。現在のサブパスがすでに閉じている場合、\"ClosePath\" は何もしません。この演算子は現在のサブパスを終了します。現在のパスに別のセグメントを追加すると、新しいサブパスが開始されます。たとえ新しいセグメントが \"ClosePath\" メソッドで到達した終点から始まっても同様です。 |
| [cubicBezierTo](../../com.aspose.html.rendering.doc/docdevice/cubicbezierto/)(PointF, PointF, PointF) | 現在のパスに三次ベジエ曲線を追加します。曲線は現在の点から点 pt2 まで伸び、pt1 と pt2 をベジエ制御点として使用します。新しい現在の点は pt3 です。 |
| [dispose](../../com.aspose.html.rendering/device-2/dispose/)() |  |
| [drawImage](../../com.aspose.html.rendering.doc/docdevice/drawimage/)(byte[], WebImageFormat, RectangleF) | 指定された画像を描画します。 |
| [endDocument](../../com.aspose.html.rendering/device-2/enddocument/)() |  |
| [endElement](../../com.aspose.html.rendering.doc/docdevice/endelement/)(Element) | HTML ノードのレンダリングを終了します。 |
| [endPage](../../com.aspose.html.rendering.doc/docdevice/endpage/)() | 現在のページのレンダリングを終了します。 |
| [fill](../../com.aspose.html.rendering.doc/docdevice/fill/)(FillRule) | 現在のパスで囲まれた全領域を塗りつぶします。パスがいくつかの切断されたサブパスで構成されている場合、すべてのサブパスの内部をまとめて塗りつぶします。このメソッドは現在のパスを終了します。 |
| [fillText](../../com.aspose.html.rendering.doc/docdevice/filltext/)(String, PointF) | 指定された位置に指定されたテキスト文字列を塗りつぶします。 |
| [flush](../../com.aspose.html.rendering.doc/docdevice/flush/)() | すべてのデータを出力ストリームにフラッシュします。 |
| [lineTo](../../com.aspose.html.rendering.doc/docdevice/lineto/)(PointF) | 現在の点から点 (pt) までの直線セグメントを追加します。新しい現在の点は pt です。 |
| [moveTo](../../com.aspose.html.rendering.doc/docdevice/moveto/)(PointF) | 現在の点をパラメータ pt の座標へ移動させ、新しいサブパスを開始します。この際、接続線セグメントは省略されます。もし現在のパスにおける直前のパス構築メソッドが同じく \"MoveTo\" であった場合、新しい \"MoveTo\" がそれを上書きします。パス内に以前の \"MoveTo\" 操作の痕跡は残りません。 |
| [restoreGraphicContext](../../com.aspose.html.rendering/device-2/restoregraphiccontext/)() |  |
| [saveGraphicContext](../../com.aspose.html.rendering/device-2/savegraphiccontext/)() |  |
| [stroke](../../com.aspose.html.rendering.doc/docdevice/stroke/)() | 現在のパスに沿って線を描画します。描画された線はパス内の各直線または曲線セグメントに沿い、セグメントの中心に配置され、側面はそれに平行になります。パスの各サブパスは個別に扱われます。このメソッドは現在のパスを終了します。 |
| [strokeAndFill](../../com.aspose.html.rendering.doc/docdevice/strokeandfill/)(FillRule) | 現在のパスを描画および塗りつぶします。このメソッドは現在のパスを終了します。 |
| [strokeText](../../com.aspose.html.rendering.doc/docdevice/stroketext/)(String, PointF) | 指定された位置に指定されたテキスト文字列を描画します。 |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| class [DocGraphicContext](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext) | DocDevice の現在のグラフィック制御パラメータを保持します。これらのパラメータは、グラフィック演算子が実行されるグローバルフレームワークを定義します。 |

### 関連項目

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [DocGraphicContext](../docdevice.docgraphiccontext/)
* class [DocRenderingOptions](../docrenderingoptions/)
* package [com.aspose.html.rendering.doc](../../com.aspose.html.rendering.doc/)
* package [Aspose.HTML](../../)
