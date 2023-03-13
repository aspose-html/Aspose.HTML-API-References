---
title: Class DocDevice
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Rendering.Doc.DocDevice クラス. DOCX ドキュメントへのレンダリングを表します
type: docs
weight: 4170
url: /ja/net/aspose.html.rendering.doc/docdevice/
---
## DocDevice class

DOCX ドキュメントへのレンダリングを表します。

```csharp
public class DocDevice : Device<DocGraphicContext, DocRenderingOptions>
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [DocDevice](docdevice/#constructor)(ICreateStreamProvider) | の新しいインスタンスを初期化します`DocDevice` class. |
| [DocDevice](docdevice/#constructor_4)(Stream) | の新しいインスタンスを初期化します`DocDevice`出力ストリームによるクラス. |
| [DocDevice](docdevice/#constructor_5)(string) | の新しいインスタンスを初期化します`DocDevice`出力ファイル名別分類. |
| [DocDevice](docdevice/#constructor_1)(DocRenderingOptions, ICreateStreamProvider) | の新しいインスタンスを初期化します`DocDevice`レンダリング オプションとストリーム プロバイダーによるクラス. |
| [DocDevice](docdevice/#constructor_2)(DocRenderingOptions, Stream) | の新しいインスタンスを初期化します`DocDevice`オプションと出力ストリームをレンダリングすることによってクラス。 |
| [DocDevice](docdevice/#constructor_3)(DocRenderingOptions, string) | の新しいインスタンスを初期化します`DocDevice`レンダリング オプションと出力ファイル名によるクラス. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } |  |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } |  |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [AddRect](../../aspose.html.rendering.doc/docdevice/addrect/)(RectangleF) | 四角形を現在のパスに完全なサブパスとして追加します。 |
| override [BeginDocument](../../aspose.html.rendering.doc/docdevice/begindocument/)(Document) | ドキュメントのレンダリングを開始します。 |
| override [BeginElement](../../aspose.html.rendering.doc/docdevice/beginelement/)(Element, RectangleF) | html ノードのレンダリングを開始します。 |
| override [BeginPage](../../aspose.html.rendering.doc/docdevice/beginpage/)(SizeF) | 新しいページのレンダリングを開始します。 |
| override [Clip](../../aspose.html.rendering.doc/docdevice/clip/)(FillMode) | FillMode ルールを使用して塗りつぶす領域を決定し、現在のクリッピング パスを現在のパスと交差させて変更します。 このメソッドは、現在のパスを終了します。 |
| override [ClosePath](../../aspose.html.rendering.doc/docdevice/closepath/)() | 現在のポイントからサブパスの開始点までの直線セグメントを追加することにより、現在のサブパスを閉じます。 現在のサブパスが既に閉じられている場合、"ClosePath" は何もしません。 この演算子は現在のサブパスを終了します。現在のパスに別のセグメントを追加すると、新しいサブパス が開始されますが、新しいセグメントが「ClosePath」メソッドによって到達したエンドポイントで開始される場合でも. |
| override [CubicBezierTo](../../aspose.html.rendering.doc/docdevice/cubicbezierto/)(PointF, PointF, PointF) | 3 次ベジエ曲線を現在のパスに追加します。曲線は、ベジエ制御点として pt1 と pt2 を使用して、現在の点から点 pt2, まで延長されます。新しい現在のポイントは pt3. です |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() |  |
| override [DrawImage](../../aspose.html.rendering.doc/docdevice/drawimage/)(byte[], ImageType, RectangleF) | 指定した画像を描画します。 |
| virtual [EndDocument](../../aspose.html.rendering/device-2/enddocument/)() |  |
| override [EndElement](../../aspose.html.rendering.doc/docdevice/endelement/)(Element) | html ノードのレンダリングを終了します。 |
| override [EndPage](../../aspose.html.rendering.doc/docdevice/endpage/)() | 現在のページのレンダリングを終了します。 |
| override [Fill](../../aspose.html.rendering.doc/docdevice/fill/)(FillMode) | 現在のパスで囲まれた領域全体を塗りつぶします。 パスがいくつかの切断されたサブパスで構成されている場合、 をまとめて考慮して、すべてのサブパスの内部を埋めます。 このメソッドは、現在のパスを終了します。 |
| override [FillText](../../aspose.html.rendering.doc/docdevice/filltext/)(string, PointF) | 指定した位置に指定したテキスト文字列を入力します。 |
| override [Flush](../../aspose.html.rendering.doc/docdevice/flush/)() | すべてのデータを出力ストリームにフラッシュします。 |
| override [LineTo](../../aspose.html.rendering.doc/docdevice/lineto/)(PointF) | 現在の点から点 (pt) までの直線セグメントを追加します。新しい現在のポイントは pt. です |
| override [MoveTo](../../aspose.html.rendering.doc/docdevice/moveto/)(PointF) | 現在の点をパラメーター pt の座標に移動し、接続する線分を省略して、新しいサブパスを開始します。 現在のパスの以前のパス構築方法も「MoveTo」だった場合、新しい「MoveTo」がそれをオーバーライドします。 前の「MoveTo」操作の痕跡がパスに残っていません. |
| override [RestoreGraphicContext](../../aspose.html.rendering.doc/docdevice/restoregraphiccontext/)() | スタックからポップすることにより、グラフィック コンテキスト全体を以前の値に復元します。 |
| override [SaveGraphicContext](../../aspose.html.rendering.doc/docdevice/savegraphiccontext/)() | グラフィックス コンテキスト全体のコピーをスタックにプッシュします。 |
| override [Stroke](../../aspose.html.rendering.doc/docdevice/stroke/)() | 現在のパスに沿って線を引きます。ストローク ラインは、パス内の各直線または曲線のセグメントに従います。 はセグメントの中心にあり、辺はそれに平行です。パスの各サブパスは個別に扱われます。 このメソッドは、現在のパスを終了します。 |
| override [StrokeAndFill](../../aspose.html.rendering.doc/docdevice/strokeandfill/)(FillMode) | 現在のパスをストロークして塗りつぶします。 このメソッドは現在のパスを終了します。 |
| override [StrokeText](../../aspose.html.rendering.doc/docdevice/stroketext/)(string, PointF) | 指定された位置で指定されたテキスト文字列をストロークします。 |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| class [DocGraphicContext](docdevice.docgraphiccontext/) | DocDevice の現在のグラフィック制御パラメーターを保持します。 これらのパラメーターは、グラフィック オペレーターが実行されるグローバル フレームワークを定義します。 |

### 関連項目

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2/)
* class [DocGraphicContext](../docdevice.docgraphiccontext/)
* class [DocRenderingOptions](../docrenderingoptions/)
* 名前空間 [Aspose.Html.Rendering.Doc](../../aspose.html.rendering.doc/)
* 組み立て [Aspose.HTML](../../)


