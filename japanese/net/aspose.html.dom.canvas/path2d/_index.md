---
title: Class Path2D
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Dom.Canvas.Path2D クラス. Canvas 2D API の Path2D インターフェイスは後で CanvasRenderingContext2D オブジェクトで使用されるパスを宣言するために使用されます CanvasRenderingContext2D インターフェイスのパス メソッドもこのインターフェイスに存在しキャンバス上で必要に応じて保持および再生できる パスを作成できます
type: docs
weight: 290
url: /ja/net/aspose.html.dom.canvas/path2d/
---
## Path2D class

Canvas 2D API の Path2D インターフェイスは、後で CanvasRenderingContext2D オブジェクトで使用されるパスを宣言するために使用されます。 CanvasRenderingContext2D インターフェイスのパス メソッドもこのインターフェイスに存在し、キャンバス上で必要に応じて保持および再生できる パスを作成できます。

```csharp
public class Path2D : DOMObject, ICanvasPathMethods, IDisposable
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [Path2D](path2d/#constructor)() | は新しくインスタンス化された Path2D object を返します |
| [Path2D](path2d/#constructor_1)(Path2D) | は、別のパスを引数として新しくインスタンス化された Path2D オブジェクトを返します (コピーを作成します) |
| [Path2D](path2d/#constructor_2)(string) | は、SVG パス データで構成される文字列を含む、新しくインスタンス化された Path2D オブジェクトを返します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddPath](../../aspose.html.dom.canvas/path2d/addpath/#addpath)(Path2D) | 引数で指定されたパスをパスに追加します。 |
| [AddPath](../../aspose.html.dom.canvas/path2d/addpath/#addpath_1)(Path2D, SVGMatrix) | 引数で指定されたパスをパスに追加します。 |
| [Arc](../../aspose.html.dom.canvas/path2d/arc/#arc)(double, double, double, double, double) | (x, y) 位置を中心とし、startAngle から始まり endAngle で終わる半径 r のパスに、指定された方向に反時計回り (デフォルトでは時計回り) に円弧を追加します。 |
| [Arc](../../aspose.html.dom.canvas/path2d/arc/#arc_1)(double, double, double, double, double, bool) | (x, y) 位置を中心とし、startAngle から始まり endAngle で終わる半径 r のパスに、指定された方向に反時計回り (デフォルトでは時計回り) に円弧を追加します。 |
| [ArcTo](../../aspose.html.dom.canvas/path2d/arcto/)(double, double, double, double, double) | 指定された制御点と半径を使用してパスに円弧を追加し、前の点に直線で接続します。 |
| [BezierCurveTo](../../aspose.html.dom.canvas/path2d/beziercurveto/)(double, double, double, double, double, double) | 3 次ベジエ曲線をパスに追加します。 3点必要です。 最初の 2 点は制御点で、3 番目の点は終点です。 開始点は現在のパスの最後の点 であり、ベジエ曲線を作成する前に moveTo() を使用して変更できます. |
| [ClosePath](../../aspose.html.dom.canvas/path2d/closepath/)() | ペンのポイントを現在のサブパスの開始点に戻します。 現在点から始点まで直線を引こうとします。 シェイプがすでに閉じているか、ポイントが 1 つしかない場合、この関数は何もしません。 |
| [Dispose](../../aspose.html.dom.canvas/path2d/dispose/)() | オブジェクトを破棄します。 |
| [Ellipse](../../aspose.html.dom.canvas/path2d/ellipse/#ellipse)(double, double, double, double, double, double, double) | (x, y) 位置を中心とし、半径 radiusX および radiusY で、startAngle から開始し、endAngle で終了する楕円をパスに追加します。 |
| [Ellipse](../../aspose.html.dom.canvas/path2d/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | (x, y) 位置を中心とし、半径 radiusX および radiusY で、startAngle から開始し、endAngle で終了する楕円をパスに追加します。 |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | このメソッドは、ECMAScript オブジェクトを取得するために使用されますType. |
| [LineTo](../../aspose.html.dom.canvas/path2d/lineto/)(double, double) | サブパスの最後のポイントを x、y 座標に直線で接続します。 |
| [MoveTo](../../aspose.html.dom.canvas/path2d/moveto/)(double, double) | 新しいサブパスの始点を (x, y) 座標に移動します。 |
| [QuadraticCurveTo](../../aspose.html.dom.canvas/path2d/quadraticcurveto/)(double, double, double, double) | 現在のパスに 2 次ベジエ曲線を追加します。 |
| [Rect](../../aspose.html.dom.canvas/path2d/rect/)(double, double, double, double) | 位置 (x, y) に、幅と高さによって決まるサイズの四角形のパスを作成します。 |

### 関連項目

* class [DOMObject](../../aspose.html.dom/domobject/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* 名前空間 [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* 組み立て [Aspose.HTML](../../)


