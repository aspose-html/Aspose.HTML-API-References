---
title: ICanvasRenderingContext2D.GetImageData
second_title: Aspose.HTML for .NET API Reference
description: ICanvasRenderingContext2D GetImageData method. Returns an ImageData object representing the underlying pixel data for the area of the canvas denoted by the rectangle which starts at sx sy and has an sw width and sh height. This method is not affected by the canvas transformation matrix
type: docs
weight: 250
url: /net/aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata/
---
## ICanvasRenderingContext2D.GetImageData method

Returns an ImageData object representing the underlying pixel data for the area of the canvas denoted by the rectangle which starts at (sx, sy) and has an sw width and sh height. This method is not affected by the canvas transformation matrix.

```csharp
public IImageData GetImageData(double sx, double sy, double sw, double sh)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sx | Double | The x coordinate of the upper left corner of the rectangle from which the ImageData will be extracted. |
| sy | Double | The y coordinate of the upper left corner of the rectangle from which the ImageData will be extracted. |
| sw | Double | The width of the rectangle from which the ImageData will be extracted. |
| sh | Double | The height of the rectangle from which the ImageData will be extracted. |

### Return Value

An ImageData object containing the image data for the given rectangle of the canvas.

### See Also

* interface [IImageData](../../iimagedata/)
* interface [ICanvasRenderingContext2D](../)
* namespace [Aspose.Html.Dom.Canvas](../../../aspose.html.dom.canvas/)
* assembly [Aspose.HTML](../../../)
