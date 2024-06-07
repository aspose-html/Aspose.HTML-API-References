---
title: bezier_curve_to method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 40
url: /aspose.html.dom.canvas/icanvaspathmethods/bezier_curve_to/
is_root: false
---

## bezier_curve_to {#float-float-float-float-float-float}

Adds a cubic Bézier curve to the path. It requires three points. 
The first two points are control points and the third one is the end point. 
The starting point is the last point in the current path, 
which can be changed using moveTo() before creating the Bézier curve.



```python
def bezier_curve_to(self, cp_1x, cp_1y, cp_2x, cp_2y, x, y):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| cp_1x | float | The x axis of the coordinate for the first control point. |
| cp_1y | float | The y axis of the coordinate for the first control point. |
| cp_2x | float | The x axis of the coordinate for the second control point. |
| cp_2y | float | The y axis of the coordinate for the second control point. |
| x | float | The x axis of the coordinate for the end point. |
| y | float | The y axis of the coordinate for the end point. |



### See Also
* module [`aspose.html.dom.canvas`](../../)
* class [`ICanvasPathMethods`](/html/python-net/aspose.html.dom.canvas/icanvaspathmethods)
