---
title: Path2D class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 80
url: /aspose.html.dom.canvas/path2d/
is_root: false
---

## Path2D class

The Path2D interface of the Canvas 2D API is used to declare paths that are then later used on CanvasRenderingContext2D objects. 
The path methods of the CanvasRenderingContext2D interface are present on this interface as well and are allowing you to create 
paths that you can retain and replay as required on a canvas.



**Inheritance:** [`Path2D`](/html/python-net/aspose.html.dom.canvas/path2d) → 
[`DOMObject`](/html/python-net/aspose.html.dom/domobject)



The Path2D type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/html/python-net/aspose.html.dom.canvas/path2d/__init__/#) | returns a newly instantiated Path2D object |
| [__init__](/html/python-net/aspose.html.dom.canvas/path2d/__init__/#aspose.html.dom.canvas.Path2D) | returns a newly instantiated Path2D object with another path as an argument (creates a copy) |
| [__init__](/html/python-net/aspose.html.dom.canvas/path2d/__init__/#str) | returns a newly instantiated Path2D object with a string consisting of SVG path data. |


### Methods
| Method | Description |
| :- | :- |
| [add_path](/html/python-net/aspose.html.dom.canvas/path2d/add_path/#aspose.html.dom.canvas.Path2D) | Adds to the path the path given by the argument. |
| [add_path](/html/python-net/aspose.html.dom.canvas/path2d/add_path/#aspose.html.dom.canvas.Path2D-aspose.html.dom.svg.datatypes.SVGMatrix) | Adds to the path the path given by the argument. |
| [arc](/html/python-net/aspose.html.dom.canvas/path2d/arc/#float-float-float-float-float) | Adds an arc to the path which is centered at (x, y) position with radius r starting at startAngle and ending at endAngle going in the given direction by anticlockwise (defaulting to clockwise). |
| [arc](/html/python-net/aspose.html.dom.canvas/path2d/arc/#float-float-float-float-float-bool) | Adds an arc to the path which is centered at (x, y) position with radius r starting at startAngle and ending at endAngle going in the given direction by anticlockwise (defaulting to clockwise). |
| [ellipse](/html/python-net/aspose.html.dom.canvas/path2d/ellipse/#float-float-float-float-float-float-float) | Adds an ellipse to the path which is centered at (x, y) position with the radii radiusX and radiusY starting at startAngle<br/>and ending at endAngle going in the given direction by anticlockwise (defaulting to clockwise). |
| [ellipse](/html/python-net/aspose.html.dom.canvas/path2d/ellipse/#float-float-float-float-float-float-float-bool) | Adds an ellipse to the path which is centered at (x, y) position with the radii radiusX and radiusY starting at startAngle<br/>and ending at endAngle going in the given direction by anticlockwise (defaulting to clockwise). |
| [get_platform_type](/html/python-net/aspose.html.dom.canvas/path2d/get_platform_type/#) | This method is used to retrieve ECMAScript object Type. |
| [close_path](/html/python-net/aspose.html.dom.canvas/path2d/close_path/#) | Causes the point of the pen to move back to the start of the current sub-path. <br/>It tries to draw a straight line from the current point to the start. <br/>If the shape has already been closed or has only one point, this function does nothing. |
| [move_to](/html/python-net/aspose.html.dom.canvas/path2d/move_to/#float-float) | Moves the starting point of a new sub-path to the (x, y) coordinates. |
| [line_to](/html/python-net/aspose.html.dom.canvas/path2d/line_to/#float-float) | Connects the last point in the subpath to the x, y coordinates with a straight line. |
| [quadratic_curve_to](/html/python-net/aspose.html.dom.canvas/path2d/quadratic_curve_to/#float-float-float-float) | Adds a quadratic Bézier curve to the current path. |
| [bezier_curve_to](/html/python-net/aspose.html.dom.canvas/path2d/bezier_curve_to/#float-float-float-float-float-float) | Adds a cubic Bézier curve to the path. It requires three points. <br/>The first two points are control points and the third one is the end point. <br/>The starting point is the last point in the current path, <br/>which can be changed using moveTo() before creating the Bézier curve. |
| [arc_to](/html/python-net/aspose.html.dom.canvas/path2d/arc_to/#float-float-float-float-float) | Adds an arc to the path with the given control points and radius, connected to the previous point by a straight line. |
| [rect](/html/python-net/aspose.html.dom.canvas/path2d/rect/#float-float-float-float) | Creates a path for a rectangle at position (x, y) with a size that is determined by width and height. |



### See Also
* module [`aspose.html.dom.canvas`](..)
* class [`DOMObject`](/html/python-net/aspose.html.dom/domobject)
* class [`Path2D`](/html/python-net/aspose.html.dom.canvas/path2d)
