---
title: Class Path2D
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Canvas.Path2D 班级. Canvas 2D API 的 Path2D 接口用于声明稍后在 CanvasRenderingContext2D 对象上使用的路径 CanvasRenderingContext2D 接口的路径方法也出现在该接口上并允许您创建 路径您可以根据需要在画布上保留和重放这些路径
type: docs
weight: 290
url: /zh/net/aspose.html.dom.canvas/path2d/
---
## Path2D class

Canvas 2D API 的 Path2D 接口用于声明稍后在 CanvasRenderingContext2D 对象上使用的路径。 CanvasRenderingContext2D 接口的路径方法也出现在该接口上，并允许您创建 路径，您可以根据需要在画布上保留和重放这些路径。

```csharp
public class Path2D : DOMObject, ICanvasPathMethods, IDisposable
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Path2D](path2d/#constructor)() | 返回一个新实例化的 Path2D 对象 |
| [Path2D](path2d/#constructor_1)(Path2D) | 返回一个新实例化的 Path2D 对象，并将另一个路径作为参数（创建一个副本） |
| [Path2D](path2d/#constructor_2)(string) | 返回一个新实例化的 Path2D 对象，其字符串由 SVG 路径数据组成。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [AddPath](../../aspose.html.dom.canvas/path2d/addpath/#addpath)(Path2D) | 将参数给定的路径添加到路径中。 |
| [AddPath](../../aspose.html.dom.canvas/path2d/addpath/#addpath_1)(Path2D, SVGMatrix) | 将参数给定的路径添加到路径中。 |
| [Arc](../../aspose.html.dom.canvas/path2d/arc/#arc)(double, double, double, double, double) | 向以 (x, y) 位置为中心、半径为 r 的路径添加一个圆弧，从 startAngle 开始到 endAngle 结束，沿给定方向逆时针（默认为顺时针）。 |
| [Arc](../../aspose.html.dom.canvas/path2d/arc/#arc_1)(double, double, double, double, double, bool) | 向以 (x, y) 位置为中心、半径为 r 的路径添加一个圆弧，从 startAngle 开始到 endAngle 结束，沿给定方向逆时针（默认为顺时针）。 |
| [ArcTo](../../aspose.html.dom.canvas/path2d/arcto/)(double, double, double, double, double) | 将圆弧添加到具有给定控制点和半径的路径，通过直线连接到前一个点。 |
| [BezierCurveTo](../../aspose.html.dom.canvas/path2d/beziercurveto/)(double, double, double, double, double, double) | 向路径添加三次贝塞尔曲线。它需要三点。 前两个点是控制点，第三个是终点。 起点是当前路径中的最后一个点， 可以在创建贝塞尔曲线之前使用 moveTo() 更改。 |
| [ClosePath](../../aspose.html.dom.canvas/path2d/closepath/)() | 使笔尖移回当前子路径的起点。 它试图从当前点到起点画一条直线。 如果形状已经闭合或只有一个点，则此函数不执行任何操作。 |
| [Dispose](../../aspose.html.dom.canvas/path2d/dispose/)() | 处理对象。 |
| [Ellipse](../../aspose.html.dom.canvas/path2d/ellipse/#ellipse)(double, double, double, double, double, double, double) | 向以 (x, y) 位置为中心的路径添加一个椭圆，半径为 radiusX 和 radiusY，从 startAngle 开始到 endAngle 结束，沿给定方向逆时针（默认为顺时针）。 |
| [Ellipse](../../aspose.html.dom.canvas/path2d/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | 向以 (x, y) 位置为中心的路径添加一个椭圆，半径为 radiusX 和 radiusY，从 startAngle 开始到 endAngle 结束，沿给定方向逆时针（默认为顺时针）。 |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象Type. |
| [LineTo](../../aspose.html.dom.canvas/path2d/lineto/)(double, double) | 用直线将子路径中的最后一个点连接到 x、y 坐标。 |
| [MoveTo](../../aspose.html.dom.canvas/path2d/moveto/)(double, double) | 将新子路径的起点移动到 (x, y) 坐标。 |
| [QuadraticCurveTo](../../aspose.html.dom.canvas/path2d/quadraticcurveto/)(double, double, double, double) | 将二次贝塞尔曲线添加到当前路径。 |
| [Rect](../../aspose.html.dom.canvas/path2d/rect/)(double, double, double, double) | 在位置 (x, y) 处为矩形创建路径，其大小由宽度和高度决定。 |

### 也可以看看

* class [DOMObject](../../aspose.html.dom/domobject/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* 命名空间 [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* 部件 [Aspose.HTML](../../)


