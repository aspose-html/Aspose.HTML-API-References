---
title: DocDevice
second_title: Aspose.HTML for .NET API Reference
description: Represents rendering to a DOCX document.
type: docs
weight: 4250
url: /net/aspose.html.rendering.doc/docdevice/
---
## DocDevice class

Represents rendering to a DOCX document.

```csharp
public class DocDevice : Device<DocGraphicContext, DocRenderingOptions>
```

## Constructors

| Name | Description |
| --- | --- |
| [DocDevice](docdevice#constructor)(ICreateStreamProvider) | Initializes a new instance of the [`DocDevice`](../docdevice) class. |
| [DocDevice](docdevice#constructor_4)(Stream) | Initializes a new instance of the [`DocDevice`](../docdevice) class by output stream. |
| [DocDevice](docdevice#constructor_5)(string) | Initializes a new instance of the [`DocDevice`](../docdevice) class by output file name. |
| [DocDevice](docdevice#constructor_1)(DocRenderingOptions, ICreateStreamProvider) | Initializes a new instance of the [`DocDevice`](../docdevice) class by rendering options and stream provider. |
| [DocDevice](docdevice#constructor_2)(DocRenderingOptions, Stream) | Initializes a new instance of the [`DocDevice`](../docdevice) class by rendering options and output stream. |
| [DocDevice](docdevice#constructor_3)(DocRenderingOptions, string) | Initializes a new instance of the [`DocDevice`](../docdevice) class by rendering options and output file name. |

## Properties

| Name | Description |
| --- | --- |
| [GraphicContext](../../aspose.html.rendering/device`2/graphiccontext) { get; } |  |
| [Options](../../aspose.html.rendering/device`2/options) { get; } |  |

## Methods

| Name | Description |
| --- | --- |
| override [AddRect](../../aspose.html.rendering.doc/docdevice/addrect)(RectangleF) | Appends a rectangle to the current path as a complete subpath. |
| override [BeginDocument](../../aspose.html.rendering.doc/docdevice/begindocument)(Document) | Begins rendering of the document. |
| override [BeginElement](../../aspose.html.rendering.doc/docdevice/beginelement)(Element, RectangleF) | Begins rendering of the html node. |
| override [BeginPage](../../aspose.html.rendering.doc/docdevice/beginpage)(SizeF) | Begins rendering of the new page. |
| override [Clip](../../aspose.html.rendering.doc/docdevice/clip)(FillMode) | Modifies the current clipping path by intersecting it with the current path, using the FillMode rule to determine the region to fill. This method terminates current path. |
| override [ClosePath](../../aspose.html.rendering.doc/docdevice/closepath)() | Closes the current subpath by appending a straight line segment from the current point to the starting point of the subpath. If the current subpath is already closed, "ClosePath" does nothing. This operator terminates the current subpath. Appending another segment to the current path begins a new subpath, even if the new segment begins at the endpoint reached by the "ClosePath" method. |
| override [CubicBezierTo](../../aspose.html.rendering.doc/docdevice/cubicbezierto)(PointF, PointF, PointF) | Appends a cubic Bézier curve to the current path. The curve extends from the current point to the point pt2, using pt1 and pt2 as the Bézier control points. The new current point is pt3. |
| [Dispose](../../aspose.html.rendering/device`2/dispose)() |  |
| override [DrawImage](../../aspose.html.rendering.doc/docdevice/drawimage)(byte[], ImageType, RectangleF) | Draws the specified image. |
| virtual [EndDocument](../../aspose.html.rendering/device`2/enddocument)() |  |
| override [EndElement](../../aspose.html.rendering.doc/docdevice/endelement)(Element) | Ends rendering of the html node. |
| override [EndPage](../../aspose.html.rendering.doc/docdevice/endpage)() | Ends rendering of the current page. |
| override [Fill](../../aspose.html.rendering.doc/docdevice/fill)(FillMode) | Fills the entire region enclosed by the current path. If the path consists of several disconnected subpaths, it fills the insides of all subpaths, considered together. This method terminates current path. |
| override [FillText](../../aspose.html.rendering.doc/docdevice/filltext)(string, PointF) | Fills the specified text string at the specified location. |
| override [Flush](../../aspose.html.rendering.doc/docdevice/flush)() | Flushes all data to output stream. |
| override [LineTo](../../aspose.html.rendering.doc/docdevice/lineto)(PointF) | Appends a straight line segment from the current point to the point (pt). The new current point is pt. |
| override [MoveTo](../../aspose.html.rendering.doc/docdevice/moveto)(PointF) | Begins a new subpath by moving the current point to coordinates of the parameter pt, omitting any connecting line segment. If the previous path construction method in the current path was also "MoveTo", the new "MoveTo" overrides it; no vestige of the previous "MoveTo" operation remains in the path. |
| override [RestoreGraphicContext](../../aspose.html.rendering.doc/docdevice/restoregraphiccontext)() | Restores the entire graphics context to its former value by popping it from the stack. |
| override [SaveGraphicContext](../../aspose.html.rendering.doc/docdevice/savegraphiccontext)() | Pushes a copy of the entire graphics context onto the stack. |
| override [Stroke](../../aspose.html.rendering.doc/docdevice/stroke)() | Strokes a line along the current path. The stroked line follows each straight or curved segment in the path, centered on the segment with sides parallel to it. Each of the path’s subpaths is treated separately. This method terminates current path. |
| override [StrokeAndFill](../../aspose.html.rendering.doc/docdevice/strokeandfill)(FillMode) | Strokes and fill current path. This method terminates current path. |
| override [StrokeText](../../aspose.html.rendering.doc/docdevice/stroketext)(string, PointF) | Strokes the specified text string at the specified location. |

## Other Members

| Name | Description |
| --- | --- |
| class [DocGraphicContext](docdevice.docgraphiccontext) | Holds current graphics control parameters for the DocDevice. These parameters define the global framework within which the graphics operators execute. |

### See Also

* class [Device&lt;TGraphicContext,TRenderingOptions&gt;](../../aspose.html.rendering/device-2)
* class [DocGraphicContext](../docdevice.docgraphiccontext)
* class [DocRenderingOptions](../docrenderingoptions)
* namespace [Aspose.Html.Rendering.Doc](../../aspose.html.rendering.doc)
* assembly [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
