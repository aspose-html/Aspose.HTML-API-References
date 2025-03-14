---
title: IDevice Interface
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Rendering.IDevice interface. Defines methods and properties that support custom rendering of the graphic elements like paths text and images
type: docs
weight: 4500
url: /net/aspose.html.rendering/idevice/
---
## IDevice interface

Defines methods and properties that support custom rendering of the graphic elements like paths, text and images.

```csharp
public interface IDevice : IDisposable
```

## Members
## Properties

| Name | Description |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/idevice/graphiccontext/) { get; } | Gets the graphic context. |
| [Options](../../aspose.html.rendering/idevice/options/) { get; } | Gets rendering options. |

## Members
## Methods

| Name | Description |
| --- | --- |
| [AddRect](../../aspose.html.rendering/idevice/addrect/)(*RectangleF*) | Appends a rectangle to the current path as a complete subpath. |
| [BeginDocument](../../aspose.html.rendering/idevice/begindocument/)(*[Document](../../aspose.html.dom/document/)*) | Begins rendering of the document. |
| [BeginElement](../../aspose.html.rendering/idevice/beginelement/)(*[Element](../../aspose.html.dom/element/), RectangleF*) | Begins rendering of the element. |
| [BeginPage](../../aspose.html.rendering/idevice/beginpage/)(*SizeF*) | Begins rendering of the new page. |
| [Clip](../../aspose.html.rendering/idevice/clip/)(*[FillRule](../fillrule/)*) | Modifies the current clipping path by intersecting it with the current path, using the FillRule to determine the region to fill. This method terminates current path. |
| [ClosePath](../../aspose.html.rendering/idevice/closepath/)() | Closes the current subpath by appending a straight line segment from the current point to the starting point of the subpath. If the current subpath is already closed, "ClosePath" does nothing. This operator terminates the current subpath. Appending another segment to the current path begins a new subpath, even if the new segment begins at the endpoint reached by the "ClosePath" method. |
| [CubicBezierTo](../../aspose.html.rendering/idevice/cubicbezierto/)(*PointF, PointF, PointF*) | Appends a cubic Bézier curve to the current path. The curve extends from the current point to the point pt3, using pt1 and pt2 as the Bézier control points. The new current point is pt3. |
| [DrawImage](../../aspose.html.rendering/idevice/drawimage/)(*byte[], [WebImageFormat](../../aspose.html.drawing/webimageformat/), RectangleF*) | Draws the specified image. |
| [EndDocument](../../aspose.html.rendering/idevice/enddocument/)() | Ends rendering of the document. |
| [EndElement](../../aspose.html.rendering/idevice/endelement/)(*[Element](../../aspose.html.dom/element/)*) | Ends rendering of the element. |
| [EndPage](../../aspose.html.rendering/idevice/endpage/)() | Ends rendering of the current page. |
| [Fill](../../aspose.html.rendering/idevice/fill/)(*[FillRule](../fillrule/)*) | Fills the entire region enclosed by the current path. If the path consists of several disconnected subpaths, it fills the insides of all subpaths, considered together. This method terminates current path. |
| [FillText](../../aspose.html.rendering/idevice/filltext/)(*string, PointF*) | Fills the specified text string at the specified location. |
| [Flush](../../aspose.html.rendering/idevice/flush/)() | Flushes all data to output stream. |
| [LineTo](../../aspose.html.rendering/idevice/lineto/)(*PointF*) | Appends a straight line segment from the current point to the point (pt). The new current point is pt. |
| [MoveTo](../../aspose.html.rendering/idevice/moveto/)(*PointF*) | Begins a new subpath by moving the current point to coordinates of the parameter pt, omitting any connecting line segment. If the previous path construction method in the current path was also "MoveTo", the new "MoveTo" overrides it; no vestige of the previous "MoveTo" operation remains in the path. |
| [RestoreGraphicContext](../../aspose.html.rendering/idevice/restoregraphiccontext/)() | Restores the entire graphics context to its former value by popping it from the stack. |
| [SaveGraphicContext](../../aspose.html.rendering/idevice/savegraphiccontext/)() | Pushes a copy of the entire graphics context onto the stack. |
| [Stroke](../../aspose.html.rendering/idevice/stroke/)() | Strokes a line along the current path. The stroked line follows each straight or curved segment in the path, centered on the segment with sides parallel to it. Each of the path’s subpaths is treated separately. This method terminates current path. |
| [StrokeAndFill](../../aspose.html.rendering/idevice/strokeandfill/)(*[FillRule](../fillrule/)*) | Strokes and fill current path. This method terminates current path. |
| [StrokeText](../../aspose.html.rendering/idevice/stroketext/)(*string, PointF*) | Strokes the specified text string at the specified location. |

### See Also

* namespace [Aspose.Html.Rendering](../../aspose.html.rendering/)
* assembly [Aspose.HTML](../../)
