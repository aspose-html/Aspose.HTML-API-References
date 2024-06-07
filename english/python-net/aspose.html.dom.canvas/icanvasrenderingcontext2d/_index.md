---
title: ICanvasRenderingContext2D class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 50
url: /aspose.html.dom.canvas/icanvasrenderingcontext2d/
is_root: false
---

## ICanvasRenderingContext2D class

The ICanvasRenderingContext2D interface is used for drawing rectangles, text, images and other objects onto the canvas element. It provides the 2D rendering context for the drawing surface of a canvas element.



The ICanvasRenderingContext2D type exposes the following members:

### Properties
| Property | Description |
| :- | :- |
| [canvas](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/canvas) | A read-only back-reference to the HTMLCanvasElement. Might be null if it is not associated with a canvas element. |
| [global_alpha](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/global_alpha) | Alpha value that is applied to shapes and images before they are composited onto the canvas. Default 1.0 (opaque). |
| [global_composite_operation](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/global_composite_operation) | With globalAlpha applied this sets how shapes and images are drawn onto the existing bitmap. Default: (source-over) |
| [stroke_style](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke_style) | Color or style to use for the lines around shapes. Default: (black). |
| [fill_style](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/fill_style) | Color or style to use inside shapes. Default: (black). |
| [image_smoothing_enabled](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/image_smoothing_enabled) | Image smoothing mode; if disabled, images will not be smoothed if scaled. |
| [shadow_offset_x](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/shadow_offset_x) | Horizontal distance the shadow will be offset. Default 0. |
| [shadow_offset_y](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/shadow_offset_y) | Vertical distance the shadow will be offset. Default 0. |
| [shadow_blur](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/shadow_blur) | Specifies the blurring effect. Default 0 |
| [shadow_color](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/shadow_color) | Color of the shadow. Default fully-transparent black. |
| [line_width](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/line_width) | Width of lines. Default 1.0 |
| [line_cap](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/line_cap) | Type of endings on the end of lines. Possible values: butt (default), round, square. |
| [line_join](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/line_join) | Defines the type of corners where two lines meet. Possible values: round, bevel, miter (default). |
| [miter_limit](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/miter_limit) | Miter limit ratio. Default 10. |
| [line_dash_offset](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/line_dash_offset) | Specifies where to start a dash array on a line. |
| [font](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/font) | Font setting. Default value 10px sans-serif |
| [text_align](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/text_align) | Text alignment setting. Possible values: start (default), end, left, right or center. |
| [text_baseline](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/text_baseline) | Baseline alignment setting. Possible values: top, hanging, middle, alphabetic (default), ideographic, bottom. |


