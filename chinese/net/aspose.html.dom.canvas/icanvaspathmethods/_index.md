---
title: Interface ICanvasPathMethods
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Canvas.ICanvasPathMethods 界面. ICanvasPathMethods 接口用于操作对象的路径
type: docs
weight: 240
url: /zh/net/aspose.html.dom.canvas/icanvaspathmethods/
---
## ICanvasPathMethods interface

ICanvasPathMethods 接口用于操作对象的路径。

```csharp
public interface ICanvasPathMethods
```

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Arc](../../aspose.html.dom.canvas/icanvaspathmethods/arc/#arc)(double, double, double, double, double) | 向以 (x, y) 位置为中心、半径为 r 的路径添加一个圆弧，从 startAngle 开始到 endAngle 结束，沿给定方向逆时针（默认为顺时针）。 |
| [Arc](../../aspose.html.dom.canvas/icanvaspathmethods/arc/#arc_1)(double, double, double, double, double, bool) | 向以 (x, y) 位置为中心、半径为 r 的路径添加一个圆弧，从 startAngle 开始到 endAngle 结束，沿给定方向逆时针（默认为顺时针）。 |
| [ArcTo](../../aspose.html.dom.canvas/icanvaspathmethods/arcto/)(double, double, double, double, double) | 将圆弧添加到具有给定控制点和半径的路径，通过直线连接到前一个点。 |
| [BezierCurveTo](../../aspose.html.dom.canvas/icanvaspathmethods/beziercurveto/)(double, double, double, double, double, double) | 向路径添加三次贝塞尔曲线。它需要三点。 前两个点是控制点，第三个是终点。 起点是当前路径中的最后一个点， 可以在创建贝塞尔曲线之前使用 moveTo() 更改。 |
| [ClosePath](../../aspose.html.dom.canvas/icanvaspathmethods/closepath/)() | 使笔尖移回当前子路径的起点。 它试图从当前点到起点画一条直线。 如果形状已经闭合或只有一个点，则此函数不执行任何操作。 |
| [Ellipse](../../aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse)(double, double, double, double, double, double, double) | 向以 (x, y) 位置为中心的路径添加一个椭圆，半径为 radiusX 和 radiusY，从 startAngle 开始到 endAngle 结束，沿给定方向逆时针（默认为顺时针）。 |
| [Ellipse](../../aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | 向以 (x, y) 位置为中心的路径添加一个椭圆，半径为 radiusX 和 radiusY，从 startAngle 开始到 endAngle 结束，沿给定方向逆时针（默认为顺时针）。 |
| [LineTo](../../aspose.html.dom.canvas/icanvaspathmethods/lineto/)(double, double) | 用直线将子路径中的最后一个点连接到 x、y 坐标。 |
| [MoveTo](../../aspose.html.dom.canvas/icanvaspathmethods/moveto/)(double, double) | 将新子路径的起点移动到 (x, y) 坐标。 |
| [QuadraticCurveTo](../../aspose.html.dom.canvas/icanvaspathmethods/quadraticcurveto/)(double, double, double, double) | 将二次贝塞尔曲线添加到当前路径。 |
| [Rect](../../aspose.html.dom.canvas/icanvaspathmethods/rect/)(double, double, double, double) | 在位置 (x, y) 处为矩形创建路径，其大小由宽度和高度决定。 |

### 也可以看看

* 命名空间 [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* 部件 [Aspose.HTML](../../)


