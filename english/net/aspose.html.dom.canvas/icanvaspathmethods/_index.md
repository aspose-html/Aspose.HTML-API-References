---
title: ICanvasPathMethods Interface
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Dom.Canvas.ICanvasPathMethods interface. The ICanvasPathMethods interface is used to manipulate paths of objects
type: docs
weight: 390
url: /net/aspose.html.dom.canvas/icanvaspathmethods/
---
## ICanvasPathMethods interface

The ICanvasPathMethods interface is used to manipulate paths of objects.

```csharp
public interface ICanvasPathMethods
```

## Methods

| Name | Description |
| --- | --- |
| [Arc](../../aspose.html.dom.canvas/icanvaspathmethods/arc/#arc)(double, double, double, double, double) | Adds an arc to the path which is centered at (x, y) position with radius r starting at startAngle and ending at endAngle going in the given direction by anticlockwise (defaulting to clockwise). |
| [Arc](../../aspose.html.dom.canvas/icanvaspathmethods/arc/#arc_1)(double, double, double, double, double, bool) | Adds an arc to the path which is centered at (x, y) position with radius r starting at startAngle and ending at endAngle going in the given direction by anticlockwise (defaulting to clockwise). |
| [ArcTo](../../aspose.html.dom.canvas/icanvaspathmethods/arcto/)(double, double, double, double, double) | Adds an arc to the path with the given control points and radius, connected to the previous point by a straight line. |
| [BezierCurveTo](../../aspose.html.dom.canvas/icanvaspathmethods/beziercurveto/)(double, double, double, double, double, double) | Adds a cubic Bézier curve to the path. It requires three points. The first two points are control points and the third one is the end point. The starting point is the last point in the current path, which can be changed using moveTo() before creating the Bézier curve. |
| [ClosePath](../../aspose.html.dom.canvas/icanvaspathmethods/closepath/)() | Causes the point of the pen to move back to the start of the current sub-path. It tries to draw a straight line from the current point to the start. If the shape has already been closed or has only one point, this function does nothing. |
| [Ellipse](../../aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse)(double, double, double, double, double, double, double) | Adds an ellipse to the path which is centered at (x, y) position with the radii radiusX and radiusY starting at startAngle and ending at endAngle going in the given direction by anticlockwise (defaulting to clockwise). |
| [Ellipse](../../aspose.html.dom.canvas/icanvaspathmethods/ellipse/#ellipse_1)(double, double, double, double, double, double, double, bool) | Adds an ellipse to the path which is centered at (x, y) position with the radii radiusX and radiusY starting at startAngle and ending at endAngle going in the given direction by anticlockwise (defaulting to clockwise). |
| [LineTo](../../aspose.html.dom.canvas/icanvaspathmethods/lineto/)(double, double) | Connects the last point in the subpath to the x, y coordinates with a straight line. |
| [MoveTo](../../aspose.html.dom.canvas/icanvaspathmethods/moveto/)(double, double) | Moves the starting point of a new sub-path to the (x, y) coordinates. |
| [QuadraticCurveTo](../../aspose.html.dom.canvas/icanvaspathmethods/quadraticcurveto/)(double, double, double, double) | Adds a quadratic Bézier curve to the current path. |
| [Rect](../../aspose.html.dom.canvas/icanvaspathmethods/rect/)(double, double, double, double) | Creates a path for a rectangle at position (x, y) with a size that is determined by width and height. |

### See Also

* namespace [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas/)
* assembly [Aspose.HTML](../../)
