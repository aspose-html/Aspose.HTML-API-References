---
title: arc method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 20
url: /aspose.html.dom.canvas/icanvaspathmethods/arc/
is_root: false
---

## arc {#float-float-float-float-float}

Adds an arc to the path which is centered at (x, y) position with radius r starting at startAngle and ending at endAngle going in the given direction by anticlockwise (defaulting to clockwise).



```python
def arc(self, x, y, radius, start_angle, end_angle):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The x coordinate of the arc's center. |
| y | float | The y coordinate of the arc's center. |
| radius | float | The arc's radius. |
| start_angle | float | The angle at which the arc starts, measured clockwise from the positive x axis and expressed in radians. |
| end_angle | float | The angle at which the arc ends, measured clockwise from the positive x axis and expressed in radians. |


## arc {#float-float-float-float-float-bool}

Adds an arc to the path which is centered at (x, y) position with radius r starting at startAngle and ending at endAngle going in the given direction by anticlockwise (defaulting to clockwise).



```python
def arc(self, x, y, radius, start_angle, end_angle, counterclockwise):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | float | The x coordinate of the arc's center. |
| y | float | The y coordinate of the arc's center. |
| radius | float | The arc's radius. |
| start_angle | float | The angle at which the arc starts, measured clockwise from the positive x axis and expressed in radians. |
| end_angle | float | The angle at which the arc ends, measured clockwise from the positive x axis and expressed in radians. |
| counterclockwise | bool | Causes the arc to be drawn counter-clockwise between the two angles. By default it is drawn clockwise. |



### See Also
* module [`aspose.html.dom.canvas`](../../)
* class [`ICanvasPathMethods`](/html/python-net/aspose.html.dom.canvas/icanvaspathmethods)
