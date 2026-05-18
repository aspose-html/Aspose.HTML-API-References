---
title: "ICanvasPathMethods 接口"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.canvas.ICanvasPathMethods 接口。ICanvasPathMethods 接口用于操作对象的路径。"
type: docs

url: /zh/java/com.aspose.html.dom.canvas/icanvaspathmethods/
---
## ICanvasPathMethods interface

ICanvasPathMethods 接口用于操作对象的路径。

```java
public interface ICanvasPathMethods
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [arc](../../com.aspose.html.dom.canvas/icanvaspathmethods/arc/#arc)(double, double, double, double, double) | 向路径添加一个弧，该弧以 (x, y) 为中心，半径为 r，从 startAngle 开始到 endAngle 结束，按给定方向逆时针绘制（默认顺时针）。 |
| [arc](../../com.aspose.html.dom.canvas/icanvaspathmethods/arc/#arc_1)(double, double, double, double, double, bool) | 向路径添加一个弧，该弧以 (x, y) 为中心，半径为 r，从 startAngle 开始到 endAngle 结束，按给定方向逆时针绘制（默认顺时针）。 |
| [arcTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/arcto/)(double, double, double, double, double) | 向路径添加一个弧，使用给定的控制点和半径，并通过直线与前一点相连。 |
| [bezierCurveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/beziercurveto/)(double, double, double, double, double, double) | 向路径添加三次 Bézier 曲线。它需要三个点。前两个点是控制点，第三个点是终点。起始点是当前路径中的最后一点，可在创建 Bézier 曲线之前使用 moveTo() 更改。 |
| [closePath](../../com.aspose.html.dom.canvas/icanvaspathmethods/closepath/)() | 使笔尖移动回当前子路径的起点。它尝试从当前点绘制一条直线到起点。如果形状已经闭合或只有一个点，此函数不执行任何操作。 |
| [ellipse](../../com.aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse)(double, double, double, double, double, double, double) | 向路径添加一个椭圆，该椭圆以 (x, y) 为中心，半径为 radiusX 和 radiusY，从 startAngle 开始到 endAngle 结束，按给定方向逆时针绘制（默认顺时针）。 |
| [ellipse](../../com.aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | 向路径添加一个椭圆，该椭圆以 (x, y) 为中心，半径为 radiusX 和 radiusY，从 startAngle 开始到 endAngle 结束，按给定方向逆时针绘制（默认顺时针）。 |
| [lineTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/lineto/)(double, double) | 用直线将子路径的最后一点连接到 x, y 坐标。 |
| [moveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/moveto/)(double, double) | 将新子路径的起始点移动到 (x, y) 坐标。 |
| [quadraticCurveTo](../../com.aspose.html.dom.canvas/icanvaspathmethods/quadraticcurveto/)(double, double, double, double) | 向当前路径添加二次 Bézier 曲线。 |
| [rect](../../com.aspose.html.dom.canvas/icanvaspathmethods/rect/)(double, double, double, double) | 在位置 (x, y) 创建一个矩形路径，其大小由 width 和 height 决定。 |

### 另请参阅

* package [com.aspose.html.dom.canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
