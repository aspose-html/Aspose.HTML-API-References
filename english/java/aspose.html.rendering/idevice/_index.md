---
title: IDevice Interface
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.rendering.IDevice interface. Defines methods and properties that support custom rendering of the graphic elements like paths text and images
type: docs

url: /java/com.aspose.html.rendering/idevice/
---
## IDevice interface

Defines methods and properties that support custom rendering of the graphic elements like paths, text and images.

```java
public interface IDevice : IDisposable
```

## Properties

| Name | Description |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/idevice/graphiccontext/) Gets the graphic context. |
| [getOptions](../../com.aspose.html.rendering/idevice/options/) Gets rendering options. |

## Methods

| Name | Description |
| --- | --- |
| [addRect](../../com.aspose.html.rendering/idevice/addrect/)(RectangleF) | Appends a rectangle to the current path as a complete subpath. |
| [beginDocument](../../com.aspose.html.rendering/idevice/begindocument/)(Document) | Begins rendering of the document. |
| [beginElement](../../com.aspose.html.rendering/idevice/beginelement/)(Element, RectangleF) | Begins rendering of the element. |
| [beginPage](../../com.aspose.html.rendering/idevice/beginpage/)(SizeF) | Begins rendering of the new page. |
| [clip](../../com.aspose.html.rendering/idevice/clip/)(FillRule) | Modifies the current clipping path by intersecting it with the current path, using the FillRule to determine the region to fill. This method terminates current path. |
| [closePath](../../com.aspose.html.rendering/idevice/closepath/)() | Closes the current subpath by appending a straight line segment from the current point to the starting point of the subpath. If the current subpath is already closed, "ClosePath" does nothing. This operator terminates the current subpath. Appending another segment to the current path begins a new subpath, even if the new segment begins at the endpoint reached by the "ClosePath" method. |
| [cubicBezierTo](../../com.aspose.html.rendering/idevice/cubicbezierto/)(PointF, PointF, PointF) | Appends a cubic Bézier curve to the current path. The curve extends from the current point to the point pt3, using pt1 and pt2 as the Bézier control points. The new current point is pt3. |
| [drawImage](../../com.aspose.html.rendering/idevice/drawimage/)(byte[], WebImageFormat, RectangleF) | Draws the specified image. |
| [endDocument](../../com.aspose.html.rendering/idevice/enddocument/)() | Ends rendering of the document. |
| [endElement](../../com.aspose.html.rendering/idevice/endelement/)(Element) | Ends rendering of the element. |
| [endPage](../../com.aspose.html.rendering/idevice/endpage/)() | Ends rendering of the current page. |
| [fill](../../com.aspose.html.rendering/idevice/fill/)(FillRule) | Fills the entire region enclosed by the current path. If the path consists of several disconnected subpaths, it fills the insides of all subpaths, considered together. This method terminates current path. |
| [fillText](../../com.aspose.html.rendering/idevice/filltext/)(String, PointF) | Fills the specified text String at the specified location. |
| [flush](../../com.aspose.html.rendering/idevice/flush/)() | Flushes all data to output stream. |
| [lineTo](../../com.aspose.html.rendering/idevice/lineto/)(PointF) | Appends a straight line segment from the current point to the point (pt). The new current point is pt. |
| [moveTo](../../com.aspose.html.rendering/idevice/moveto/)(PointF) | Begins a new subpath by moving the current point to coordinates of the parameter pt, omitting any connecting line segment. If the previous path construction method in the current path was also "MoveTo", the new "MoveTo" overrides it; no vestige of the previous "MoveTo" operation remains in the path. |
| [restoreGraphicContext](../../com.aspose.html.rendering/idevice/restoregraphiccontext/)() | Restores the entire graphics context to its former value by popping it from the stack. |
| [saveGraphicContext](../../com.aspose.html.rendering/idevice/savegraphiccontext/)() | Pushes a copy of the entire graphics context onto the stack. |
| [stroke](../../com.aspose.html.rendering/idevice/stroke/)() | Strokes a line along the current path. The stroked line follows each straight or curved segment in the path, centered on the segment with sides parallel to it. Each of the path’s subpaths is treated separately. This method terminates current path. |
| [strokeAndFill](../../com.aspose.html.rendering/idevice/strokeandfill/)(FillRule) | Strokes and fill current path. This method terminates current path. |
| [strokeText](../../com.aspose.html.rendering/idevice/stroketext/)(String, PointF) | Strokes the specified text String at the specified location. |

### See Also

* package [com.aspose.html.rendering](../../com.aspose.html.rendering/)
* package [Aspose.HTML](../../)
