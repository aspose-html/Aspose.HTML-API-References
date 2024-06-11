---
title: ICanvasPathMethods class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 30
url: /python-net/aspose.html.dom.canvas/icanvaspathmethods/
is_root: false
---

## ICanvasPathMethods class

The ICanvasPathMethods interface is used to manipulate paths of objects.



The ICanvasPathMethods type exposes the following members:

### Methods
| Method | Description |
| :- | :- |
| [arc](/html/python-net/aspose.html.dom.canvas/icanvaspathmethods/arc/#float-float-float-float-float) | Adds an arc to the path which is centered at (x, y) position with radius r starting at startAngle and ending at endAngle going in the given direction by anticlockwise (defaulting to clockwise). |
| [arc](/html/python-net/aspose.html.dom.canvas/icanvaspathmethods/arc/#float-float-float-float-float-bool) | Adds an arc to the path which is centered at (x, y) position with radius r starting at startAngle and ending at endAngle going in the given direction by anticlockwise (defaulting to clockwise). |
| [ellipse](/html/python-net/aspose.html.dom.canvas/icanvaspathmethods/ellipse/#float-float-float-float-float-float-float) | Adds an ellipse to the path which is centered at (x, y) position with the radii radiusX and radiusY starting at startAngle<br/>and ending at endAngle going in the given direction by anticlockwise (defaulting to clockwise). |
| [ellipse](/html/python-net/aspose.html.dom.canvas/icanvaspathmethods/ellipse/#float-float-float-float-float-float-float-bool) | Adds an ellipse to the path which is centered at (x, y) position with the radii radiusX and radiusY starting at startAngle<br/>and ending at endAngle going in the given direction by anticlockwise (defaulting to clockwise). |
| [close_path](/html/python-net/aspose.html.dom.canvas/icanvaspathmethods/close_path/#) | Causes the point of the pen to move back to the start of the current sub-path. <br/>It tries to draw a straight line from the current point to the start. <br/>If the shape has already been closed or has only one point, this function does nothing. |
| [move_to](/html/python-net/aspose.html.dom.canvas/icanvaspathmethods/move_to/#float-float) | Moves the starting point of a new sub-path to the (x, y) coordinates. |
| [line_to](/html/python-net/aspose.html.dom.canvas/icanvaspathmethods/line_to/#float-float) | Connects the last point in the subpath to the x, y coordinates with a straight line. |
| [quadratic_curve_to](/html/python-net/aspose.html.dom.canvas/icanvaspathmethods/quadratic_curve_to/#float-float-float-float) | Adds a quadratic Bézier curve to the current path. |
| [bezier_curve_to](/html/python-net/aspose.html.dom.canvas/icanvaspathmethods/bezier_curve_to/#float-float-float-float-float-float) | Adds a cubic Bézier curve to the path. It requires three points. <br/>The first two points are control points and the third one is the end point. <br/>The starting point is the last point in the current path, <br/>which can be changed using moveTo() before creating the Bézier curve. |
| [arc_to](/html/python-net/aspose.html.dom.canvas/icanvaspathmethods/arc_to/#float-float-float-float-float) | Adds an arc to the path with the given control points and radius, connected to the previous point by a straight line. |
| [rect](/html/python-net/aspose.html.dom.canvas/icanvaspathmethods/rect/#float-float-float-float) | Creates a path for a rectangle at position (x, y) with a size that is determined by width and height. |



### See Also
* module [`aspose.html.dom.canvas`](..)
