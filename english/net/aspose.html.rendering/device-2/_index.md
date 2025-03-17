---
title: DeviceTGraphicContextTRenderingOptions Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Rendering.Device2TGraphicContextTRenderingOptions class. Represents base class for implementation particular rendering devices
type: docs
weight: 4350
url: /net/aspose.html.rendering/device-2/
---
## Device&lt;TGraphicContext,TRenderingOptions&gt; class

Represents base class for implementation particular rendering devices.

```csharp
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
| [GraphicContext](../../aspose.html.rendering/device-2/graphiccontext/) { get; } | Gets the graphic context |
| [Options](../../aspose.html.rendering/device-2/options/) { get; } | Gets rendering options. |
| virtual [Configuration](../../aspose.html.rendering/device-2/configuration/) { get; } | Gets device configuration. |
| [OutputStream](../../aspose.html.rendering/device-2/outputstream/) { get; } | Sets and gets the output stream. |
| [StreamProvider](../../aspose.html.rendering/device-2/streamprovider/) { get; } | Gets the stream provider object. |

## Methods

| Name | Description |
| --- | --- |
| virtual [AddRect](../../aspose.html.rendering/device-2/addrect/)(*RectangleF*) | Appends a rectangle to the current path as a complete subpath. |
| virtual [BeginDocument](../../aspose.html.rendering/device-2/begindocument/)(*[Document](../../aspose.html.dom/document/)*) | Begins rendering of the document. |
| virtual [BeginElement](../../aspose.html.rendering/device-2/beginelement/)(*[Element](../../aspose.html.dom/element/), RectangleF*) | Begins rendering of the node. |
| virtual [BeginPage](../../aspose.html.rendering/device-2/beginpage/)(*SizeF*) | Begins rendering of the new page. |
| virtual [Clip](../../aspose.html.rendering/device-2/clip/)(*[FillRule](../fillrule/)*) | Modifies the current clipping path by intersecting it with the current path, using the FillRule to determine the region to fill. This method terminates current path. |
| virtual [ClosePath](../../aspose.html.rendering/device-2/closepath/)() | Closes the current subpath by appending a straight line segment from the current point to the starting point of the subpath. If the current subpath is already closed, "ClosePath" does nothing. This operator terminates the current subpath. Appending another segment to the current path begins a new subpath, even if the new segment begins at the endpoint reached by the "ClosePath" method. |
| virtual [CubicBezierTo](../../aspose.html.rendering/device-2/cubicbezierto/)(*PointF, PointF, PointF*) | Appends a cubic Bézier curve to the current path. The curve extends from the current point to the point pt2, using pt1 and pt2 as the Bézier control points. The new current point is pt3. |
| [Dispose](../../aspose.html.rendering/device-2/dispose/)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| virtual [DrawImage](../../aspose.html.rendering/device-2/drawimage/)(*byte[], [WebImageFormat](../../aspose.html.drawing/webimageformat/), RectangleF*) | Draws the specified image. |
| virtual [EndDocument](../../aspose.html.rendering/device-2/enddocument/)() | Ends rendering of the document. |
| virtual [EndElement](../../aspose.html.rendering/device-2/endelement/)(*[Element](../../aspose.html.dom/element/)*) | Ends rendering of the node. |
| virtual [EndPage](../../aspose.html.rendering/device-2/endpage/)() | Ends rendering of the current page. |
| virtual [Fill](../../aspose.html.rendering/device-2/fill/)(*[FillRule](../fillrule/)*) | Fills the entire region enclosed by the current path. If the path consists of several disconnected subpaths, it fills the insides of all subpaths, considered together. This method terminates current path. |
| virtual [FillText](../../aspose.html.rendering/device-2/filltext/)(*string, PointF*) | Fills the specified text string at the specified location. |
| virtual [Flush](../../aspose.html.rendering/device-2/flush/)() | Flushes all data to output stream. |
| virtual [LineTo](../../aspose.html.rendering/device-2/lineto/)(*PointF*) | Appends a straight line segment from the current point to the point (pt). The new current point is pt. |
| virtual [MoveTo](../../aspose.html.rendering/device-2/moveto/)(*PointF*) | Begins a new subpath by moving the current point to coordinates of the parameter pt, omitting any connecting line segment. If the previous path construction method in the current path was also "MoveTo", the new "MoveTo" overrides it; no vestige of the previous "MoveTo" operation remains in the path. |
| virtual [RestoreGraphicContext](../../aspose.html.rendering/device-2/restoregraphiccontext/)() | Restores the entire graphics context to its former value by popping it from the stack. |
| virtual [SaveGraphicContext](../../aspose.html.rendering/device-2/savegraphiccontext/)() | Pushes a copy of the entire graphics context onto the stack. |
| virtual [Stroke](../../aspose.html.rendering/device-2/stroke/)() | Strokes a line along the current path. The stroked line follows each straight or curved segment in the path, centered on the segment with sides parallel to it. Each of the path’s subpaths is treated separately. This method terminates current path. |
| virtual [StrokeAndFill](../../aspose.html.rendering/device-2/strokeandfill/)(*[FillRule](../fillrule/)*) | Strokes and fill current path. This method terminates current path. |
| virtual [StrokeText](../../aspose.html.rendering/device-2/stroketext/)(*string, PointF*) | Strokes the specified text string at the specified location. |

## Other Members

| Name | Description |
| --- | --- |
| class [DeviceConfiguration&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2.deviceconfiguration-2) |  |
| enum [PageWritingStrategy&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2.pagewritingstrategy-2) | Specifies types of strategies for writing pages into output stream\streams. |

### See Also

* class [Device](../device/)
* interface [IDevice](../idevice/)
* class [GraphicContext](../graphiccontext/)
* class [RenderingOptions](../renderingoptions/)
* namespace [Aspose.Html.Rendering](../../aspose.html.rendering/)
* assembly [Aspose.HTML](../../)
