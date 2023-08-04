---
title: DeviceTGraphicContextTRenderingOptions Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.Rendering.Device2TGraphicContextTRenderingOptions class. Represents base class for implementation particular rendering devices
type: docs
weight: 4170
url: /java/com.aspose.html.rendering/device-2/
---
## Device&lt;TGraphicContext,TRenderingOptions&gt; class

Represents base class for implementation particular rendering devices.

```java
public abstract class Device<TGraphicContext, TRenderingOptions> : Device, IDevice
    where TGraphicContext : GraphicContext, new()
    where TRenderingOptions : RenderingOptions
```

| Parameter | Description |
| --- | --- |
| TGraphicContext | Graphic context that holds current graphics control parameters |
| TRenderingOptions | Rendering options |

## Properties

| Name | Description |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/) Gets the graphic context |
| [getOptions](../../com.aspose.html.rendering/device-2/options/) Gets rendering options. |

## Methods

| Name | Description |
| --- | --- |
| abstract [AddRect](../../com.aspose.html.rendering/device-2/addrect/)(RectangleF) | Appends a rectangle to the current path as a complete subpath. |
| [beginDocument](../../com.aspose.html.rendering/device-2/begindocument/)(Document) | Begins rendering of the document. |
| abstract [BeginElement](../../com.aspose.html.rendering/device-2/beginelement/)(Element, RectangleF) | Begins rendering of the node. |
| [beginPage](../../com.aspose.html.rendering/device-2/beginpage/)(SizeF) | Begins rendering of the new page. |
| abstract [Clip](../../com.aspose.html.rendering/device-2/clip/)(FillMode) | Modifies the current clipping path by intersecting it with the current path, using the FillMode rule to determine the region to fill. This method terminates current path. |
| abstract [ClosePath](../../com.aspose.html.rendering/device-2/closepath/)() | Closes the current subpath by appending a straight line segment from the current point to the starting point of the subpath. If the current subpath is already closed, "ClosePath" does nothing. This operator terminates the current subpath. Appending another segment to the current path begins a new subpath, even if the new segment begins at the endpoint reached by the "ClosePath" method. |
| abstract [CubicBezierTo](../../com.aspose.html.rendering/device-2/cubicbezierto/)(PointF, PointF, PointF) | Appends a cubic Bézier curve to the current path. The curve extends from the current point to the point pt2, using pt1 and pt2 as the Bézier control points. The new current point is pt3. |
| [dispose](../../com.aspose.html.rendering/device-2/dispose/)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| abstract [DrawImage](../../com.aspose.html.rendering/device-2/drawimage/)(byte[], ImageType, RectangleF) | Draws the specified image. |
| [endDocument](../../com.aspose.html.rendering/device-2/enddocument/)() | Ends rendering of the document. |
| abstract [EndElement](../../com.aspose.html.rendering/device-2/endelement/)(Element) | Ends rendering of the node. |
| [endPage](../../com.aspose.html.rendering/device-2/endpage/)() | Ends rendering of the current page. |
| abstract [Fill](../../com.aspose.html.rendering/device-2/fill/)(FillMode) | Fills the entire region enclosed by the current path. If the path consists of several disconnected subpaths, it fills the insides of all subpaths, considered together. This method terminates current path. |
| abstract [FillText](../../com.aspose.html.rendering/device-2/filltext/)(String, PointF) | Fills the specified text String at the specified location. |
| [flush](../../com.aspose.html.rendering/device-2/flush/)() | Flushes all data to output stream. |
| abstract [LineTo](../../com.aspose.html.rendering/device-2/lineto/)(PointF) | Appends a straight line segment from the current point to the point (pt). The new current point is pt. |
| abstract [MoveTo](../../com.aspose.html.rendering/device-2/moveto/)(PointF) | Begins a new subpath by moving the current point to coordinates of the parameter pt, omitting any connecting line segment. If the previous path construction method in the current path was also "MoveTo", the new "MoveTo" overrides it; no vestige of the previous "MoveTo" operation remains in the path. |
| [restoreGraphicContext](../../com.aspose.html.rendering/device-2/restoregraphiccontext/)() | Restores the entire graphics context to its former value by popping it from the stack. |
| [saveGraphicContext](../../com.aspose.html.rendering/device-2/savegraphiccontext/)() | Pushes a copy of the entire graphics context onto the stack. |
| abstract [Stroke](../../com.aspose.html.rendering/device-2/stroke/)() | Strokes a line along the current path. The stroked line follows each straight or curved segment in the path, centered on the segment with sides parallel to it. Each of the path’s subpaths is treated separately. This method terminates current path. |
| abstract [StrokeAndFill](../../com.aspose.html.rendering/device-2/strokeandfill/)(FillMode) | Strokes and fill current path. This method terminates current path. |
| abstract [StrokeText](../../com.aspose.html.rendering/device-2/stroketext/)(String, PointF) | Strokes the specified text String at the specified location. |

## Other Members

| Name | Description |
| --- | --- |
| class [DeviceConfiguration&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2.deviceconfiguration-2) |  |
| enum [PageWritingStrategy&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2.pagewritingstrategy-2) | Specifies types of strategies for writing pages into output stream\streams. |

### See Also

* class [Device](../device/)
* interface [IDevice](../idevice/)
* class [GraphicContext](../graphiccontext/)
* class [RenderingOptions](../renderingoptions/)
* package [com.aspose.html.Rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
