---
title: XpsDevice class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 10
url: /python-net/aspose.html.rendering.xps/xpsdevice/
is_root: false
---

## XpsDevice class

Represents rendering to a xps document.



**Inheritance:** [`XpsDevice`](/html/python-net/aspose.html.rendering.xps/xpsdevice) → 
[`Device`](/html/python-net/aspose.html.rendering/device)



The XpsDevice type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/html/python-net/aspose.html.rendering.xps/xpsdevice/__init__/#aspose.html.io.ICreateStreamProvider) | Initializes a new instance of the [`XpsDevice`](/html/python-net/aspose.html.rendering.xps/xpsdevice) class. |
| [__init__](/html/python-net/aspose.html.rendering.xps/xpsdevice/__init__/#aspose.html.rendering.xps.XpsRenderingOptions-aspose.html.io.ICreateStreamProvider) | Initializes a new instance of the [`XpsDevice`](/html/python-net/aspose.html.rendering.xps/xpsdevice) class by rendering options and stream provider. |
| [__init__](/html/python-net/aspose.html.rendering.xps/xpsdevice/__init__/#str) | Initializes a new instance of the [`XpsDevice`](/html/python-net/aspose.html.rendering.xps/xpsdevice) class. |
| [__init__](/html/python-net/aspose.html.rendering.xps/xpsdevice/__init__/#aspose.html.rendering.xps.XpsRenderingOptions-str) | Initializes a new instance of the [`XpsDevice`](/html/python-net/aspose.html.rendering.xps/xpsdevice) class by rendering options and output file name. |
| [__init__](/html/python-net/aspose.html.rendering.xps/xpsdevice/__init__/#io.RawIOBase) | Initializes a new instance of the [`XpsDevice`](/html/python-net/aspose.html.rendering.xps/xpsdevice) class. |
| [__init__](/html/python-net/aspose.html.rendering.xps/xpsdevice/__init__/#aspose.html.rendering.xps.XpsRenderingOptions-io.RawIOBase) | Initializes a new instance of the [`XpsDevice`](/html/python-net/aspose.html.rendering.xps/xpsdevice) class by rendering options and output stream. |


### Properties
| Property | Description |
| :- | :- |
| [options](/html/python-net/aspose.html.rendering.xps/xpsdevice/options) |  |
| [graphic_context](/html/python-net/aspose.html.rendering.xps/xpsdevice/graphic_context) |  |


### Methods
| Method | Description |
| :- | :- |
| [restore_graphic_context](/html/python-net/aspose.html.rendering.xps/xpsdevice/restore_graphic_context/#) | Restores the entire graphics context to its former value by popping it from the stack. |
| [line_to](/html/python-net/aspose.html.rendering.xps/xpsdevice/line_to/#aspose.pydrawing.PointF) | Appends a straight line segment from the current point to the point (pt). The new current point is pt. |
| [move_to](/html/python-net/aspose.html.rendering.xps/xpsdevice/move_to/#aspose.pydrawing.PointF) | Begins a new subpath by moving the current point to coordinates of the parameter pt, omitting any connecting line segment. <br/>If the previous path construction method in the current path was also "MoveTo", the new "MoveTo" overrides it; <br/>no vestige of the previous "MoveTo" operation remains in the path. |
| [cubic_bezier_to](/html/python-net/aspose.html.rendering.xps/xpsdevice/cubic_bezier_to/#aspose.pydrawing.PointF-aspose.pydrawing.PointF-aspose.pydrawing.PointF) | Appends a cubic Bézier curve to the current path. The curve extends from the current point to the point pt2,<br/>using pt1 and pt2 as the Bézier control points. The new current point is pt3. |
| [add_rect](/html/python-net/aspose.html.rendering.xps/xpsdevice/add_rect/#aspose.pydrawing.RectangleF) | Appends a rectangle to the current path as a complete subpath. |
| [close_path](/html/python-net/aspose.html.rendering.xps/xpsdevice/close_path/#) | Closes the current subpath by appending a straight line segment from the current point to the starting point of the subpath. <br/>If the current subpath is already closed, "ClosePath" does nothing.<br/>This operator terminates the current subpath. Appending another segment to the current path begins a new subpath, <br/>even if the new segment begins at the endpoint reached by the "ClosePath" method. |
| [clip](/html/python-net/aspose.html.rendering.xps/xpsdevice/clip/#aspose.pydrawing.drawing2d.FillMode) | Modifies the current clipping path by intersecting it with the current path, using the FillMode rule to determine the region to fill. <br/>This method terminates current path. |
| [fill](/html/python-net/aspose.html.rendering.xps/xpsdevice/fill/#aspose.pydrawing.drawing2d.FillMode) | Fills the entire region enclosed by the current path. <br/>If the path consists of several disconnected subpaths, it fills the insides of all subpaths, <br/>considered together. <br/>This method terminates current path. |
| [stroke_and_fill](/html/python-net/aspose.html.rendering.xps/xpsdevice/stroke_and_fill/#aspose.pydrawing.drawing2d.FillMode) | Strokes and fill current path.<br/>This method terminates current path. |
| [stroke](/html/python-net/aspose.html.rendering.xps/xpsdevice/stroke/#) | Strokes a line along the current path. The stroked line follows each straight or curved segment in the path, <br/>centered on the segment with sides parallel to it. Each of the path’s subpaths is treated separately. <br/>This method terminates current path. |
| [fill_text](/html/python-net/aspose.html.rendering.xps/xpsdevice/fill_text/#str-aspose.pydrawing.PointF) | Fills the specified text string at the specified location. |
| [stroke_text](/html/python-net/aspose.html.rendering.xps/xpsdevice/stroke_text/#str-aspose.pydrawing.PointF) | Strokes the specified text string at the specified location. |
| [begin_document](/html/python-net/aspose.html.rendering.xps/xpsdevice/begin_document/#aspose.html.dom.Document) | Begins rendering of the document. |
| [begin_element](/html/python-net/aspose.html.rendering.xps/xpsdevice/begin_element/#aspose.html.dom.Element-aspose.pydrawing.RectangleF) | Begins rendering of the element. |
| [begin_page](/html/python-net/aspose.html.rendering.xps/xpsdevice/begin_page/#aspose.pydrawing.SizeF) | Begins rendering of the new page. |
| [end_page](/html/python-net/aspose.html.rendering.xps/xpsdevice/end_page/#) | Ends rendering of the current page. |
| [flush](/html/python-net/aspose.html.rendering.xps/xpsdevice/flush/#) | Flushes all data to output stream. |
| [end_element](/html/python-net/aspose.html.rendering.xps/xpsdevice/end_element/#aspose.html.dom.Element) | Ends rendering of the element. |
| [draw_image](/html/python-net/aspose.html.rendering.xps/xpsdevice/draw_image/#bytes-aspose.html.rendering.ImageType-aspose.pydrawing.RectangleF) | Draws the specified image. |
| [save_graphic_context](/html/python-net/aspose.html.rendering.xps/xpsdevice/save_graphic_context/#) |  |
| [end_document](/html/python-net/aspose.html.rendering.xps/xpsdevice/end_document/#) |  |



### See Also
* module [`aspose.html.rendering.xps`](..)
* class [`Device`](/html/python-net/aspose.html.rendering/device)
* class [`XpsDevice`](/html/python-net/aspose.html.rendering.xps/xpsdevice)
