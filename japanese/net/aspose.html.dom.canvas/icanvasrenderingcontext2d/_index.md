---
title: Interface ICanvasRenderingContext2D
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Dom.Canvas.ICanvasRenderingContext2D インターフェース. ICanvasRenderingContext2D インターフェイスはcanvas 要素に四角形テキスト画像およびその他のオブジェクトを描画するために使用されます canvas 要素の描画面に 2D レンダリング コンテキストを提供します
type: docs
weight: 260
url: /ja/net/aspose.html.dom.canvas/icanvasrenderingcontext2d/
---
## ICanvasRenderingContext2D interface

ICanvasRenderingContext2D インターフェイスは、canvas 要素に四角形、テキスト、画像、およびその他のオブジェクトを描画するために使用されます。 canvas 要素の描画面に 2D レンダリング コンテキストを提供します。

```csharp
public interface ICanvasRenderingContext2D : ICanvasDrawingStyles, ICanvasPathMethods
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Canvas](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/canvas/) { get; } | HTMLCanvasElement への読み取り専用の後方参照。キャンバス要素に関連付けられていない場合は null になる可能性があります. |
| [FillStyle](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fillstyle/) { get; set; } | シェイプ内で使用する色またはスタイル。デフォルト: (黒). |
| [GlobalAlpha](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/globalalpha/) { get; set; } | キャンバスに合成される前に形状と画像に適用されるアルファ値。デフォルト 1.0 (不透明). |
| [GlobalCompositeOperation](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/globalcompositeoperation/) { get; set; } | globalAlpha が適用された状態で、既存のビットマップにシェイプと画像を描画する方法を設定します。デフォルト: (source-over) |
| [ImageSmoothingEnabled](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/imagesmoothingenabled/) { get; set; } | 画像スムージング モード。無効にすると、スケーリングしても画像は滑らかになりません。 |
| [ShadowBlur](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowblur/) { get; set; } | ぼかし効果を指定します。デフォルト 0 |
| [ShadowColor](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowcolor/) { get; set; } | 影の色。デフォルトの完全に透明な黒. |
| [ShadowOffsetX](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowoffsetx/) { get; set; } | 影がオフセットされる水平距離。デフォルト 0. |
| [ShadowOffsetY](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowoffsety/) { get; set; } | 影がオフセットされる垂直距離。デフォルト 0. |
| [StrokeStyle](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/strokestyle/) { get; set; } | 図形の周りの線に使用する色またはスタイル。デフォルト: (黒). |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddHitRegion](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/addhitregion/)(Dictionary&lt;string, string&gt;) | キャンバスにヒット領域を追加します。 これにより、ヒット検出が容易になり、イベントを DOM 要素にルーティングできるようになり、 ユーザーがキャンバスを見ずに探索できるようになります。 |
| [BeginPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/beginpath/)() | サブパスのリストを空にして、新しいパスを開始します。新しいパスを作成する場合は、このメソッドを呼び出します. |
| [ClearHitRegions](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clearhitregions/)() | キャンバスからすべてのヒット領域を削除します。 |
| [ClearRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clearrect/)(double, double, double, double) | 開始点 (x、y) とサイズ (幅、高さ) によって定義される四角形内のすべてのピクセルを透明な黒に設定し、以前に描画されたコンテンツを消去します。 |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip)() | 現在のクリッピング領域とパスによって記述された領域の交点を計算することにより、新しいクリッピング領域を作成します。 クリッピング領域を計算するときは、実際のサブパスに影響を与えずに、開いているサブパスを暗黙的に閉じる必要があります. 新しいクリッピング領域が現在のクリッピング領域を置き換えます. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_1)(CanvasFillRule) | 非ゼロの巻き数規則を使用して、現在のクリッピング領域とパスによって記述された領域の交点を計算することにより、新しいクリッピング領域を作成します。 開いているサブパスは、実際のサブパスに影響を与えることなく、クリッピング領域を計算するときに暗黙的に閉じる必要があります. 新しいクリッピング領域が現在のクリッピング領域を置き換えます. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_2)(Path2D, CanvasFillRule) | 非ゼロの巻き数規則を使用して、現在のクリッピング領域とパスによって記述された領域の交点を計算することにより、新しいクリッピング領域を作成します。 開いているサブパスは、実際のサブパスに影響を与えることなく、クリッピング領域を計算するときに暗黙的に閉じる必要があります. 新しいクリッピング領域が現在のクリッピング領域を置き換えます. |
| [CreateImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata)(IImageData) | 指定された寸法で新しい空の ImageData オブジェクトを作成します。 新しいオブジェクトのピクセルはすべて透明な黒です。 |
| [CreateImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata_1)(double, double) | 指定された寸法で新しい空の ImageData オブジェクトを作成します。 新しいオブジェクトのピクセルはすべて透明な黒です。 |
| [CreateLinearGradient](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createlineargradient/)(double, double, double, double) | パラメーターによって表される座標によって指定された線に沿って線形グラデーションを作成します。 |
| [CreatePattern](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern)(HTMLCanvasElement, string) | 指定された画像 (CanvasImageSource) を使用してパターンを作成します。 繰り返し引数で指定された方向にソースを繰り返します。 |
| [CreatePattern](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern_1)(HTMLImageElement, string) | 指定された画像 (CanvasImageSource) を使用してパターンを作成します。 繰り返し引数で指定された方向にソースを繰り返します。 |
| [CreateRadialGradient](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createradialgradient/)(double, double, double, double, double, double) | パラメータで表される 2 つの円の座標によって指定される放射状グラデーションを作成します。 |
| [DrawFocusIfNeeded](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawfocusifneeded/)(Element) | 特定の要素がフォーカスされている場合、このメソッドは現在のパスの周りにフォーカス リングを描画します. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage)(HTMLCanvasElement, double, double) | 指定した画像を描画します。 |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_3)(HTMLImageElement, double, double) | 指定した画像を描画します。 |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_1)(HTMLCanvasElement, double, double, double, double) | 指定した画像を描画します。 |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_4)(HTMLImageElement, double, double, double, double) | 指定した画像を描画します。 |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_2)(HTMLCanvasElement, double, double, double, double, double, double, double, double) | 指定した画像を描画します。 |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_5)(HTMLImageElement, double, double, double, double, double, double, double, double) | 指定した画像を描画します。 |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill)() | サブパスを現在の塗りつぶしスタイルとデフォルトのアルゴリズムで塗りつぶします CanvasFillRule.Nonzero. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_1)(CanvasFillRule) | 現在の塗りつぶしスタイルでサブパスを塗りつぶします. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_2)(Path2D) | サブパスを現在の塗りつぶしスタイルとデフォルトのアルゴリズムで塗りつぶします CanvasFillRule.Nonzero. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_3)(Path2D, CanvasFillRule) | 現在の塗りつぶしスタイルでサブパスを塗りつぶします. |
| [FillRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fillrect/)(double, double, double, double) | (x, y) 位置に、幅と高さによってサイズが決まる塗りつぶされた長方形を描画します。 |
| [FillText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext)(string, double, double) | 指定された (x,y) 位置に指定されたテキストを描画 (塗りつぶし) します。 |
| [FillText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext_1)(string, double, double, double) | 指定された (x,y) 位置に指定されたテキストを描画 (塗りつぶし) します。 |
| [GetImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata/)(double, double, double, double) | (sx, sy) で始まり、幅が sw で高さが sh の長方形で示されるキャンバスの領域の基礎となるピクセル データを表す ImageData オブジェクトを返します。 このメソッドは、キャンバスの変換行列の影響を受けません。 |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_2)(double, double) | 指定したポイントが現在のパスに含まれているかどうかを報告します。 |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_3)(double, double, CanvasFillRule) | 指定したポイントが現在のパスに含まれているかどうかを報告します。 |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath)(Path2D, double, double) | 指定したポイントが現在のパスに含まれているかどうかを報告します。 |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_1)(Path2D, double, double, CanvasFillRule) | 指定したポイントが現在のパスに含まれているかどうかを報告します。 |
| [IsPointInStroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke_1)(double, double) | 指定されたポイントが、パスのストロークによって含まれる領域内にあるかどうかを報告します。 |
| [IsPointInStroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke)(Path2D, double, double) | 指定されたポイントが、パスのストロークによって含まれる領域内にあるかどうかを報告します。 |
| [MeasureText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/measuretext/)(string) | TextMetrics オブジェクトを返します。 |
| [PutImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata)(IImageData, double, double) | 指定された ImageData オブジェクトのデータをビットマップに描画します。 ダーティな四角形が指定されている場合、その四角形のピクセルのみが描画されます。 このメソッドはキャンバス変換マトリックスの影響を受けません. |
| [PutImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata_1)(IImageData, double, double, double, double, double, double) | 指定された ImageData オブジェクトのデータをビットマップに描画します。 ダーティな四角形が指定されている場合、その四角形のピクセルのみが描画されます。 このメソッドはキャンバス変換マトリックスの影響を受けません. |
| [RemoveHitRegion](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/removehitregion/)(string) | 指定された ID を持つヒット領域をキャンバスから削除します。 |
| [ResetTransform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/resettransform/)() | 単位行列によって現在の変換をリセットします. |
| [Restore](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/restore/)() | 描画スタイルの状態を、save(). によって保存された「状態スタック」の最後の要素に復元します。 |
| [Rotate](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/rotate/)(double) | 変換行列に回転を追加します。 angle 引数は、時計回りの回転角度を表し、ラジアンで表されます. |
| [Save](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/save/)() | スタックを使用して現在の描画スタイルの状態を保存し、restore(). を使用して変更を元に戻すことができるようにします。 |
| [Scale](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/scale/)(double, double) | キャンバス単位に水平 x および垂直 y によるスケーリング変換を追加します。 |
| [SetTransform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/settransform/)(double, double, double, double, double, double) | 現在の変換を単位行列にリセットし、同じ引数で transform() メソッドを呼び出します。 |
| [Stroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke)() | 現在のストローク スタイルでサブパスをストロークします。 |
| [Stroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke_1)(Path2D) | 現在のストローク スタイルでサブパスをストロークします。 |
| [StrokeRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/strokerect/)(double, double, double, double) | 現在のストローク スタイルを使用して、(x, y) を始点とし、幅が w で高さが h の長方形をキャンバスに描画します。 |
| [StrokeText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext)(string, double, double) | 指定された (x, y) 位置に指定されたテキストを描画 (ストローク) します。 |
| [StrokeText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext_1)(string, double, double, double?) | 指定された (x, y) 位置に指定されたテキストを描画 (ストローク) します。 |
| [Transform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/transform/)(double, double, double, double, double, double) | 現在の変換行列と、その引数で記述された行列を乗算します。 |
| [Translate](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/translate/)(double, double) | キャンバスとその原点をグリッド上で x 水平方向および y 垂直方向に移動することにより、平行移動変換を追加します。 |

### 関連項目

* interface [ICanvasDrawingStyles](../icanvasdrawingstyles/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* 名前空間 [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* 組み立て [Aspose.HTML](../../)


