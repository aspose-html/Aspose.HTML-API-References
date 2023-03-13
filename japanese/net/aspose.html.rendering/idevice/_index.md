---
title: Interface IDevice
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Rendering.IDevice インターフェース. パステキスト画像などのグラフィック要素のカスタム レンダリングをサポートするメソッドとプロパティを定義します
type: docs
weight: 4280
url: /ja/net/aspose.html.rendering/idevice/
---
## IDevice interface

パス、テキスト、画像などのグラフィック要素のカスタム レンダリングをサポートするメソッドとプロパティを定義します。

```csharp
public interface IDevice : IDisposable
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/idevice/graphiccontext/) { get; } | グラフィック コンテキストを取得します。 |
| [Options](../../aspose.html.rendering/idevice/options/) { get; } | レンダリング オプションを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddRect](../../aspose.html.rendering/idevice/addrect/)(RectangleF) | 四角形を現在のパスに完全なサブパスとして追加します。 |
| [BeginDocument](../../aspose.html.rendering/idevice/begindocument/)(Document) | ドキュメントのレンダリングを開始します。 |
| [BeginElement](../../aspose.html.rendering/idevice/beginelement/)(Element, RectangleF) | 要素のレンダリングを開始します。 |
| [BeginPage](../../aspose.html.rendering/idevice/beginpage/)(SizeF) | 新しいページのレンダリングを開始します。 |
| [Clip](../../aspose.html.rendering/idevice/clip/)(FillMode) | FillMode ルールを使用して塗りつぶす領域を決定し、現在のクリッピング パスを現在のパスと交差させて変更します。 このメソッドは、現在のパスを終了します。 |
| [ClosePath](../../aspose.html.rendering/idevice/closepath/)() | 現在のポイントからサブパスの開始点までの直線セグメントを追加することにより、現在のサブパスを閉じます。 現在のサブパスが既に閉じられている場合、"ClosePath" は何もしません。 この演算子は現在のサブパスを終了します。現在のパスに別のセグメントを追加すると、新しいサブパス が開始されますが、新しいセグメントが「ClosePath」メソッドによって到達したエンドポイントで開始される場合でも. |
| [CubicBezierTo](../../aspose.html.rendering/idevice/cubicbezierto/)(PointF, PointF, PointF) | 3 次ベジエ曲線を現在のパスに追加します。曲線は、ベジエ制御点として pt1 と pt2 を使用して、現在の点から点 pt3, まで延長されます。新しい現在のポイントは pt3. です |
| [DrawImage](../../aspose.html.rendering/idevice/drawimage/)(byte[], ImageType, RectangleF) | 指定した画像を描画します。 |
| [EndDocument](../../aspose.html.rendering/idevice/enddocument/)() | ドキュメントのレンダリングを終了します。 |
| [EndElement](../../aspose.html.rendering/idevice/endelement/)(Element) | 要素のレンダリングを終了します。 |
| [EndPage](../../aspose.html.rendering/idevice/endpage/)() | 現在のページのレンダリングを終了します。 |
| [Fill](../../aspose.html.rendering/idevice/fill/)(FillMode) | 現在のパスで囲まれた領域全体を塗りつぶします。 パスがいくつかの切断されたサブパスで構成されている場合、 をまとめて考慮して、すべてのサブパスの内部を埋めます。 このメソッドは、現在のパスを終了します。 |
| [FillText](../../aspose.html.rendering/idevice/filltext/)(string, PointF) | 指定した位置に指定したテキスト文字列を入力します。 |
| [Flush](../../aspose.html.rendering/idevice/flush/)() | すべてのデータを出力ストリームにフラッシュします。 |
| [LineTo](../../aspose.html.rendering/idevice/lineto/)(PointF) | 現在の点から点 (pt) までの直線セグメントを追加します。新しい現在のポイントは pt. です |
| [MoveTo](../../aspose.html.rendering/idevice/moveto/)(PointF) | 現在の点をパラメーター pt の座標に移動し、接続する線分を省略して、新しいサブパスを開始します。 現在のパスの以前のパス構築方法も「MoveTo」だった場合、新しい「MoveTo」がそれをオーバーライドします。 前の「MoveTo」操作の痕跡がパスに残っていません. |
| [RestoreGraphicContext](../../aspose.html.rendering/idevice/restoregraphiccontext/)() | スタックからポップすることにより、グラフィック コンテキスト全体を以前の値に復元します。 |
| [SaveGraphicContext](../../aspose.html.rendering/idevice/savegraphiccontext/)() | グラフィックス コンテキスト全体のコピーをスタックにプッシュします。 |
| [Stroke](../../aspose.html.rendering/idevice/stroke/)() | 現在のパスに沿って線を引きます。ストローク ラインは、パス内の各直線または曲線のセグメントに従います。 はセグメントの中心にあり、辺はそれに平行です。パスの各サブパスは個別に扱われます。 このメソッドは、現在のパスを終了します。 |
| [StrokeAndFill](../../aspose.html.rendering/idevice/strokeandfill/)(FillMode) | 現在のパスをストロークして塗りつぶします。 このメソッドは現在のパスを終了します。 |
| [StrokeText](../../aspose.html.rendering/idevice/stroketext/)(string, PointF) | 指定された位置で指定されたテキスト文字列をストロークします。 |

### 関連項目

* 名前空間 [Aspose.Html.Rendering](../../aspose.html.rendering/)
* 組み立て [Aspose.HTML](../../)


