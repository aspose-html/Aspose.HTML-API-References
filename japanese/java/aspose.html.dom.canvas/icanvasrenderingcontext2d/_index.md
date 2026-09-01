---
title: "ICanvasRenderingContext2D インターフェイス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.canvas.ICanvasRenderingContext2D インターフェイス。ICanvasRenderingContext2D インターフェイスは、矩形、テキスト、画像、その他のオブジェクトを canvas 要素上に描画するために使用されます。canvas 要素の描画表面に対する 2D レンダリングコンテキストを提供します。"
type: docs

url: /ja/java/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/
---
## ICanvasRenderingContext2D interface

ICanvasRenderingContext2D インターフェイスは、キャンバス要素上に矩形、テキスト、画像、その他のオブジェクトを描画するために使用されます。キャンバス要素の描画表面に対する 2D レンダリングコンテキストを提供します。

```java
public interface ICanvasRenderingContext2D : ICanvasDrawingStyles, ICanvasPathMethods
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [getCanvas](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/canvas/) HTMLCanvasElement への読み取り専用のバックリファレンスです。canvas 要素に関連付けられていない場合は null になる可能性があります。 |
[getFillStyle]
[setFillStyle] Color or style to use inside shapes. Default: (black). |
[getGlobalAlpha]
[setGlobalAlpha] Alpha value that is applied to shapes and images before they are composited onto the canvas. Default 1.0 (opaque). |
[getGlobalCompositeOperation]
[setGlobalCompositeOperation] With globalAlpha applied this sets how shapes and images are drawn onto the existing bitmap. Default: (source-over) |
[getImageSmoothingEnabled]
[setImageSmoothingEnabled] Image smoothing mode; if disabled, images will not be smoothed if scaled. |
[getShadowBlur]
[setShadowBlur] Specifies the blurring effect. Default 0 |
[getShadowColor]
[setShadowColor] Color of the shadow. Default fully-transparent black. |
[getShadowOffsetX]
[setShadowOffsetX] Horizontal distance the shadow will be offset. Default 0. |
[getShadowOffsetY]
[setShadowOffsetY] Vertical distance the shadow will be offset. Default 0. |
[getStrokeStyle]
[setStrokeStyle] Color or style to use for the lines around shapes. Default: (black). |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [addHitRegion](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/addhitregion/)(Dictionary&lt;String, String&gt;) |  |
| [beginPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/beginpath/)() | サブパスのリストを空にして新しいパスを開始します。新しいパスを作成したいときにこのメソッドを呼び出します。 |
| [clearHitRegions](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clearhitregions/)() | canvas からすべてのヒット領域を削除します。 |
| [clearRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clearrect/)(double, double, double, double) | 開始点 (x, y) とサイズ (width, height) で定義された矩形内のすべてのピクセルを透明な黒に設定し、以前に描画された内容を消去します。 |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip)() | 非ゼロ巻き数規則を使用して、現在のクリッピング領域とパスで記述された領域の交差を計算することにより、新しいクリッピング領域を作成します。クリッピング領域を計算する際には、開いているサブパスは暗黙的に閉じられますが、実際のサブパスには影響しません。新しいクリッピング領域は現在のクリッピング領域と置き換えられます。 |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_1)(CanvasFillRule) | 非ゼロ巻き数規則を使用して、現在のクリッピング領域とパスで記述された領域の交差を計算することにより、新しいクリッピング領域を作成します。クリッピング領域を計算する際には、開いているサブパスは暗黙的に閉じられますが、実際のサブパスには影響しません。新しいクリッピング領域は現在のクリッピング領域と置き換えられます。 |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_2)(Path2D, CanvasFillRule) | 非ゼロ巻き数規則を使用して、現在のクリッピング領域とパスで記述された領域の交差を計算することにより、新しいクリッピング領域を作成します。クリッピング領域を計算する際には、開いているサブパスは暗黙的に閉じられますが、実際のサブパスには影響しません。新しいクリッピング領域は現在のクリッピング領域と置き換えられます。 |
| [createImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata)(IImageData) | 指定された寸法で新しい空の ImageData オブジェクトを作成します。新しいオブジェクトのすべてのピクセルは透明な黒です。 |
| [createImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata_1)(double, double) | 指定された寸法で新しい空の ImageData オブジェクトを作成します。新しいオブジェクトのすべてのピクセルは透明な黒です。 |
| [createLinearGradient](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createlineargradient/)(double, double, double, double) | パラメータで表される座標によって定義された直線に沿って線形グラデーションを作成します。 |
| [createPattern](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern)(HTMLCanvasElement, String) | 指定された画像（CanvasImageSource）を使用してパターンを作成します。繰り返し引数で指定された方向にソースを繰り返します。 |
| [createPattern](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern_1)(HTMLImageElement, String) | 指定された画像（CanvasImageSource）を使用してパターンを作成します。繰り返し引数で指定された方向にソースを繰り返します。 |
| [createRadialGradient](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createradialgradient/)(double, double, double, double, double, double) | パラメータで表される 2 つの円の座標によって放射状グラデーションを作成します。 |
| [drawFocusIfNeeded](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawfocusifneeded/)(Element) | 要素がフォーカスされている場合、このメソッドは現在のパスの周囲にフォーカスリングを描画します。 |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage)(HTMLCanvasElement, double, double) | 指定された画像を描画します。 |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_3)(HTMLImageElement, double, double) | 指定された画像を描画します。 |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_1)(HTMLCanvasElement, double, double, double, double) | 指定された画像を描画します。 |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_4)(HTMLImageElement, double, double, double, double) | 指定された画像を描画します。 |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_2)(HTMLCanvasElement, double, double, double, double, double, double, double, double) | 指定された画像を描画します。 |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_5)(HTMLImageElement, double, double, double, double, double, double, double, double) | 指定された画像を描画します。 |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill)() | 現在の塗りスタイルとデフォルトアルゴリズム CanvasFillRule.Nonzero を使用してサブパスを塗りつぶします。 |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_1)(CanvasFillRule) | 現在の塗りスタイルでサブパスを塗りつぶします。 |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_2)(Path2D) | 現在の塗りスタイルとデフォルトアルゴリズム CanvasFillRule.Nonzero を使用してサブパスを塗りつぶします。 |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_3)(Path2D, CanvasFillRule) | 現在の塗りスタイルでサブパスを塗りつぶします。 |
| [fillRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fillrect/)(double, double, double, double) | (x, y) の位置に、幅と高さで決まるサイズの塗りつぶし矩形を描画します。 |
| [fillText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext)(String, double, double) | 指定された (x, y) の位置にテキストを描画（塗りつぶし）します。 |
| [fillText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext_1)(String, double, double, double) | 指定された (x, y) の位置にテキストを描画（塗りつぶし）します。 |
| [getImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata/)(double, double, double, double) | 矩形 (sx, sy) から始まり、幅 sw と高さ sh を持つ領域のピクセルデータを表す ImageData オブジェクトを返します。このメソッドはキャンバスの変換行列の影響を受けません。 |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_2)(double, double) | 指定された点が現在のパスに含まれているかどうかを報告します。 |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_3)(double, double, CanvasFillRule) | 指定された点が現在のパスに含まれているかどうかを報告します。 |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath)(Path2D, double, double) | 指定された点が現在のパスに含まれているかどうかを報告します。 |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_1)(Path2D, double, double, CanvasFillRule) | 指定された点が現在のパスに含まれているかどうかを報告します。 |
| [isPointInStroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke_1)(double, double) | 指定された点がパスのストロークで囲まれた領域内にあるかどうかを報告します。 |
| [isPointInStroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke)(Path2D, double, double) | 指定された点がパスのストロークで囲まれた領域内にあるかどうかを報告します。 |
| [measureText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/measuretext/)(String) | TextMetrics オブジェクトを返します。 |
| [putImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata)(IImageData, double, double) | 指定された ImageData オブジェクトからビットマップへデータを描画します。ダーティ矩形が指定された場合、その矩形内のピクセルだけが描画されます。このメソッドはキャンバスの変換行列の影響を受けません。 |
| [putImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata_1)(IImageData, double, double, double, double, double, double) | 指定された ImageData オブジェクトからビットマップへデータを描画します。ダーティ矩形が指定された場合、その矩形内のピクセルだけが描画されます。このメソッドはキャンバスの変換行列の影響を受けません。 |
| [removeHitRegion](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/removehitregion/)(String) | 指定された ID のヒット領域をキャンバスから削除します。 |
| [resetTransform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/resettransform/)() | 現在の変換を単位行列でリセットします。 |
| [restore](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/restore/)() | save() によって保存された 'state stack' の最後の要素に描画スタイルの状態を復元します。 |
| [rotate](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/rotate/)(double) | 変換行列に回転を加えます。angle 引数は時計回りの回転角度をラジアンで表します。 |
| [save](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/save/)() | スタックを使用して現在の描画スタイル状態を保存し、restore() で変更を元に戻すことができます。 |
| [scale](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/scale/)(double, double) | キャンバスの単位に対して、横方向に x、縦方向に y のスケーリング変換を加えます。 |
| [setTransform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/settransform/)(double, double, double, double, double, double) | 現在の変換を単位行列にリセットし、同じ引数で `transform()` メソッドを呼び出します。 |
| [stroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke)() | 現在のストロークスタイルでサブパスを描画します。 |
| [stroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke_1)(Path2D) | 現在のストロークスタイルでサブパスを描画します。 |
| [strokeRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/strokerect/)(double, double, double, double) | (x, y) を開始点とし、幅 w と高さ h を持つ矩形を現在のストロークスタイルでキャンバスに描画します。 |
| [strokeText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext)(String, double, double) | 指定された (x, y) の位置にテキストを描画（ストローク）します。 |
| [strokeText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext_1)(String, double, double, double?) | 指定された (x, y) の位置にテキストを描画（ストローク）します。 |
| [transform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/transform/)(double, double, double, double, double, double) | 現在の変換行列に、引数で記述された行列を掛け合わせます。 |
| [translate](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/translate/)(double, double) | キャンバスとその原点を x 水平方向、y 垂直方向に移動させ、平行移動変換を加えます。 |

### 関連項目

* interface [ICanvasDrawingStyles](../icanvasdrawingstyles/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
