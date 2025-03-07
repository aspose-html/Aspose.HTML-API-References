---
title: ICanvasRenderingContext2D.PutImageData
second_title: Aspose.HTML for .NET API Reference
description: ICanvasRenderingContext2D PutImageData method. Paints data from the given ImageData object onto the bitmap. If a dirty rectangle is provided only the pixels from that rectangle are painted. This method is not affected by the canvas transformation matrix
type: docs
weight: 290
url: /net/aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/
---
## PutImageData(*[IImageData](../../iimagedata/), double, double*) {#putimagedata}

Paints data from the given ImageData object onto the bitmap. If a dirty rectangle is provided, only the pixels from that rectangle are painted. This method is not affected by the canvas transformation matrix.

```csharp
public void PutImageData(IImageData imagedata, double dx, double dy)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imagedata | IImageData | An ImageData object containing the array of pixel values. |
| dx | Double | Horizontal position (x-coordinate) at which to place the image data in the destination canvas. |
| dy | Double | Vertical position (y-coordinate) at which to place the image data in the destination canvas. |

### See Also

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* namespace [Aspose.Html.Dom.Canvas](../../../aspose.html.dom.canvas/)
* assembly [Aspose.HTML](../../../)

---

## PutImageData(*[IImageData](../../iimagedata/), double, double, double, double, double, double*) {#putimagedata_1}

Paints data from the given ImageData object onto the bitmap. If a dirty rectangle is provided, only the pixels from that rectangle are painted. This method is not affected by the canvas transformation matrix.

```csharp
public void PutImageData(IImageData imagedata, double dx, double dy, double dirtyX, double dirtyY, 
    double dirtyWidth, double dirtyHeight)
```

| Parameter | Type | Description |
| --- | --- | --- |
| imagedata | IImageData | An ImageData object containing the array of pixel values. |
| dx | Double | Horizontal position (x-coordinate) at which to place the image data in the destination canvas. |
| dy | Double | Vertical position (y-coordinate) at which to place the image data in the destination canvas. |
| dirtyX | Double | Horizontal position (x-coordinate). The x coordinate of the top left hand corner of your Image data. Defaults to 0. |
| dirtyY | Double | Vertical position (y-coordinate). The y coordinate of the top left hand corner of your Image data. Defaults to 0. |
| dirtyWidth | Double | Width of the rectangle to be painted. Defaults to the width of the image data. |
| dirtyHeight | Double | Height of the rectangle to be painted. Defaults to the height of the image data. |

### See Also

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* namespace [Aspose.Html.Dom.Canvas](../../../aspose.html.dom.canvas/)
* assembly [Aspose.HTML](../../../)
