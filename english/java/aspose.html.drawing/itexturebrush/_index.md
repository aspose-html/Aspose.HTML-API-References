---
title: ITextureBrush Interface
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.Drawing.ITextureBrush interface. Defines brush interface that uses an image to fill the interior of a shape
type: docs
weight: 2750
url: /java/com.aspose.html.drawing/itexturebrush/
---
## ITextureBrush interface

Defines brush interface that uses an image to fill the interior of a shape.

```java
public interface ITextureBrush : ITransformableBrush
```

## Properties

| Name | Description |
| --- | --- |
| [getColorMap](../../com.aspose.html.drawing/itexturebrush/colormap/) The number of elements must be even. Every even element is old color. Every odd element is new color. |
| [getImage](../../com.aspose.html.drawing/itexturebrush/image/) Gets or sets the image used by the brush. |
| [getImageArea](../../com.aspose.html.drawing/itexturebrush/imagearea/) Specifies the portion of the image used by the brush. If it equals RectangleF.Empty then the whole image will be used. Coordinates are in pixels. |
| [getOpacity](../../com.aspose.html.drawing/itexturebrush/opacity/) Get opacity value in a color transform matrix. |

### See Also

* interface [ITransformableBrush](../itransformablebrush/)
* package [com.aspose.html.Drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
