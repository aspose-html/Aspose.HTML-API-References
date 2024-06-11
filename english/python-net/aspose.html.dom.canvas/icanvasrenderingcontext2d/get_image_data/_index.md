---
title: get_image_data method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 200
url: /python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/get_image_data/
is_root: false
---

## get_image_data {#float-float-float-float}

Returns an ImageData object representing the underlying pixel data for the area of the canvas denoted by the rectangle which starts at (sx, sy) and has an sw width and sh height.
This method is not affected by the canvas transformation matrix.


### Returns 


An ImageData object containing the image data for the given rectangle of the canvas.


```python
def get_image_data(self, sx, sy, sw, sh):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| sx | float | The x coordinate of the upper left corner of the rectangle from which the ImageData will be extracted. |
| sy | float | The y coordinate of the upper left corner of the rectangle from which the ImageData will be extracted. |
| sw | float | The width of the rectangle from which the ImageData will be extracted. |
| sh | float | The height of the rectangle from which the ImageData will be extracted. |



### See Also
* module [`aspose.html.dom.canvas`](../../)
* class [`ICanvasRenderingContext2D`](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d)
