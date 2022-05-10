---
title: ICanvasRenderingContext2D
second_title: Aspose.HTML for .NET API Reference
description: 
type: docs
weight: 370
url: /net/aspose.html.dom.canvas/icanvasrenderingcontext2d/
---
## ICanvasRenderingContext2D interface

The ICanvasRenderingContext2D interface is used for drawing rectangles, text, images and other objects onto the canvas element. It provides the 2D rendering context for the drawing surface of a canvas element.

```csharp
public interface ICanvasRenderingContext2D : ICanvasDrawingStyles, ICanvasPathMethods
```

## Properties

| Name | Description |
| --- | --- |
| [Canvas](canvas) { get; } | A read-only back-reference to the HTMLCanvasElement. Might be null if it is not associated with a canvas element. |
| [FillStyle](fillstyle) { get; set; } | Color or style to use inside shapes. Default: (black). |
| [GlobalAlpha](globalalpha) { get; set; } | Alpha value that is applied to shapes and images before they are composited onto the canvas. Default 1.0 (opaque). |
| [GlobalCompositeOperation](globalcompositeoperation) { get; set; } | With globalAlpha applied this sets how shapes and images are drawn onto the existing bitmap. Default: (source-over) |
| [ImageSmoothingEnabled](imagesmoothingenabled) { get; set; } | Image smoothing mode; if disabled, images will not be smoothed if scaled. |
| [ShadowBlur](shadowblur) { get; set; } | Specifies the blurring effect. Default 0 |
| [ShadowColor](shadowcolor) { get; set; } | Color of the shadow. Default fully-transparent black. |
| [ShadowOffsetX](shadowoffsetx) { get; set; } | Horizontal distance the shadow will be offset. Default 0. |
| [ShadowOffsetY](shadowoffsety) { get; set; } | Vertical distance the shadow will be offset. Default 0. |
| [StrokeStyle](strokestyle) { get; set; } | Color or style to use for the lines around shapes. Default: (black). |

## Methods

