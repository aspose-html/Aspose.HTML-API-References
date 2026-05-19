---
title: "Path2D クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.dom.canvas.Path2D クラス。Canvas 2D API の Path2D インターフェイスは、後で CanvasRenderingContext2D オブジェクトで使用されるパスを宣言するために使用されます。このインターフェイスには CanvasRenderingContext2D インターフェイスのパスメソッドも含まれており、必要に応じてキャンバス上で保持および再生できるパスを作成できます。"
type: docs

url: /ja/java/com.aspose.html.dom.canvas/path2d/
---
## Path2D class

Canvas 2D API の Path2D インターフェイスは、パスを宣言するために使用され、その後 CanvasRenderingContext2D オブジェクトで使用されます。CanvasRenderingContext2D インターフェイスのパスメソッドもこのインターフェイスに存在し、必要に応じてキャンバス上でパスを保持および再生できるようにします。

```java
public class Path2D : DOMObject, ICanvasPathMethods, IDisposable
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Path2D](path2d/#constructor)() | 新しくインスタンス化された Path2D オブジェクトを返します。 |
| [Path2D](path2d/#constructor_1)(Path2D) | 別のパスを引数として渡した新しくインスタンス化された Path2D オブジェクトを返します（コピーを作成）。 |
| [Path2D](path2d/#constructor_2)(String) | SVG パスデータからなる文字列を使用して新しくインスタンス化された Path2D オブジェクトを返します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [addPath](../../com.aspose.html.dom.canvas/path2d/addpath/#addpath)(Path2D) | 引数で指定されたパスを現在のパスに追加します。 |
| [addPath](../../com.aspose.html.dom.canvas/path2d/addpath/#addpath_1)(Path2D, SVGMatrix) | 引数で指定されたパスを現在のパスに追加します。 |
| [arc](../../com.aspose.html.dom.canvas/path2d/arc/#arc)(double, double, double, double, double) | パスに弧を追加します。弧は (x, y) を中心とし、半径 r で、startAngle から始まり endAngle で終わり、指定された方向（デフォルトは時計回りで、反時計回りを指定可能）に描かれます。 |
| [arc](../../com.aspose.html.dom.canvas/path2d/arc/#arc_1)(double, double, double, double, double, bool) | パスに弧を追加します。弧は (x, y) を中心とし、半径 r で、startAngle から始まり endAngle で終わり、指定された方向（デフォルトは時計回りで、反時計回りを指定可能）に描かれます。 |
| [arcTo](../../com.aspose.html.dom.canvas/path2d/arcto/)(double, double, double, double, double) | 指定された制御点と半径を使用してパスに弧を追加し、前の点と直線で接続します。 |
| [bezierCurveTo](../../com.aspose.html.dom.canvas/path2d/beziercurveto/)(double, double, double, double, double, double) | パスに三次ベジェ曲線を追加します。3 つの点が必要です。最初の 2 点は制御点、3 番目の点が終点です。開始点は現在のパスの最後の点で、ベジェ曲線を作成する前に moveTo() で変更できます。 |
| [closePath](../../com.aspose.html.dom.canvas/path2d/closepath/)() | ペンの位置を現在のサブパスの開始点に戻します。現在の点から開始点へ直線を描こうとします。形状がすでに閉じているか、点が1つしかない場合、この関数は何もしません。 |
| [dispose](../../com.aspose.html.dom.canvas/path2d/dispose/)() | オブジェクトを破棄します。 |
| [ellipse](../../com.aspose.html.dom.canvas/path2d/ellipse/#ellipse)(double, double, double, double, double, double, double) | パスに楕円を追加します。楕円は (x, y) を中心とし、半径 radiusX と radiusY を持ち、startAngle から始まり endAngle で終わり、指定された方向（デフォルトは時計回りで、反時計回りを指定可能）に描かれます。 |
| [ellipse](../../com.aspose.html.dom.canvas/path2d/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | パスに楕円を追加します。楕円は (x, y) を中心とし、半径 radiusX と radiusY を持ち、startAngle から始まり endAngle で終わり、指定された方向（デフォルトは時計回りで、反時計回りを指定可能）に描かれます。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | このメソッドは ECMAScript オブジェクトを取得するために使用されます。 |
| [lineTo](../../com.aspose.html.dom.canvas/path2d/lineto/)(double, double) | サブパスの最後の点を (x, y) 座標へ直線で接続します。 |
| [moveTo](../../com.aspose.html.dom.canvas/path2d/moveto/)(double, double) | 新しいサブパスの開始点を (x, y) 座標に移動します。 |
| [quadraticCurveTo](../../com.aspose.html.dom.canvas/path2d/quadraticcurveto/)(double, double, double, double) | 現在のパスに二次ベジェ曲線を追加します。 |
| [rect](../../com.aspose.html.dom.canvas/path2d/rect/)(double, double, double, double) | (x, y) の位置に、幅と高さで決まるサイズの矩形のパスを作成します。 |

### 関連項目

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
