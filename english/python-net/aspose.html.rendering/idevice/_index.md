---
title: IDevice class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 70
url: /python-net/aspose.html.rendering/idevice/
is_root: false
---

## IDevice class

Defines methods and properties that support custom rendering of the graphic elements like paths, text and images.



The IDevice type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [options](/html/python-net/aspose.html.rendering/idevice/options) | Gets rendering options. |
| [graphic_context](/html/python-net/aspose.html.rendering/idevice/graphic_context) | Gets the graphic context. |


### Methods
| Method | Description |
| :- | :- |
| [save_graphic_context](/html/python-net/aspose.html.rendering/idevice/save_graphic_context/#) | Pushes a copy of the entire graphics context onto the stack. |
| [restore_graphic_context](/html/python-net/aspose.html.rendering/idevice/restore_graphic_context/#) | Restores the entire graphics context to its former value by popping it from the stack. |
| [begin_document](/html/python-net/aspose.html.rendering/idevice/begin_document/#aspose.html.dom.Document) | Begins rendering of the document. |
| [end_document](/html/python-net/aspose.html.rendering/idevice/end_document/#) | Ends rendering of the document. |
| [begin_page](/html/python-net/aspose.html.rendering/idevice/begin_page/#aspose.pydrawing.SizeF) | Begins rendering of the new page. |
| [end_page](/html/python-net/aspose.html.rendering/idevice/end_page/#) | Ends rendering of the current page. |
| [begin_element](/html/python-net/aspose.html.rendering/idevice/begin_element/#aspose.html.dom.Element-aspose.pydrawing.RectangleF) | Begins rendering of the element. |
| [end_element](/html/python-net/aspose.html.rendering/idevice/end_element/#aspose.html.dom.Element) | Ends rendering of the element. |
| [close_path](/html/python-net/aspose.html.rendering/idevice/close_path/#) | Closes the current subpath by appending a straight line segment from the current point to the starting point of the subpath. <br/>If the current subpath is already closed, "ClosePath" does nothing.<br/>This operator terminates the current subpath. Appending another segment to the current path begins a new subpath, <br/>even if the new segment begins at the endpoint reached by the "ClosePath" method. |
| [move_to](/html/python-net/aspose.html.rendering/idevice/move_to/#aspose.pydrawing.PointF) | Begins a new subpath by moving the current point to coordinates of the parameter pt, omitting any connecting line segment. <br/>If the previous path construction method in the current path was also "MoveTo", the new "MoveTo" overrides it; <br/>no vestige of the previous "MoveTo" operation remains in the path. |
| [line_to](/html/python-net/aspose.html.rendering/idevice/line_to/#aspose.pydrawing.PointF) | Appends a straight line segment from the current point to the point (pt). The new current point is pt. |
| [add_rect](/html/python-net/aspose.html.rendering/idevice/add_rect/#aspose.pydrawing.RectangleF) | Appends a rectangle to the current path as a complete subpath. |
| [cubic_bezier_to](/html/python-net/aspose.html.rendering/idevice/cubic_bezier_to/#aspose.pydrawing.PointF-aspose.pydrawing.PointF-aspose.pydrawing.PointF) | Appends a cubic Bézier curve to the current path. The curve extends from the current point to the point pt3,<br/>using pt1 and pt2 as the Bézier control points. The new current point is pt3. |
| [stroke](/html/python-net/aspose.html.rendering/idevice/stroke/#) | Strokes a line along the current path. The stroked line follows each straight or curved segment in the path, <br/>centered on the segment with sides parallel to it. Each of the path’s subpaths is treated separately. <br/>This method terminates current path. |
| [fill](/html/python-net/aspose.html.rendering/idevice/fill/#aspose.pydrawing.drawing2d.FillMode) | Fills the entire region enclosed by the current path. <br/>If the path consists of several disconnected subpaths, it fills the insides of all subpaths, <br/>considered together. <br/>This method terminates current path. |
| [clip](/html/python-net/aspose.html.rendering/idevice/clip/#aspose.pydrawing.drawing2d.FillMode) | Modifies the current clipping path by intersecting it with the current path, using the FillMode rule to determine the region to fill. <br/>This method terminates current path. |
| [stroke_and_fill](/html/python-net/aspose.html.rendering/idevice/stroke_and_fill/#aspose.pydrawing.drawing2d.FillMode) | Strokes and fill current path.<br/>This method terminates current path. |
| [fill_text](/html/python-net/aspose.html.rendering/idevice/fill_text/#str-aspose.pydrawing.PointF) | Fills the specified text string at the specified location. |
| [stroke_text](/html/python-net/aspose.html.rendering/idevice/stroke_text/#str-aspose.pydrawing.PointF) | Strokes the specified text string at the specified location. |
| [draw_image](/html/python-net/aspose.html.rendering/idevice/draw_image/#bytes-aspose.html.rendering.ImageType-aspose.pydrawing.RectangleF) | Draws the specified image. |
| [flush](/html/python-net/aspose.html.rendering/idevice/flush/#) | Flushes all data to output stream. |



### See Also
* module [`aspose.html.rendering`](..)
