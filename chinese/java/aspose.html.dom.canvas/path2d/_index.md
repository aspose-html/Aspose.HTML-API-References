---
title: "Path2D 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.canvas.Path2D 类。Canvas 2D API 的 Path2D 接口用于声明路径，随后在 CanvasRenderingContext2D 对象上使用这些路径。CanvasRenderingContext2D 接口的路径方法也在此接口中提供，允许您创建可以在画布上按需保留和重放的路径。"
type: docs

url: /zh/java/com.aspose.html.dom.canvas/path2d/
---
## Path2D class

Canvas 2D API 的 Path2D 接口用于声明路径，这些路径随后会在 CanvasRenderingContext2D 对象上使用。CanvasRenderingContext2D 接口的路径方法也出现在此接口中，允许您创建可以在画布上根据需要保留和重放的路径。

```java
public class Path2D : DOMObject, ICanvasPathMethods, IDisposable
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Path2D](path2d/#constructor)() | 返回一个新实例化的 Path2D 对象 |
| [Path2D](path2d/#constructor_1)(Path2D) | 返回一个新实例化的 Path2D 对象，使用另一个路径作为参数（创建副本） |
| [Path2D](path2d/#constructor_2)(String) | 返回一个新实例化的 Path2D 对象，使用包含 SVG 路径数据的字符串。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [addPath](../../com.aspose.html.dom.canvas/path2d/addpath/#addpath)(Path2D) | 将参数提供的路径添加到当前路径中。 |
| [addPath](../../com.aspose.html.dom.canvas/path2d/addpath/#addpath_1)(Path2D, SVGMatrix) | 将参数提供的路径添加到当前路径中。 |
| [arc](../../com.aspose.html.dom.canvas/path2d/arc/#arc)(double, double, double, double, double) | 向路径添加一个弧，该弧以 (x, y) 为中心，半径为 r，从 startAngle 开始到 endAngle 结束，按给定方向逆时针绘制（默认顺时针）。 |
| [arc](../../com.aspose.html.dom.canvas/path2d/arc/#arc_1)(double, double, double, double, double, bool) | 向路径添加一个弧，该弧以 (x, y) 为中心，半径为 r，从 startAngle 开始到 endAngle 结束，按给定方向逆时针绘制（默认顺时针）。 |
| [arcTo](../../com.aspose.html.dom.canvas/path2d/arcto/)(double, double, double, double, double) | 向路径添加一个弧，使用给定的控制点和半径，并通过直线与前一点相连。 |
| [bezierCurveTo](../../com.aspose.html.dom.canvas/path2d/beziercurveto/)(double, double, double, double, double, double) | 向路径添加一条三次 Bézier 曲线。它需要三个点。前两个点是控制点，第三个点是终点。起始点是当前路径中的最后一点，可在创建 Bézier 曲线之前使用 moveTo() 更改。 |
| [closePath](../../com.aspose.html.dom.canvas/path2d/closepath/)() | 使笔的点返回到当前子路径的起始位置。它尝试从当前点绘制一条直线到起点。如果形状已经闭合或只有一个点，则此函数不执行任何操作。 |
| [dispose](../../com.aspose.html.dom.canvas/path2d/dispose/)() | 释放对象。 |
| [ellipse](../../com.aspose.html.dom.canvas/path2d/ellipse/#ellipse)(double, double, double, double, double, double, double) | 向路径添加一个椭圆，该椭圆以 (x, y) 为中心，半径为 radiusX 和 radiusY，从 startAngle 开始到 endAngle 结束，按给定方向逆时针绘制（默认顺时针）。 |
| [ellipse](../../com.aspose.html.dom.canvas/path2d/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | 向路径添加一个椭圆，该椭圆以 (x, y) 为中心，半径为 radiusX 和 radiusY，从 startAngle 开始到 endAngle 结束，按给定方向逆时针绘制（默认顺时针）。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象。 |
| [lineTo](../../com.aspose.html.dom.canvas/path2d/lineto/)(double, double) | 用直线将子路径的最后一点连接到 x, y 坐标。 |
| [moveTo](../../com.aspose.html.dom.canvas/path2d/moveto/)(double, double) | 将新子路径的起始点移动到 (x, y) 坐标。 |
| [quadraticCurveTo](../../com.aspose.html.dom.canvas/path2d/quadraticcurveto/)(double, double, double, double) | 向当前路径添加二次 Bézier 曲线。 |
| [rect](../../com.aspose.html.dom.canvas/path2d/rect/)(double, double, double, double) | 在位置 (x, y) 创建一个矩形路径，其大小由宽度和高度决定。 |

### 另请参见

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
