---
title: Interface ICanvasPathMethods
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Dom.Canvas.ICanvasPathMethods インターフェース. ICanvasPathMethods インターフェイスはオブジェクトのパスを操作するために使用されます
type: docs
weight: 240
url: /ja/net/aspose.html.dom.canvas/icanvaspathmethods/
---
## ICanvasPathMethods interface

ICanvasPathMethods インターフェイスは、オブジェクトのパスを操作するために使用されます。

```csharp
public interface ICanvasPathMethods
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Arc](../../aspose.html.dom.canvas/icanvaspathmethods/arc/#arc)(double, double, double, double, double) | (x, y) 位置を中心とし、startAngle から始まり endAngle で終わる半径 r のパスに、指定された方向に反時計回り (デフォルトでは時計回り) に円弧を追加します。 |
| [Arc](../../aspose.html.dom.canvas/icanvaspathmethods/arc/#arc_1)(double, double, double, double, double, bool) | (x, y) 位置を中心とし、startAngle から始まり endAngle で終わる半径 r のパスに、指定された方向に反時計回り (デフォルトでは時計回り) に円弧を追加します。 |
| [ArcTo](../../aspose.html.dom.canvas/icanvaspathmethods/arcto/)(double, double, double, double, double) | 指定された制御点と半径を使用してパスに円弧を追加し、前の点に直線で接続します。 |
| [BezierCurveTo](../../aspose.html.dom.canvas/icanvaspathmethods/beziercurveto/)(double, double, double, double, double, double) | 3 次ベジエ曲線をパスに追加します。 3点必要です。 最初の 2 点は制御点で、3 番目の点は終点です。 開始点は現在のパスの最後の点 であり、ベジエ曲線を作成する前に moveTo() を使用して変更できます. |
| [ClosePath](../../aspose.html.dom.canvas/icanvaspathmethods/closepath/)() | ペンのポイントを現在のサブパスの開始点に戻します。 現在点から始点まで直線を引こうとします。 シェイプがすでに閉じているか、ポイントが 1 つしかない場合、この関数は何もしません。 |
| [Ellipse](../../aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse)(double, double, double, double, double, double, double) | (x, y) 位置を中心とし、半径 radiusX および radiusY で、startAngle から開始し、endAngle で終了する楕円をパスに追加します。 |
| [Ellipse](../../aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | (x, y) 位置を中心とし、半径 radiusX および radiusY で、startAngle から開始し、endAngle で終了する楕円をパスに追加します。 |
| [LineTo](../../aspose.html.dom.canvas/icanvaspathmethods/lineto/)(double, double) | サブパスの最後のポイントを x、y 座標に直線で接続します。 |
| [MoveTo](../../aspose.html.dom.canvas/icanvaspathmethods/moveto/)(double, double) | 新しいサブパスの始点を (x, y) 座標に移動します。 |
| [QuadraticCurveTo](../../aspose.html.dom.canvas/icanvaspathmethods/quadraticcurveto/)(double, double, double, double) | 現在のパスに 2 次ベジエ曲線を追加します。 |
| [Rect](../../aspose.html.dom.canvas/icanvaspathmethods/rect/)(double, double, double, double) | 位置 (x, y) に、幅と高さによって決まるサイズの四角形のパスを作成します。 |

### 関連項目

* 名前空間 [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* 組み立て [Aspose.HTML](../../)


