---
title: ellipse method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 60
url: /aspose.html.dom.canvas/icanvaspathmethods/ellipse/
is_root: false
---

## ellipse {#float-float-float-float-float-float-float}

Adds an ellipse to the path which is centered at (x, y) position with the radii radiusX and radiusY starting at startAngle
and ending at endAngle going in the given direction by anticlockwise (defaulting to clockwise).



```python
def ellipse(self, x, y, radius_x, radius_y, rotation, start_angle, end_angle):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The x axis of the coordinate for the ellipse's center. |
| y | float | The y axis of the coordinate for the ellipse's center. |
| radius_x | float | The ellipse's major-axis radius. |
| radius_y | float | The ellipse's minor-axis radius. |
| rotation | float | The rotation for this ellipse, expressed in radians. |
| start_angle | float | The starting point, measured from the x axis, from which it will be drawn, expressed in radians. |
| end_angle | float | The end ellipse's angle to which it will be drawn, expressed in radians. |


## ellipse {#float-float-float-float-float-float-float-bool}

Adds an ellipse to the path which is centered at (x, y) position with the radii radiusX and radiusY starting at startAngle
and ending at endAngle going in the given direction by anticlockwise (defaulting to clockwise).



```python
def ellipse(self, x, y, radius_x, radius_y, rotation, start_angle, end_angle, anticlockwise):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The x axis of the coordinate for the ellipse's center. |
| y | float | The y axis of the coordinate for the ellipse's center. |
| radius_x | float | The ellipse's major-axis radius. |
| radius_y | float | The ellipse's minor-axis radius. |
| rotation | float | The rotation for this ellipse, expressed in radians. |
| start_angle | float | The starting point, measured from the x axis, from which it will be drawn, expressed in radians. |
| end_angle | float | The end ellipse's angle to which it will be drawn, expressed in radians. |
| anticlockwise | bool | An optional boolean which, if true, draws the ellipse anticlockwise (counter-clockwise), otherwise in a clockwise direction. |



### See Also
* module [`aspose.html.dom.canvas`](../../)
* class [`ICanvasPathMethods`](/html/python-net/aspose.html.dom.canvas/icanvaspathmethods)
