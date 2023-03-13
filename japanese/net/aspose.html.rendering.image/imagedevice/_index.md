---
title: Class ImageDevice
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Rendering.Image.ImageDevice クラス. ラスター形式へのレンダリングを表します jpegpngbmpgiftiff.
type: docs
weight: 4300
url: /ja/net/aspose.html.rendering.image/imagedevice/
---
## ImageDevice class

ラスター形式へのレンダリングを表します: jpeg、png、bmp、gif、tiff.

```csharp
public class ImageDevice : Device<ImageGraphicContext, ImageRenderingOptions>
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)(ICreateStreamProvider) | の新しいインスタンスを初期化します`ImageDevice` class. |
| [ImageDevice](imagedevice/#constructor_4)(Stream) | の新しいインスタンスを初期化します`ImageDevice` class. |
| [ImageDevice](imagedevice/#constructor_5)(string) | の新しいインスタンスを初期化します`ImageDevice` class. |
| [ImageDevice](imagedevice/#constructor_1)(ImageRenderingOptions, ICreateStreamProvider) | の新しいインスタンスを初期化します`ImageDevice`レンダリング オプションとストリーム プロバイダーによるクラス. |
| [ImageDevice](imagedevice/#constructor_2)(ImageRenderingOptions, Stream) | の新しいインスタンスを初期化します`ImageDevice`オプションと出力ストリームをレンダリングすることによるクラス. |
| [ImageDevice](imagedevice/#constructor_3)(ImageRenderingOptions, string) | の新しいインスタンスを初期化します`ImageDevice`レンダリング オプションと出力ファイル名によるクラス. |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } |  |
| virtual [Graphics](../../aspose.html.rendering.image/imagedevice/graphics/) { get; } | Graphics. のインスタンスを取得します。 |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } |  |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [AddRect](../../aspose.html.rendering.image/imagedevice/addrect/)(RectangleF) | 四角形を現在のパスに完全なサブパスとして追加します。 |
| override [BeginDocument](../../aspose.html.rendering.image/imagedevice/begindocument/)(Document) | ドキュメントのレンダリングを開始します。 |
| override [BeginElement](../../aspose.html.rendering.image/imagedevice/beginelement/)(Element, RectangleF) | 要素のレンダリングを開始します。 |
| override [BeginPage](../../aspose.html.rendering.image/imagedevice/beginpage/)(SizeF) | 新しいページのレンダリングを開始します。 |
| override [Clip](../../aspose.html.rendering.image/imagedevice/clip/)(FillMode) | FillMode ルールを使用して塗りつぶす領域を決定し、現在のクリッピング パスを現在のパスと交差させて変更します。 このメソッドは、現在のパスを終了します。 |
| override [ClosePath](../../aspose.html.rendering.image/imagedevice/closepath/)() | 現在のポイントからサブパスの開始点までの直線セグメントを追加することにより、現在のサブパスを閉じます。 現在のサブパスが既に閉じられている場合、"ClosePath" は何もしません。 この演算子は現在のサブパスを終了します。現在のパスに別のセグメントを追加すると、新しいサブパス が開始されますが、新しいセグメントが「ClosePath」メソッドによって到達したエンドポイントで開始される場合でも. |
| override [CubicBezierTo](../../aspose.html.rendering.image/imagedevice/cubicbezierto/)(PointF, PointF, PointF) | 3 次ベジエ曲線を現在のパスに追加します。曲線は、ベジエ制御点として pt1 と pt2 を使用して、現在の点から点 pt2, まで延長されます。新しい現在のポイントは pt3. です |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() |  |
| override [DrawImage](../../aspose.html.rendering.image/imagedevice/drawimage/)(byte[], ImageType, RectangleF) | 指定した画像を描画します。 |
| override [EndDocument](../../aspose.html.rendering.image/imagedevice/enddocument/)() | ドキュメントのレンダリングを終了します。 |
| override [EndElement](../../aspose.html.rendering.image/imagedevice/endelement/)(Element) | 要素のレンダリングを終了します。 |
| override [EndPage](../../aspose.html.rendering.image/imagedevice/endpage/)() | 現在のページのレンダリングを終了します。 |
| override [Fill](../../aspose.html.rendering.image/imagedevice/fill/)(FillMode) | 現在のパスで囲まれた領域全体を塗りつぶします。 パスがいくつかの切断されたサブパスで構成されている場合、 をまとめて考慮して、すべてのサブパスの内部を埋めます。 このメソッドは、現在のパスを終了します。 |
| override [FillText](../../aspose.html.rendering.image/imagedevice/filltext/)(string, PointF) | 指定した位置に指定したテキスト文字列を入力します。 |
| override [Flush](../../aspose.html.rendering.image/imagedevice/flush/)() | すべてのデータを出力ストリームにフラッシュします。 |
| override [LineTo](../../aspose.html.rendering.image/imagedevice/lineto/)(PointF) | 現在の点から点 (pt) までの直線セグメントを追加します。新しい現在のポイントは pt. です |
| override [MoveTo](../../aspose.html.rendering.image/imagedevice/moveto/)(PointF) | 現在の点をパラメーター pt の座標に移動し、接続する線分を省略して、新しいサブパスを開始します。 現在のパスの以前のパス構築方法も「MoveTo」だった場合、新しい「MoveTo」がそれをオーバーライドします。 前の「MoveTo」操作の痕跡がパスに残っていません. |
| override [RestoreGraphicContext](../../aspose.html.rendering.image/imagedevice/restoregraphiccontext/)() | スタックからポップすることにより、グラフィック コンテキスト全体を以前の値に復元します。 |
| override [SaveGraphicContext](../../aspose.html.rendering.image/imagedevice/savegraphiccontext/)() | グラフィックス コンテキスト全体のコピーをスタックにプッシュします。 |
| override [Stroke](../../aspose.html.rendering.image/imagedevice/stroke/)() | 現在のパスに沿って線を引きます。ストローク ラインは、パス内の各直線または曲線のセグメントに従います。 はセグメントの中心にあり、辺はそれに平行です。パスの各サブパスは個別に扱われます。 このメソッドは、現在のパスを終了します。 |
| override [StrokeAndFill](../../aspose.html.rendering.image/imagedevice/strokeandfill/)(FillMode) | 現在のパスをストロークして塗りつぶします。 このメソッドは現在のパスを終了します。 |
| override [StrokeText](../../aspose.html.rendering.image/imagedevice/stroketext/)(string, PointF) | 指定された位置で指定されたテキスト文字列をストロークします。 |

## その他のメンバー

| 名前 | 説明 |
| --- | --- |
| class [ImageGraphicContext](imagedevice.imagegraphiccontext/) | の現在のグラフィックス コントロール パラメータを保持します。`ImageDevice` . これらのパラメーターは、グラフィック オペレーターが実行されるグローバル フレームワークを定義します。 |

### 関連項目

* class [ImageGraphicContext](../imagedevice.imagegraphiccontext/)
* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2/)
* class [ImageRenderingOptions](../imagerenderingoptions/)
* 名前空間 [Aspose.Html.Rendering.Image](../../aspose.html.rendering.image/)
* 組み立て [Aspose.HTML](../../)


