---
title: clip method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 80
url: /aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/
is_root: false
---

## clip {#}

Creates a new clipping region by calculating the intersection of the current clipping region and the area described by the path, using the non-zero winding number rule.
Open subpaths must be implicitly closed when computing the clipping region, without affecting the actual subpaths.
The new clipping region replaces the current clipping region.



```python
def clip(self):
    ...
```




## clip {#aspose.html.dom.canvas.CanvasFillRule}

Creates a new clipping region by calculating the intersection of the current clipping region and the area described by the path, using the non-zero winding number rule. 
Open subpaths must be implicitly closed when computing the clipping region, without affecting the actual subpaths.
The new clipping region replaces the current clipping region.



```python
def clip(self, fill_rule):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| fill_rule | [`CanvasFillRule`](/html/python-net/aspose.html.dom.canvas/canvasfillrule) | The algorithm by which to determine if a point is inside a path or outside a path |


## clip {#aspose.html.dom.canvas.Path2D-aspose.html.dom.canvas.CanvasFillRule}

Creates a new clipping region by calculating the intersection of the current clipping region and the area described by the path, using the non-zero winding number rule. 
Open subpaths must be implicitly closed when computing the clipping region, without affecting the actual subpaths.
The new clipping region replaces the current clipping region.



```python
def clip(self, path, fill_rule):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| path | [`Path2D`](/html/python-net/aspose.html.dom.canvas/path2d) | A Path2D path to clip. |
| fill_rule | [`CanvasFillRule`](/html/python-net/aspose.html.dom.canvas/canvasfillrule) | The algorithm by which to determine if a point is inside a path or outside a path. |



### See Also
* module [`aspose.html.dom.canvas`](../../)
* class [`ICanvasRenderingContext2D`](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d)
