---
title: XpsDevice Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.rendering.xps.XpsDevice class. Represents rendering to a xps document
type: docs
weight: 4560
url: /java/com.aspose.html.rendering.xps/xpsdevice/
---
## XpsDevice class

Represents rendering to a xps document.

```java
public class XpsDevice : Device<XpsGraphicContext, XpsRenderingOptions>
```

## Constructors

| Name | Description |
| --- | --- |
| [XpsDevice](xpsdevice/#constructor)(ICreateStreamProvider) | Initializes a new instance of the `XpsDevice` class. |
| [XpsDevice](xpsdevice/#constructor_4)(Stream) | Initializes a new instance of the `XpsDevice` class. |
| [XpsDevice](xpsdevice/#constructor_5)(String) | Initializes a new instance of the `XpsDevice` class. |
| [XpsDevice](xpsdevice/#constructor_1)(XpsRenderingOptions, ICreateStreamProvider) | Initializes a new instance of the `XpsDevice` class by rendering options and stream provider. |
| [XpsDevice](xpsdevice/#constructor_2)(XpsRenderingOptions, Stream) | Initializes a new instance of the `XpsDevice` class by rendering options and output stream. |
| [XpsDevice](xpsdevice/#constructor_3)(XpsRenderingOptions, String) | Initializes a new instance of the `XpsDevice` class by rendering options and output file name. |

## Properties

| Name | Description |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/)  |
| [getOptions](../../com.aspose.html.rendering/device-2/options/)  |

## Methods

| Name | Description |
| --- | --- |
| [addRect](../../com.aspose.html.rendering.xps/xpsdevice/addrect/)(RectangleF) | Appends a rectangle to the current path as a complete subpath. |
| [beginDocument](../../com.aspose.html.rendering.xps/xpsdevice/begindocument/)(Document) | Begins rendering of the document. |
| [beginElement](../../com.aspose.html.rendering.xps/xpsdevice/beginelement/)(Element, RectangleF) | Begins rendering of the element. |
| [beginPage](../../com.aspose.html.rendering.xps/xpsdevice/beginpage/)(SizeF) | Begins rendering of the new page. |
| [clip](../../com.aspose.html.rendering.xps/xpsdevice/clip/)(FillMode) | Modifies the current clipping path by intersecting it with the current path, using the FillMode rule to determine the region to fill. This method terminates current path. |
| [closePath](../../com.aspose.html.rendering.xps/xpsdevice/closepath/)() | Closes the current subpath by appending a straight line segment from the current point to the starting point of the subpath. If the current subpath is already closed, "ClosePath" does nothing. This operator terminates the current subpath. Appending another segment to the current path begins a new subpath, even if the new segment begins at the endpoint reached by the "ClosePath" method. |
| [cubicBezierTo](../../com.aspose.html.rendering.xps/xpsdevice/cubicbezierto/)(PointF, PointF, PointF) | Appends a cubic Bézier curve to the current path. The curve extends from the current point to the point pt2, using pt1 and pt2 as the Bézier control points. The new current point is pt3. |
| [dispose](../../com.aspose.html.rendering/device-2/dispose/)() |  |
| [drawImage](../../com.aspose.html.rendering.xps/xpsdevice/drawimage/)(byte[], ImageType, RectangleF) | Draws the specified image. |
| [endDocument](../../com.aspose.html.rendering/device-2/enddocument/)() |  |
| [endElement](../../com.aspose.html.rendering.xps/xpsdevice/endelement/)(Element) | Ends rendering of the element. |
| [endPage](../../com.aspose.html.rendering.xps/xpsdevice/endpage/)() | Ends rendering of the current page. |
| [fill](../../com.aspose.html.rendering.xps/xpsdevice/fill/)(FillMode) | Fills the entire region enclosed by the current path. If the path consists of several disconnected subpaths, it fills the insides of all subpaths, considered together. This method terminates current path. |
| [fillText](../../com.aspose.html.rendering.xps/xpsdevice/filltext/)(String, PointF) | Fills the specified text String at the specified location. |
| [flush](../../com.aspose.html.rendering.xps/xpsdevice/flush/)() | Flushes all data to output stream. |
| [lineTo](../../com.aspose.html.rendering.xps/xpsdevice/lineto/)(PointF) | Appends a straight line segment from the current point to the point (pt). The new current point is pt. |
| [moveTo](../../com.aspose.html.rendering.xps/xpsdevice/moveto/)(PointF) | Begins a new subpath by moving the current point to coordinates of the parameter pt, omitting any connecting line segment. If the previous path construction method in the current path was also "MoveTo", the new "MoveTo" overrides it; no vestige of the previous "MoveTo" operation remains in the path. |
| [restoreGraphicContext](../../com.aspose.html.rendering.xps/xpsdevice/restoregraphiccontext/)() | Restores the entire graphics context to its former value by popping it from the stack. |
| [saveGraphicContext](../../com.aspose.html.rendering/device-2/savegraphiccontext/)() |  |
| [stroke](../../com.aspose.html.rendering.xps/xpsdevice/stroke/)() | Strokes a line along the current path. The stroked line follows each straight or curved segment in the path, centered on the segment with sides parallel to it. Each of the path’s subpaths is treated separately. This method terminates current path. |
| [strokeAndFill](../../com.aspose.html.rendering.xps/xpsdevice/strokeandfill/)(FillMode) | Strokes and fill current path. This method terminates current path. |
| [strokeText](../../com.aspose.html.rendering.xps/xpsdevice/stroketext/)(String, PointF) | Strokes the specified text String at the specified location. |

## Other Members

| Name | Description |
| --- | --- |
| class [XpsGraphicContext](../../com.aspose.html.rendering.xps/xpsdevice.xpsgraphiccontext) | Holds current graphics control parameters for the XpsDevice. These parameters define the global framework within which the graphics operators execute. |

### See Also

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [XpsGraphicContext](../xpsdevice.xpsgraphiccontext/)
* class [XpsRenderingOptions](../xpsrenderingoptions/)
* package [com.aspose.html.rendering.xps](../../com.aspose.html.rendering.xps/)
* package [Aspose.HTML](../../)
