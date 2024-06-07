---
title: put_image_data method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 270
url: /aspose.html.dom.canvas/icanvasrenderingcontext2d/put_image_data/
is_root: false
---

## put_image_data {#aspose.html.dom.canvas.IImageData-float-float}

Paints data from the given ImageData object onto the bitmap. 
If a dirty rectangle is provided, only the pixels from that rectangle are painted. 
This method is not affected by the canvas transformation matrix.



```python
def put_image_data(self, imagedata, dx, dy):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| imagedata | [`IImageData`](/html/python-net/aspose.html.dom.canvas/iimagedata) | An ImageData object containing the array of pixel values. |
| dx | float | Horizontal position (x-coordinate) at which to place the image data in the destination canvas. |
| dy | float | Vertical position (y-coordinate) at which to place the image data in the destination canvas. |


## put_image_data {#aspose.html.dom.canvas.IImageData-float-float-float-float-float-float}

Paints data from the given ImageData object onto the bitmap. 
If a dirty rectangle is provided, only the pixels from that rectangle are painted. 
This method is not affected by the canvas transformation matrix.



```python
def put_image_data(self, imagedata, dx, dy, dirty_x, dirty_y, dirty_width, dirty_height):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| imagedata | [`IImageData`](/html/python-net/aspose.html.dom.canvas/iimagedata) | An ImageData object containing the array of pixel values. |
| dx | float | Horizontal position (x-coordinate) at which to place the image data in the destination canvas. |
| dy | float | Vertical position (y-coordinate) at which to place the image data in the destination canvas. |
| dirty_x | float | Horizontal position (x-coordinate). The x coordinate of the top left hand corner of your Image data. Defaults to 0. |
| dirty_y | float | Vertical position (y-coordinate). The y coordinate of the top left hand corner of your Image data. Defaults to 0. |
| dirty_width | float | Width of the rectangle to be painted. Defaults to the width of the image data. |
| dirty_height | float | Height of the rectangle to be painted. Defaults to the height of the image data. |



### See Also
* module [`aspose.html.dom.canvas`](../../)
* class [`ICanvasRenderingContext2D`](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d)
