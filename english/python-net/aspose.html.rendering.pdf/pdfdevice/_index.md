---
title: PdfDevice class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 10
url: /python-net/aspose.html.rendering.pdf/pdfdevice/
is_root: false
---

## PdfDevice class

Represents rendering to a pdf document.



**Inheritance:** [`PdfDevice`](/html/python-net/aspose.html.rendering.pdf/pdfdevice) → 
[`Device`](/html/python-net/aspose.html.rendering/device)



The PdfDevice type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/html/python-net/aspose.html.rendering.pdf/pdfdevice/__init__/#aspose.html.io.ICreateStreamProvider) | Initializes a new instance of the [`PdfDevice`](/html/python-net/aspose.html.rendering.pdf/pdfdevice) class. |
| [__init__](/html/python-net/aspose.html.rendering.pdf/pdfdevice/__init__/#aspose.html.rendering.pdf.PdfRenderingOptions-aspose.html.io.ICreateStreamProvider) | Initializes a new instance of the [`PdfDevice`](/html/python-net/aspose.html.rendering.pdf/pdfdevice) class by rendering options and stream provider. |
| [__init__](/html/python-net/aspose.html.rendering.pdf/pdfdevice/__init__/#str) | Initializes a new instance of the [`PdfDevice`](/html/python-net/aspose.html.rendering.pdf/pdfdevice) class. |
| [__init__](/html/python-net/aspose.html.rendering.pdf/pdfdevice/__init__/#aspose.html.rendering.pdf.PdfRenderingOptions-str) | Initializes a new instance of the [`PdfDevice`](/html/python-net/aspose.html.rendering.pdf/pdfdevice) class by rendering options and output file name. |
| [__init__](/html/python-net/aspose.html.rendering.pdf/pdfdevice/__init__/#io.RawIOBase) | Initializes a new instance of the [`PdfDevice`](/html/python-net/aspose.html.rendering.pdf/pdfdevice) class. |
| [__init__](/html/python-net/aspose.html.rendering.pdf/pdfdevice/__init__/#aspose.html.rendering.pdf.PdfRenderingOptions-io.RawIOBase) | Initializes a new instance of the [`PdfDevice`](/html/python-net/aspose.html.rendering.pdf/pdfdevice) class by rendering options and output stream. |


### Properties
| Property | Description |
| :- | :- |
| [options](/html/python-net/aspose.html.rendering.pdf/pdfdevice/options) |  |
| [graphic_context](/html/python-net/aspose.html.rendering.pdf/pdfdevice/graphic_context) |  |


### Methods
| Method | Description |
| :- | :- |
| [save_graphic_context](/html/python-net/aspose.html.rendering.pdf/pdfdevice/save_graphic_context/#) | Pushes a copy of the entire graphics context onto the stack. |
| [restore_graphic_context](/html/python-net/aspose.html.rendering.pdf/pdfdevice/restore_graphic_context/#) | Restores the entire graphics context to its former value by popping it from the stack. |
| [add_rect](/html/python-net/aspose.html.rendering.pdf/pdfdevice/add_rect/#aspose.pydrawing.RectangleF) | Appends a rectangle to the current path as a complete subpath. |
| [begin_document](/html/python-net/aspose.html.rendering.pdf/pdfdevice/begin_document/#aspose.html.dom.Document) | Begins rendering of the document. |
| [begin_element](/html/python-net/aspose.html.rendering.pdf/pdfdevice/begin_element/#aspose.html.dom.Element-aspose.pydrawing.RectangleF) | Begins rendering of the element. |
| [begin_page](/html/python-net/aspose.html.rendering.pdf/pdfdevice/begin_page/#aspose.pydrawing.SizeF) | Begins rendering of the new page. |
| [clip](/html/python-net/aspose.html.rendering.pdf/pdfdevice/clip/#aspose.pydrawing.drawing2d.FillMode) | Modifies the current clipping path by intersecting it with the current path, using the FillMode rule to determine the region to fill. <br/>This method terminates current path. |
| [close_path](/html/python-net/aspose.html.rendering.pdf/pdfdevice/close_path/#) | Closes the current subpath by appending a straight line segment from the current point to the starting point of the subpath. <br/>If the current subpath is already closed, "ClosePath" does nothing.<br/>This operator terminates the current subpath. Appending another segment to the current path begins a new subpath, <br/>even if the new segment begins at the endpoint reached by the "ClosePath" method. |
| [cubic_bezier_to](/html/python-net/aspose.html.rendering.pdf/pdfdevice/cubic_bezier_to/#aspose.pydrawing.PointF-aspose.pydrawing.PointF-aspose.pydrawing.PointF) | Appends a cubic Bézier curve to the current path. The curve extends from the current point to the point pt2,<br/>using pt1 and pt2 as the Bézier control points. The new current point is pt3. |
| [draw_image](/html/python-net/aspose.html.rendering.pdf/pdfdevice/draw_image/#bytes-aspose.html.rendering.ImageType-aspose.pydrawing.RectangleF) | Draws the specified image. |
| [end_document](/html/python-net/aspose.html.rendering.pdf/pdfdevice/end_document/#) | Ends rendering of the document. |
| [flush](/html/python-net/aspose.html.rendering.pdf/pdfdevice/flush/#) | Flushes all data to output stream. |
| [end_element](/html/python-net/aspose.html.rendering.pdf/pdfdevice/end_element/#aspose.html.dom.Element) | Ends rendering of the element. |
| [end_page](/html/python-net/aspose.html.rendering.pdf/pdfdevice/end_page/#) | Ends rendering of the current page. |
| [fill](/html/python-net/aspose.html.rendering.pdf/pdfdevice/fill/#aspose.pydrawing.drawing2d.FillMode) | Fills the entire region enclosed by the current path. <br/>If the path consists of several disconnected subpaths, it fills the insides of all subpaths, <br/>considered together. <br/>This method terminates current path. |
| [fill_text](/html/python-net/aspose.html.rendering.pdf/pdfdevice/fill_text/#str-aspose.pydrawing.PointF) | Fills the specified text string at the specified location. |
| [line_to](/html/python-net/aspose.html.rendering.pdf/pdfdevice/line_to/#aspose.pydrawing.PointF) | Appends a straight line segment from the current point to the point (pt). The new current point is pt. |
| [move_to](/html/python-net/aspose.html.rendering.pdf/pdfdevice/move_to/#aspose.pydrawing.PointF) | Begins a new subpath by moving the current point to coordinates of the parameter pt, omitting any connecting line segment. <br/>If the previous path construction method in the current path was also "MoveTo", the new "MoveTo" overrides it; <br/>no vestige of the previous "MoveTo" operation remains in the path. |
| [stroke](/html/python-net/aspose.html.rendering.pdf/pdfdevice/stroke/#) | Strokes a line along the current path. The stroked line follows each straight or curved segment in the path, <br/>centered on the segment with sides parallel to it. Each of the path’s subpaths is treated separately. <br/>This method terminates current path. |
| [stroke_and_fill](/html/python-net/aspose.html.rendering.pdf/pdfdevice/stroke_and_fill/#aspose.pydrawing.drawing2d.FillMode) | Strokes and fill current path.<br/>This method terminates current path. |
| [stroke_text](/html/python-net/aspose.html.rendering.pdf/pdfdevice/stroke_text/#str-aspose.pydrawing.PointF) | Strokes the specified text string at the specified location. |



### See Also
* module [`aspose.html.rendering.pdf`](..)
* class [`Device`](/html/python-net/aspose.html.rendering/device)
* class [`PdfDevice`](/html/python-net/aspose.html.rendering.pdf/pdfdevice)
