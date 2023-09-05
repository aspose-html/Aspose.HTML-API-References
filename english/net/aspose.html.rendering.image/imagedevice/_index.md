---
title: ImageDevice Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Rendering.Image.ImageDevice class. Represents rendering to raster formats jpeg png bmp gif tiff
type: docs
weight: 4460
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
| virtual [Graphics](../../aspose.html.rendering.image/imagedevice/graphics/) { get; } | Gets the instance of Graphics. |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } |  |

## Methods

| Name | Description |
| --- | --- |
| override [AddRect](../../aspose.html.rendering.image/imagedevice/addrect/)(RectangleF) | Appends a rectangle to the current path as a complete subpath. |
| override [BeginDocument](../../aspose.html.rendering.image/imagedevice/begindocument/)(Document) | Begins rendering of the document. |
| override [BeginElement](../../aspose.html.rendering.image/imagedevice/beginelement/)(Element, RectangleF) | Begins rendering of the element. |
| override [BeginPage](../../aspose.html.rendering.image/imagedevice/beginpage/)(SizeF) | Begins rendering of the new page. |
| override [Clip](../../aspose.html.rendering.image/imagedevice/clip/)(FillMode) | Modifies the current clipping path by intersecting it with the current path, using the FillMode rule to determine the region to fill. This method terminates current path. |
| override [ClosePath](../../aspose.html.rendering.image/imagedevice/closepath/)() | Closes the current subpath by appending a straight line segment from the current point to the starting point of the subpath. If the current subpath is already closed, "ClosePath" does nothing. This operator terminates the current subpath. Appending another segment to the current path begins a new subpath, even if the new segment begins at the endpoint reached by the "ClosePath" method. |
| override [CubicBezierTo](../../aspose.html.rendering.image/imagedevice/cubicbezierto/)(PointF, PointF, PointF) | Appends a cubic Bézier curve to the current path. The curve extends from the current point to the point pt2, using pt1 and pt2 as the Bézier control points. The new current point is pt3. |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() |  |
| override [DrawImage](../../aspose.html.rendering.image/imagedevice/drawimage/)(byte[], ImageType, RectangleF) | Draws the specified image. |
| override [EndDocument](../../aspose.html.rendering.image/imagedevice/enddocument/)() | Ends rendering of the document. |
| override [EndElement](../../aspose.html.rendering.image/imagedevice/endelement/)(Element) | Ends rendering of the element. |
| override [EndPage](../../aspose.html.rendering.image/imagedevice/endpage/)() | Ends rendering of the current page. |
| override [Fill](../../aspose.html.rendering.image/imagedevice/fill/)(FillMode) | Fills the entire region enclosed by the current path. If the path consists of several disconnected subpaths, it fills the insides of all subpaths, considered together. This method terminates current path. |
| override [FillText](../../aspose.html.rendering.image/imagedevice/filltext/)(string, PointF) | Fills the specified text string at the specified location. |
| override [Flush](../../aspose.html.rendering.image/imagedevice/flush/)() | Flushes all data to output stream. |
| override [LineTo](../../aspose.html.rendering.image/imagedevice/lineto/)(PointF) | Appends a straight line segment from the current point to the point (pt). The new current point is pt. |
| override [MoveTo](../../aspose.html.rendering.image/imagedevice/moveto/)(PointF) | Begins a new subpath by moving the current point to coordinates of the parameter pt, omitting any connecting line segment. If the previous path construction method in the current path was also "MoveTo", the new "MoveTo" overrides it; no vestige of the previous "MoveTo" operation remains in the path. |
| override [RestoreGraphicContext](../../aspose.html.rendering.image/imagedevice/restoregraphiccontext/)() | Restores the entire graphics context to its former value by popping it from the stack. |
| override [SaveGraphicContext](../../aspose.html.rendering.image/imagedevice/savegraphiccontext/)() | Pushes a copy of the entire graphics context onto the stack. |
| override [Stroke](../../aspose.html.rendering.image/imagedevice/stroke/)() | Strokes a line along the current path. The stroked line follows each straight or curved segment in the path, centered on the segment with sides parallel to it. Each of the path’s subpaths is treated separately. This method terminates current path. |
| override [StrokeAndFill](../../aspose.html.rendering.image/imagedevice/strokeandfill/)(FillMode) | Strokes and fill current path. This method terminates current path. |
| override [StrokeText](../../aspose.html.rendering.image/imagedevice/stroketext/)(string, PointF) | Strokes the specified text string at the specified location. |

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
