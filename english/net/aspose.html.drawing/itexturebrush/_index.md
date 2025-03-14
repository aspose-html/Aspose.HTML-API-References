---
title: ITextureBrush Interface
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Drawing.ITextureBrush interface. Defines brush interface that uses an image to fill the interior of a shape
type: docs
weight: 2930
url: /net/aspose.html.drawing/itexturebrush/
---
## ITextureBrush interface

Defines brush interface that uses an image to fill the interior of a shape.

```csharp
public interface ITextureBrush : ITransformableBrush
```

## Members
## Properties

| Name | Description |
| --- | --- |
| [ColorMap](../../aspose.html.drawing/itexturebrush/colormap/) { get; } | The number of elements must be even. Every even element is old color. Every odd element is new color. |
| [Image](../../aspose.html.drawing/itexturebrush/image/) { get; } | Gets or sets the image used by the brush. |
| [ImageArea](../../aspose.html.drawing/itexturebrush/imagearea/) { get; } | Specifies the portion of the image used by the brush. If it equals RectangleF.Empty then the whole image will be used. Coordinates are in pixels. |
| [Opacity](../../aspose.html.drawing/itexturebrush/opacity/) { get; set; } | Get opacity value in a color transform matrix. |

### See Also

* interface [ITransformableBrush](../itransformablebrush/)
* namespace [Aspose.Html.Drawing](../../aspose.html.drawing/)
* assembly [Aspose.HTML](../../)
