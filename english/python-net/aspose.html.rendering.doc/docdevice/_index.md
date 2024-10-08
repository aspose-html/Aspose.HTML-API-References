﻿---
title: DocDevice class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 10
url: /python-net/aspose.html.rendering.doc/docdevice/
is_root: false
---

## DocDevice class

Represents rendering to a DOCX document.



**Inheritance:** [`DocDevice`](/html/python-net/aspose.html.rendering.doc/docdevice) → 
[`Device`](/html/python-net/aspose.html.rendering/device)



The DocDevice type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/html/python-net/aspose.html.rendering.doc/docdevice/__init__/#aspose.html.io.ICreateStreamProvider) | Initializes a new instance of the [`DocDevice`](/html/python-net/aspose.html.rendering.doc/docdevice) class. |
| [__init__](/html/python-net/aspose.html.rendering.doc/docdevice/__init__/#aspose.html.rendering.doc.DocRenderingOptions-aspose.html.io.ICreateStreamProvider) | Initializes a new instance of the [`DocDevice`](/html/python-net/aspose.html.rendering.doc/docdevice) class by rendering options and stream provider. |
| [__init__](/html/python-net/aspose.html.rendering.doc/docdevice/__init__/#str) | Initializes a new instance of the [`DocDevice`](/html/python-net/aspose.html.rendering.doc/docdevice) class by output file name. |
| [__init__](/html/python-net/aspose.html.rendering.doc/docdevice/__init__/#aspose.html.rendering.doc.DocRenderingOptions-str) | Initializes a new instance of the [`DocDevice`](/html/python-net/aspose.html.rendering.doc/docdevice) class by rendering options and output file name. |
| [__init__](/html/python-net/aspose.html.rendering.doc/docdevice/__init__/#io.RawIOBase) | Initializes a new instance of the [`DocDevice`](/html/python-net/aspose.html.rendering.doc/docdevice) class by output stream. |
| [__init__](/html/python-net/aspose.html.rendering.doc/docdevice/__init__/#aspose.html.rendering.doc.DocRenderingOptions-io.RawIOBase) | Initializes a new instance of the [`DocDevice`](/html/python-net/aspose.html.rendering.doc/docdevice) class by rendering options and output stream. |


### Properties
| Property | Description |
| :- | :- |
| [options](/html/python-net/aspose.html.rendering.doc/docdevice/options) |  |
| [graphic_context](/html/python-net/aspose.html.rendering.doc/docdevice/graphic_context) |  |


### Methods
| Method | Description |
| :- | :- |
| [begin_document](/html/python-net/aspose.html.rendering.doc/docdevice/begin_document/#aspose.html.dom.Document) | Begins rendering of the document. |
| [begin_page](/html/python-net/aspose.html.rendering.doc/docdevice/begin_page/#aspose.pydrawing.SizeF) | Begins rendering of the new page. |
| [end_page](/html/python-net/aspose.html.rendering.doc/docdevice/end_page/#) | Ends rendering of the current page. |
| [flush](/html/python-net/aspose.html.rendering.doc/docdevice/flush/#) | Flushes all data to output stream. |
| [begin_element](/html/python-net/aspose.html.rendering.doc/docdevice/begin_element/#aspose.html.dom.Element-aspose.pydrawing.RectangleF) | Begins rendering of the html node. |
| [end_element](/html/python-net/aspose.html.rendering.doc/docdevice/end_element/#aspose.html.dom.Element) | Ends rendering of the html node. |
| [add_rect](/html/python-net/aspose.html.rendering.doc/docdevice/add_rect/#aspose.pydrawing.RectangleF) | Appends a rectangle to the current path as a complete subpath. |
| [clip](/html/python-net/aspose.html.rendering.doc/docdevice/clip/#aspose.html.rendering.FillRule) | Modifies the current clipping path by intersecting it with the current path, using the FillMode rule to determine the region to fill. <br/>This method terminates current path. |
| [line_to](/html/python-net/aspose.html.rendering.doc/docdevice/line_to/#aspose.pydrawing.PointF) | Appends a straight line segment from the current point to the point (pt). The new current point is pt. |
| [move_to](/html/python-net/aspose.html.rendering.doc/docdevice/move_to/#aspose.pydrawing.PointF) | Begins a new subpath by moving the current point to coordinates of the parameter pt, omitting any connecting line segment. <br/>If the previous path construction method in the current path was also "MoveTo", the new "MoveTo" overrides it; <br/>no vestige of the previous "MoveTo" operation remains in the path. |
| [close_path](/html/python-net/aspose.html.rendering.doc/docdevice/close_path/#) | Closes the current subpath by appending a straight line segment from the current point to the starting point of the subpath. <br/>If the current subpath is already closed, "ClosePath" does nothing.<br/>This operator terminates the current subpath. Appending another segment to the current path begins a new subpath, <br/>even if the new segment begins at the endpoint reached by the "ClosePath" method. |
| [cubic_bezier_to](/html/python-net/aspose.html.rendering.doc/docdevice/cubic_bezier_to/#aspose.pydrawing.PointF-aspose.pydrawing.PointF-aspose.pydrawing.PointF) | Appends a cubic Bézier curve to the current path. The curve extends from the current point to the point pt2,<br/>using pt1 and pt2 as the Bézier control points. The new current point is pt3. |
| [stroke](/html/python-net/aspose.html.rendering.doc/docdevice/stroke/#) | Strokes a line along the current path. The stroked line follows each straight or curved segment in the path, <br/>centered on the segment with sides parallel to it. Each of the path’s subpaths is treated separately. <br/>This method terminates current path. |
| [stroke_and_fill](/html/python-net/aspose.html.rendering.doc/docdevice/stroke_and_fill/#aspose.html.rendering.FillRule) | Strokes and fill current path.<br/>This method terminates current path. |
| [fill](/html/python-net/aspose.html.rendering.doc/docdevice/fill/#aspose.html.rendering.FillRule) | Fills the entire region enclosed by the current path. <br/>If the path consists of several disconnected subpaths, it fills the insides of all subpaths, <br/>considered together. <br/>This method terminates current path. |
| [fill_text](/html/python-net/aspose.html.rendering.doc/docdevice/fill_text/#str-aspose.pydrawing.PointF) | Fills the specified text string at the specified location. |
| [stroke_text](/html/python-net/aspose.html.rendering.doc/docdevice/stroke_text/#str-aspose.pydrawing.PointF) | Strokes the specified text string at the specified location. |
| [draw_image](/html/python-net/aspose.html.rendering.doc/docdevice/draw_image/#bytes-aspose.html.drawing.WebImageFormat-aspose.pydrawing.RectangleF) | Draws the specified image. |
| [save_graphic_context](/html/python-net/aspose.html.rendering.doc/docdevice/save_graphic_context/#) |  |
| [restore_graphic_context](/html/python-net/aspose.html.rendering.doc/docdevice/restore_graphic_context/#) |  |
| [end_document](/html/python-net/aspose.html.rendering.doc/docdevice/end_document/#) |  |



### See Also
* module [`aspose.html.rendering.doc`](..)
* class [`Device`](/html/python-net/aspose.html.rendering/device)
* class [`DocDevice`](/html/python-net/aspose.html.rendering.doc/docdevice)