### Methods
| Method | Description |
| :- | :- |
| [create_pattern](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/create_pattern/#aspose.html.HTMLImageElement-str) | Creates a pattern using the specified image (a CanvasImageSource). <br/>It repeats the source in the directions specified by the repetition argument. |
| [create_pattern](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/create_pattern/#aspose.html.HTMLCanvasElement-str) | Creates a pattern using the specified image (a CanvasImageSource). <br/>It repeats the source in the directions specified by the repetition argument. |
| [fill](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#) | Fills the subpaths with the current fill style and default algorithm CanvasFillRule.Nonzero. |
| [fill](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#aspose.html.dom.canvas.CanvasFillRule) | Fills the subpaths with the current fill style. |
| [fill](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#aspose.html.dom.canvas.Path2D) | Fills the subpaths with the current fill style and default algorithm CanvasFillRule.Nonzero. |
| [fill](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#aspose.html.dom.canvas.Path2D-aspose.html.dom.canvas.CanvasFillRule) | Fills the subpaths with the current fill style. |
| [stroke](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#) | Strokes the subpaths with the current stroke style. |
| [stroke](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#aspose.html.dom.canvas.Path2D) | Strokes the subpaths with the current stroke style. |
| [clip](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#) | Creates a new clipping region by calculating the intersection of the current clipping region and the area described by the path, using the non-zero winding number rule.<br/>Open subpaths must be implicitly closed when computing the clipping region, without affecting the actual subpaths.<br/>The new clipping region replaces the current clipping region. |
| [clip](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#aspose.html.dom.canvas.CanvasFillRule) | Creates a new clipping region by calculating the intersection of the current clipping region and the area described by the path, using the non-zero winding number rule. <br/>Open subpaths must be implicitly closed when computing the clipping region, without affecting the actual subpaths.<br/>The new clipping region replaces the current clipping region. |
| [clip](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#aspose.html.dom.canvas.Path2D-aspose.html.dom.canvas.CanvasFillRule) | Creates a new clipping region by calculating the intersection of the current clipping region and the area described by the path, using the non-zero winding number rule. <br/>Open subpaths must be implicitly closed when computing the clipping region, without affecting the actual subpaths.<br/>The new clipping region replaces the current clipping region. |
| [is_point_in_path](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/is_point_in_path/#float-float) | Reports whether or not the specified point is contained in the current path. |
| [is_point_in_path](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/is_point_in_path/#float-float-aspose.html.dom.canvas.CanvasFillRule) | Reports whether or not the specified point is contained in the current path. |
| [is_point_in_path](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/is_point_in_path/#aspose.html.dom.canvas.Path2D-float-float) | Reports whether or not the specified point is contained in the current path. |
| [is_point_in_path](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/is_point_in_path/#aspose.html.dom.canvas.Path2D-float-float-aspose.html.dom.canvas.CanvasFillRule) | Reports whether or not the specified point is contained in the current path. |
| [is_point_in_stroke](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/is_point_in_stroke/#float-float) | Reports whether or not the specified point is inside the area contained by the stroking of a path. |
| [is_point_in_stroke](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/is_point_in_stroke/#aspose.html.dom.canvas.Path2D-float-float) | Reports whether or not the specified point is inside the area contained by the stroking of a path. |
| [fill_text](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/fill_text/#str-float-float) | Draws (fills) a given text at the given (x,y) position. |
| [fill_text](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/fill_text/#str-float-float-float) | Draws (fills) a given text at the given (x,y) position. |
| [stroke_text](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke_text/#str-float-float) | Draws (strokes) a given text at the given (x, y) position. |
| [stroke_text](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke_text/#str-float-float-Nullable<double>) |  |
| [draw_image](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/draw_image/#aspose.html.HTMLImageElement-float-float) | Draws the specified image. |
| [draw_image](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/draw_image/#aspose.html.HTMLCanvasElement-float-float) | Draws the specified image. |
| [draw_image](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/draw_image/#aspose.html.HTMLImageElement-float-float-float-float) | Draws the specified image. |
| [draw_image](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/draw_image/#aspose.html.HTMLCanvasElement-float-float-float-float) | Draws the specified image. |
| [draw_image](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/draw_image/#aspose.html.HTMLImageElement-float-float-float-float-float-float-float-float) | Draws the specified image. |
| [draw_image](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/draw_image/#aspose.html.HTMLCanvasElement-float-float-float-float-float-float-float-float) | Draws the specified image. |
| [create_image_data](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/create_image_data/#float-float) | Creates a new, blank ImageData object with the specified dimensions. <br/>All of the pixels in the new object are transparent black. |
| [create_image_data](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/create_image_data/#aspose.html.dom.canvas.IImageData) | Creates a new, blank ImageData object with the specified dimensions. <br/>All of the pixels in the new object are transparent black. |
| [put_image_data](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/put_image_data/#aspose.html.dom.canvas.IImageData-float-float) | Paints data from the given ImageData object onto the bitmap. <br/>If a dirty rectangle is provided, only the pixels from that rectangle are painted. <br/>This method is not affected by the canvas transformation matrix. |
| [put_image_data](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/put_image_data/#aspose.html.dom.canvas.IImageData-float-float-float-float-float-float) | Paints data from the given ImageData object onto the bitmap. <br/>If a dirty rectangle is provided, only the pixels from that rectangle are painted. <br/>This method is not affected by the canvas transformation matrix. |
| [arc](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/arc/#float-float-float-float-float) |  |
| [arc](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/arc/#float-float-float-float-float-bool) |  |
| [ellipse](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/ellipse/#float-float-float-float-float-float-float) |  |
| [ellipse](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/ellipse/#float-float-float-float-float-float-float-bool) |  |
| [save](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/save/#) | Saves the current drawing style state using a stack so you can revert any change you make to it using restore(). |
| [restore](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/restore/#) | Restores the drawing style state to the last element on the 'state stack' saved by save(). |
| [scale](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/scale/#float-float) | Adds a scaling transformation to the canvas units by x horizontally and by y vertically. |
| [rotate](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/rotate/#float) | Adds a rotation to the transformation matrix. The angle argument represents a clockwise rotation angle and is expressed in radians. |
| [translate](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/translate/#float-float) | Adds a translation transformation by moving the canvas and its origin x horzontally and y vertically on the grid. |
| [transform](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/transform/#float-float-float-float-float-float) | Multiplies the current transformation matrix with the matrix described by its arguments. |
| [set_transform](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/set_transform/#float-float-float-float-float-float) | Resets the current transform to the identity matrix, and then invokes the transform() method with the same arguments. |
| [reset_transform](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/reset_transform/#) | Resets the current transform by the identity matrix. |
| [create_linear_gradient](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/create_linear_gradient/#float-float-float-float) | Creates a linear gradient along the line given by the coordinates represented by the parameters. |
| [create_radial_gradient](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/create_radial_gradient/#float-float-float-float-float-float) | Creates a radial gradient given by the coordinates of the two circles represented by the parameters. |
| [clear_rect](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/clear_rect/#float-float-float-float) | Sets all pixels in the rectangle defined by starting point (x, y) and size (width, height) to transparent black, erasing any previously drawn content. |
| [fill_rect](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/fill_rect/#float-float-float-float) | Draws a filled rectangle at (x, y) position whose size is determined by width and height. |
| [stroke_rect](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke_rect/#float-float-float-float) | Paints a rectangle which has a starting point at (x, y) and has a w width and an h height onto the canvas, using the current stroke style. |
| [begin_path](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/begin_path/#) | Starts a new path by emptying the list of sub-paths. Call this method when you want to create a new path. |
| [draw_focus_if_needed](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/draw_focus_if_needed/#aspose.html.dom.Element) | If a given element is focused, this method draws a focus ring around the current path. |
| [measure_text](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/measure_text/#str) | Returns a TextMetrics object. |
| [remove_hit_region](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/remove_hit_region/#str) | Removes the hit region with the specified id from the canvas. |
| [clear_hit_regions](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/clear_hit_regions/#) | Removes all hit regions from the canvas. |
| [get_image_data](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/get_image_data/#float-float-float-float) | Returns an ImageData object representing the underlying pixel data for the area of the canvas denoted by the rectangle which starts at (sx, sy) and has an sw width and sh height.<br/>This method is not affected by the canvas transformation matrix. |
| [set_line_dash](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/set_line_dash/#list) | Sets the current line dash pattern. |
| [get_line_dash](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/get_line_dash/#) | Returns the current line dash pattern array containing an even number of non-negative numbers. |
| [close_path](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/close_path/#) |  |
| [move_to](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/move_to/#float-float) |  |
| [line_to](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/line_to/#float-float) |  |
| [quadratic_curve_to](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/quadratic_curve_to/#float-float-float-float) |  |
| [bezier_curve_to](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/bezier_curve_to/#float-float-float-float-float-float) |  |
| [arc_to](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/arc_to/#float-float-float-float-float) |  |
| [rect](/html/python-net/aspose.html.dom.canvas/icanvasrenderingcontext2d/rect/#float-float-float-float) |  |



### See Also
* module [`aspose.html.dom.canvas`](..)
* class [`ICanvasDrawingStyles`](/html/python-net/aspose.html.dom.canvas/icanvasdrawingstyles)
