---
title: ImageDevice Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Rendering.Image.ImageDevice class. Represents rendering to raster formats jpeg png bmp gif tiff
type: docs
weight: 4510
url: /net/aspose.html.rendering.image/imagedevice/
---
## ImageDevice class

Represents rendering to raster formats: jpeg, png, bmp, gif, tiff.

```csharp
public class ImageDevice : Device<ImageGraphicContext, ImageRenderingOptions>
```

## Constructors

| Name | Description |
| --- | --- |
| [ImageDevice](imagedevice/#constructor)(ICreateStreamProvider) | Initializes a new instance of the `ImageDevice` class. |
| [ImageDevice](imagedevice/#constructor_4)(Stream) | Initializes a new instance of the `ImageDevice` class. |
| [ImageDevice](imagedevice/#constructor_5)(string) | Initializes a new instance of the `ImageDevice` class. |
| [ImageDevice](imagedevice/#constructor_1)(ImageRenderingOptions, ICreateStreamProvider) | Initializes a new instance of the `ImageDevice` class by rendering options and stream provider. |
| [ImageDevice](imagedevice/#constructor_2)(ImageRenderingOptions, Stream) | Initializes a new instance of the `ImageDevice` class by rendering options and output stream. |
| [ImageDevice](imagedevice/#constructor_3)(ImageRenderingOptions, string) | Initializes a new instance of the `ImageDevice` class by rendering options and output file name. |

## Properties

| Name | Description |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } |  |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } |  |

## Methods

| Name | Description |
| --- | --- |
| virtual [AddRect](../../aspose.html.rendering/device-2/addrect/)(RectangleF) |  |
| virtual [BeginDocument](../../aspose.html.rendering/device-2/begindocument/)(Document) |  |
| virtual [BeginElement](../../aspose.html.rendering/device-2/beginelement/)(Element, RectangleF) |  |
| virtual [BeginPage](../../aspose.html.rendering/device-2/beginpage/)(SizeF) |  |
| virtual [Clip](../../aspose.html.rendering/device-2/clip/)(FillRule) |  |
| virtual [ClosePath](../../aspose.html.rendering/device-2/closepath/)() |  |
| virtual [CubicBezierTo](../../aspose.html.rendering/device-2/cubicbezierto/)(PointF, PointF, PointF) |  |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() |  |
| virtual [DrawImage](../../aspose.html.rendering/device-2/drawimage/)(byte[], WebImageFormat, RectangleF) |  |
| virtual [EndDocument](../../aspose.html.rendering/device-2/enddocument/)() |  |
| virtual [EndElement](../../aspose.html.rendering/device-2/endelement/)(Element) |  |
| virtual [EndPage](../../aspose.html.rendering/device-2/endpage/)() |  |
| virtual [Fill](../../aspose.html.rendering/device-2/fill/)(FillRule) |  |
| virtual [FillText](../../aspose.html.rendering/device-2/filltext/)(string, PointF) |  |
| virtual [Flush](../../aspose.html.rendering/device-2/flush/)() |  |
| virtual [LineTo](../../aspose.html.rendering/device-2/lineto/)(PointF) |  |
| virtual [MoveTo](../../aspose.html.rendering/device-2/moveto/)(PointF) |  |
| virtual [RestoreGraphicContext](../../aspose.html.rendering/device-2/restoregraphiccontext/)() |  |
| virtual [SaveGraphicContext](../../aspose.html.rendering/device-2/savegraphiccontext/)() |  |
| virtual [Stroke](../../aspose.html.rendering/device-2/stroke/)() |  |
| virtual [StrokeAndFill](../../aspose.html.rendering/device-2/strokeandfill/)(FillRule) |  |
| virtual [StrokeText](../../aspose.html.rendering/device-2/stroketext/)(string, PointF) |  |

## Other Members

| Name | Description |
| --- | --- |
| class [ImageGraphicContext](../../aspose.html.rendering.image/imagedevice.imagegraphiccontext) | Holds current graphics control parameters for the `ImageDevice`. These parameters define the global framework within which the graphics operators execute. |

### See Also

* class [ImageGraphicContext](../imagedevice.imagegraphiccontext/)
* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2/)
* class [ImageRenderingOptions](../imagerenderingoptions/)
* namespace [Aspose.Html.Rendering.Image](../../aspose.html.rendering.image/)
* assembly [Aspose.HTML](../../)
