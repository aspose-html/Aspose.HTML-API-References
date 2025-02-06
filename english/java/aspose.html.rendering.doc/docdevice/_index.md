---
title: DocDevice Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.rendering.doc.DocDevice class. Represents rendering to a DOCX document
type: docs
weight: 4200
url: /java/com.aspose.html.rendering.doc/docdevice/
---
## DocDevice class

Represents rendering to a DOCX document.

```java
public class DocDevice : Device<DocGraphicContext, DocRenderingOptions>
```

## Constructors

| Name | Description |
| --- | --- |
| [DocDevice](docdevice/#constructor)(ICreateStreamProvider) | Initializes a new instance of the `DocDevice` class. |
| [DocDevice](docdevice/#constructor_4)(Stream) | Initializes a new instance of the `DocDevice` class by output stream. |
| [DocDevice](docdevice/#constructor_5)(String) | Initializes a new instance of the `DocDevice` class by output file name. |
| [DocDevice](docdevice/#constructor_1)(DocRenderingOptions, ICreateStreamProvider) | Initializes a new instance of the `DocDevice` class by rendering options and stream provider. |
| [DocDevice](docdevice/#constructor_2)(DocRenderingOptions, Stream) | Initializes a new instance of the `DocDevice` class by rendering options and output stream. |
| [DocDevice](docdevice/#constructor_3)(DocRenderingOptions, String) | Initializes a new instance of the `DocDevice` class by rendering options and output file name. |

## Properties

| Name | Description |
| --- | --- |
| [getGraphicContext](../../com.aspose.html.rendering/device-2/graphiccontext/)  |
| [getOptions](../../com.aspose.html.rendering/device-2/options/)  |

## Methods

| Name | Description |
| --- | --- |
| [addRect](../../com.aspose.html.rendering.doc/docdevice/addrect/)(RectangleF) | Appends a rectangle to the current path as a complete subpath. |
| [beginDocument](../../com.aspose.html.rendering.doc/docdevice/begindocument/)(Document) | Begins rendering of the document. |
| [beginElement](../../com.aspose.html.rendering.doc/docdevice/beginelement/)(Element, RectangleF) | Begins rendering of the html node. |
| [beginPage](../../com.aspose.html.rendering.doc/docdevice/beginpage/)(SizeF) | Begins rendering of the new page. |
| [clip](../../com.aspose.html.rendering.doc/docdevice/clip/)(FillMode) | Modifies the current clipping path by intersecting it with the current path, using the FillMode rule to determine the region to fill. This method terminates current path. |
| [closePath](../../com.aspose.html.rendering.doc/docdevice/closepath/)() | Closes the current subpath by appending a straight line segment from the current point to the starting point of the subpath. If the current subpath is already closed, "ClosePath" does nothing. This operator terminates the current subpath. Appending another segment to the current path begins a new subpath, even if the new segment begins at the endpoint reached by the "ClosePath" method. |
| [cubicBezierTo](../../com.aspose.html.rendering.doc/docdevice/cubicbezierto/)(PointF, PointF, PointF) | Appends a cubic Bézier curve to the current path. The curve extends from the current point to the point pt2, using pt1 and pt2 as the Bézier control points. The new current point is pt3. |
| [dispose](../../com.aspose.html.rendering/device-2/dispose/)() |  |
| [drawImage](../../com.aspose.html.rendering.doc/docdevice/drawimage/)(byte[], ImageType, RectangleF) | Draws the specified image. |
| [endDocument](../../com.aspose.html.rendering/device-2/enddocument/)() |  |
| [endElement](../../com.aspose.html.rendering.doc/docdevice/endelement/)(Element) | Ends rendering of the html node. |
| [endPage](../../com.aspose.html.rendering.doc/docdevice/endpage/)() | Ends rendering of the current page. |
| [fill](../../com.aspose.html.rendering.doc/docdevice/fill/)(FillMode) | Fills the entire region enclosed by the current path. If the path consists of several disconnected subpaths, it fills the insides of all subpaths, considered together. This method terminates current path. |
| [fillText](../../com.aspose.html.rendering.doc/docdevice/filltext/)(String, PointF) | Fills the specified text String at the specified location. |
| [flush](../../com.aspose.html.rendering.doc/docdevice/flush/)() | Flushes all data to output stream. |
| [lineTo](../../com.aspose.html.rendering.doc/docdevice/lineto/)(PointF) | Appends a straight line segment from the current point to the point (pt). The new current point is pt. |
| [moveTo](../../com.aspose.html.rendering.doc/docdevice/moveto/)(PointF) | Begins a new subpath by moving the current point to coordinates of the parameter pt, omitting any connecting line segment. If the previous path construction method in the current path was also "MoveTo", the new "MoveTo" overrides it; no vestige of the previous "MoveTo" operation remains in the path. |
| [restoreGraphicContext](../../com.aspose.html.rendering.doc/docdevice/restoregraphiccontext/)() | Restores the entire graphics context to its former value by popping it from the stack. |
| [saveGraphicContext](../../com.aspose.html.rendering.doc/docdevice/savegraphiccontext/)() | Pushes a copy of the entire graphics context onto the stack. |
| [stroke](../../com.aspose.html.rendering.doc/docdevice/stroke/)() | Strokes a line along the current path. The stroked line follows each straight or curved segment in the path, centered on the segment with sides parallel to it. Each of the path’s subpaths is treated separately. This method terminates current path. |
| [strokeAndFill](../../com.aspose.html.rendering.doc/docdevice/strokeandfill/)(FillMode) | Strokes and fill current path. This method terminates current path. |
| [strokeText](../../com.aspose.html.rendering.doc/docdevice/stroketext/)(String, PointF) | Strokes the specified text String at the specified location. |

## Other Members

| Name | Description |
| --- | --- |
| class [DocGraphicContext](../../com.aspose.html.rendering.doc/docdevice.docgraphiccontext) | Holds current graphics control parameters for the DocDevice. These parameters define the global framework within which the graphics operators execute. |

### See Also

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../com.aspose.html.rendering/device-2/)
* class [DocGraphicContext](../docdevice.docgraphiccontext/)
* class [DocRenderingOptions](../docrenderingoptions/)
* package [com.aspose.html.rendering.doc](../../com.aspose.html.rendering.doc/)
* package [Aspose.HTML](../../)