| Name | Description |
| --- | --- |
| [AddHitRegion](addhitregion)(Dictionary&lt;string, string&gt;) |  |
| [BeginPath](beginpath)() | Starts a new path by emptying the list of sub-paths. Call this method when you want to create a new path. |
| [ClearHitRegions](clearhitregions)() | Removes all hit regions from the canvas. |
| [ClearRect](clearrect)(double, double, double, double) | Sets all pixels in the rectangle defined by starting point (x, y) and size (width, height) to transparent black, erasing any previously drawn content. |
| [Clip](clip)() | Creates a new clipping region by calculating the intersection of the current clipping region and the area described by the path, using the non-zero winding number rule. Open subpaths must be implicitly closed when computing the clipping region, without affecting the actual subpaths. The new clipping region replaces the current clipping region. |
| [Clip](clip)(CanvasFillRule) | Creates a new clipping region by calculating the intersection of the current clipping region and the area described by the path, using the non-zero winding number rule. Open subpaths must be implicitly closed when computing the clipping region, without affecting the actual subpaths. The new clipping region replaces the current clipping region. |
| [Clip](clip)(Path2D, CanvasFillRule) | Creates a new clipping region by calculating the intersection of the current clipping region and the area described by the path, using the non-zero winding number rule. Open subpaths must be implicitly closed when computing the clipping region, without affecting the actual subpaths. The new clipping region replaces the current clipping region. |
| [CreateImageData](createimagedata)(IImageData) | Creates a new, blank ImageData object with the specified dimensions. All of the pixels in the new object are transparent black. |
| [CreateImageData](createimagedata)(double, double) | Creates a new, blank ImageData object with the specified dimensions. All of the pixels in the new object are transparent black. |
| [CreateLinearGradient](createlineargradient)(double, double, double, double) | Creates a linear gradient along the line given by the coordinates represented by the parameters. |
| [CreatePattern](createpattern)(HTMLCanvasElement, string) | Creates a pattern using the specified image (a CanvasImageSource). It repeats the source in the directions specified by the repetition argument. |
| [CreatePattern](createpattern)(HTMLImageElement, string) | Creates a pattern using the specified image (a CanvasImageSource). It repeats the source in the directions specified by the repetition argument. |
| [CreateRadialGradient](createradialgradient)(double, double, double, double, double, double) | Creates a radial gradient given by the coordinates of the two circles represented by the parameters. |
| [DrawFocusIfNeeded](drawfocusifneeded)(Element) | If a given element is focused, this method draws a focus ring around the current path. |
| [DrawImage](drawimage)(HTMLCanvasElement, double, double) | Draws the specified image. |
| [DrawImage](drawimage)(HTMLImageElement, double, double) | Draws the specified image. |
| [DrawImage](drawimage)(HTMLCanvasElement, double, double, double, double) | Draws the specified image. |
| [DrawImage](drawimage)(HTMLImageElement, double, double, double, double) | Draws the specified image. |
| [DrawImage](drawimage)(HTMLCanvasElement, double, double, double, double, double, double, double, double) | Draws the specified image. |
| [DrawImage](drawimage)(HTMLImageElement, double, double, double, double, double, double, double, double) | Draws the specified image. |
| [Fill](fill)() | Fills the subpaths with the current fill style and default algorithm CanvasFillRule.Nonzero. |
| [Fill](fill)(CanvasFillRule) | Fills the subpaths with the current fill style. |
| [Fill](fill)(Path2D) | Fills the subpaths with the current fill style and default algorithm CanvasFillRule.Nonzero. |
| [Fill](fill)(Path2D, CanvasFillRule) | Fills the subpaths with the current fill style. |
| [FillRect](fillrect)(double, double, double, double) | Draws a filled rectangle at (x, y) position whose size is determined by width and height. |
| [FillText](filltext)(string, double, double) | Draws (fills) a given text at the given (x,y) position. |
| [FillText](filltext)(string, double, double, double) | Draws (fills) a given text at the given (x,y) position. |
| [GetImageData](getimagedata)(double, double, double, double) | Returns an ImageData object representing the underlying pixel data for the area of the canvas denoted by the rectangle which starts at (sx, sy) and has an sw width and sh height. This method is not affected by the canvas transformation matrix. |
| [IsPointInPath](ispointinpath)(double, double) | Reports whether or not the specified point is contained in the current path. |
| [IsPointInPath](ispointinpath)(double, double, CanvasFillRule) | Reports whether or not the specified point is contained in the current path. |
| [IsPointInPath](ispointinpath)(Path2D, double, double) | Reports whether or not the specified point is contained in the current path. |
| [IsPointInPath](ispointinpath)(Path2D, double, double, CanvasFillRule) | Reports whether or not the specified point is contained in the current path. |
| [IsPointInStroke](ispointinstroke)(double, double) | Reports whether or not the specified point is inside the area contained by the stroking of a path. |
| [IsPointInStroke](ispointinstroke)(Path2D, double, double) | Reports whether or not the specified point is inside the area contained by the stroking of a path. |
| [MeasureText](measuretext)(string) | Returns a TextMetrics object. |
| [PutImageData](putimagedata)(IImageData, double, double) | Paints data from the given ImageData object onto the bitmap. If a dirty rectangle is provided, only the pixels from that rectangle are painted. This method is not affected by the canvas transformation matrix. |
| [PutImageData](putimagedata)(IImageData, double, double, double, double, double, double) | Paints data from the given ImageData object onto the bitmap. If a dirty rectangle is provided, only the pixels from that rectangle are painted. This method is not affected by the canvas transformation matrix. |
| [RemoveHitRegion](removehitregion)(string) | Removes the hit region with the specified id from the canvas. |
| [ResetTransform](resettransform)() | Resets the current transform by the identity matrix. |
| [Restore](restore)() | Restores the drawing style state to the last element on the 'state stack' saved by save(). |
| [Rotate](rotate)(double) | Adds a rotation to the transformation matrix. The angle argument represents a clockwise rotation angle and is expressed in radians. |
| [Save](save)() | Saves the current drawing style state using a stack so you can revert any change you make to it using restore(). |
| [Scale](scale)(double, double) | Adds a scaling transformation to the canvas units by x horizontally and by y vertically. |
| [SetTransform](settransform)(double, double, double, double, double, double) | Resets the current transform to the identity matrix, and then invokes the transform() method with the same arguments. |
| [Stroke](stroke)() | Strokes the subpaths with the current stroke style. |
| [Stroke](stroke)(Path2D) | Strokes the subpaths with the current stroke style. |
| [StrokeRect](strokerect)(double, double, double, double) | Paints a rectangle which has a starting point at (x, y) and has a w width and an h height onto the canvas, using the current stroke style. |
| [StrokeText](stroketext)(string, double, double) | Draws (strokes) a given text at the given (x, y) position. |
| [StrokeText](stroketext)(string, double, double, double?) | Draws (strokes) a given text at the given (x, y) position. |
| [Transform](transform)(double, double, double, double, double, double) | Multiplies the current transformation matrix with the matrix described by its arguments. |
| [Translate](translate)(double, double) | Adds a translation transformation by moving the canvas and its origin x horzontally and y vertically on the grid. |

### See Also

* interface [ICanvasDrawingStyles](../icanvasdrawingstyles)
* interface [ICanvasPathMethods](../icanvaspathmethods)
* namespace [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas)
* assembly [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
