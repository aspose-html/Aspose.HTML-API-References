---
title: "ICanvasPathMethods インターフェイス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.canvas.ICanvasPathMethods インターフェイス。 ICanvasPathMethods インターフェイスはオブジェクトのパスを操作するために使用されます。"
type: docs

url: /ja/java/com.aspose.html.dom.canvas/icanvaspathmethods/
---
## ICanvasPathMethods interface

ICanvasPathMethods インターフェイスは、オブジェクトのパスを操作するために使用されます。

```java
public interface ICanvasPathMethods
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [arc](../../com.aspose.html.dom.canvas/icanvaspathmethods/arc/#arc)(double, double, double, double, double) | パスに円弧を追加します。円弧は (x, y) を中心とし、半径 r で、startAngle から始まり endAngle で終わり、指定された方向（デフォルトは時計回りで、反時計回りを指定可能）に描かれます。 |
| [arc](../../com.aspose.html.dom.canvas/icanvaspathmethods/arc/#arc_1)(double, double, double, double, double, bool) | パスに円弧を追加します。円弧は (x, y) を中心とし、半径 r で、startAngle から始まり endAngle で終わり、指定された方向（デフォルトは時計回りで、反時計回りを指定可能）に描かれます。 |
| [arcTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/arcto/)(double, double, double, double, double) | 指定された制御点と半径を使用してパスに円弧を追加し、前の点と直線で接続します。 |
| [bezierCurveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/beziercurveto/)(double, double, double, double, double, double) | パスに3次ベジェ曲線を追加します。3 つの点が必要です。最初の 2 点は制御点、3 番目の点が終点です。開始点は現在のパスの最後の点で、ベジェ曲線を作成する前に moveTo() を使用して変更できます。 |
| [closePath](../../com.aspose.html.dom.canvas/icanvaspathmethods/closepath/)() | ペンの位置を現在のサブパスの開始点に戻します。現在の点から開始点へ直線を描こうとします。形状がすでに閉じているか、点が1つしかない場合、この関数は何もしません。 |
| [ellipse](../../com.aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse)(double, double, double, double, double, double, double) | パスに楕円を追加します。楕円は (x, y) を中心とし、半径 radiusX と radiusY を持ち、startAngle から始まり endAngle で終わり、指定された方向（デフォルトは時計回りで、反時計回りを指定可能）に描かれます。 |
| [ellipse](../../com.aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | パスに楕円を追加します。楕円は (x, y) を中心とし、半径 radiusX と radiusY を持ち、startAngle から始まり endAngle で終わり、指定された方向（デフォルトは時計回りで、反時計回りを指定可能）に描かれます。 |
| [lineTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/lineto/)(double, double) | サブパスの最後の点を (x, y) 座標へ直線で接続します。 |
| [moveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/moveto/)(double, double) | 新しいサブパスの開始点を (x, y) 座標に移動します。 |
| [quadraticCurveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/quadraticcurveto/)(double, double, double, double) | 現在のパスに二次ベジェ曲線を追加します。 |
| [rect](../../com.aspose.html.dom.canvas/icanvaspathmethods/rect/)(double, double, double, double) | (x, y) の位置に、幅と高さで決まるサイズの矩形のパスを作成します。 |

### 関連項目

* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
