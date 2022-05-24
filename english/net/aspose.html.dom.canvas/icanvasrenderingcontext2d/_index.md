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
| [Canvas](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/canvas) { get; } | A read-only back-reference to the HTMLCanvasElement. Might be null if it is not associated with a canvas element. |
| [FillStyle](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fillstyle) { get; set; } | Color or style to use inside shapes. Default: (black). |
| [GlobalAlpha](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/globalalpha) { get; set; } | Alpha value that is applied to shapes and images before they are composited onto the canvas. Default 1.0 (opaque). |
| [GlobalCompositeOperation](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/globalcompositeoperation) { get; set; } | With globalAlpha applied this sets how shapes and images are drawn onto the existing bitmap. Default: (source-over) |
| [ImageSmoothingEnabled](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/imagesmoothingenabled) { get; set; } | Image smoothing mode; if disabled, images will not be smoothed if scaled. |
| [ShadowBlur](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowblur) { get; set; } | Specifies the blurring effect. Default 0 |
| [ShadowColor](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowcolor) { get; set; } | Color of the shadow. Default fully-transparent black. |
| [ShadowOffsetX](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowoffsetx) { get; set; } | Horizontal distance the shadow will be offset. Default 0. |
| [ShadowOffsetY](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/shadowoffsety) { get; set; } | Vertical distance the shadow will be offset. Default 0. |
| [StrokeStyle](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/strokestyle) { get; set; } | Color or style to use for the lines around shapes. Default: (black). |

## Methods

| Name | Description |
| --- | --- |
| [AddHitRegion](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/addhitregion)(Dictionary&lt;string, string&gt;) |  |
| [BeginPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/beginpath)() | Starts a new path by emptying the list of sub-paths. Call this method when you want to create a new path. |
| [ClearHitRegions](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clearhitregions)() | Removes all hit regions from the canvas. |
| [ClearRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clearrect)(double, double, double, double) | Sets all pixels in the rectangle defined by starting point (x, y) and size (width, height) to transparent black, erasing any previously drawn content. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip)() | Creates a new clipping region by calculating the intersection of the current clipping region and the area described by the path, using the non-zero winding number rule. Open subpaths must be implicitly closed when computing the clipping region, without affecting the actual subpaths. The new clipping region replaces the current clipping region. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip)(CanvasFillRule) | Creates a new clipping region by calculating the intersection of the current clipping region and the area described by the path, using the non-zero winding number rule. Open subpaths must be implicitly closed when computing the clipping region, without affecting the actual subpaths. The new clipping region replaces the current clipping region. |
| [Clip](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/clip)(Path2D, CanvasFillRule) | Creates a new clipping region by calculating the intersection of the current clipping region and the area described by the path, using the non-zero winding number rule. Open subpaths must be implicitly closed when computing the clipping region, without affecting the actual subpaths. The new clipping region replaces the current clipping region. |
| [CreateImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata)(IImageData) | Creates a new, blank ImageData object with the specified dimensions. All of the pixels in the new object are transparent black. |
| [CreateImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata)(double, double) | Creates a new, blank ImageData object with the specified dimensions. All of the pixels in the new object are transparent black. |
| [CreateLinearGradient](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createlineargradient)(double, double, double, double) | Creates a linear gradient along the line given by the coordinates represented by the parameters. |
| [CreatePattern](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern)(HTMLCanvasElement, string) | Creates a pattern using the specified image (a CanvasImageSource). It repeats the source in the directions specified by the repetition argument. |
| [CreatePattern](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern)(HTMLImageElement, string) | Creates a pattern using the specified image (a CanvasImageSource). It repeats the source in the directions specified by the repetition argument. |
| [CreateRadialGradient](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/createradialgradient)(double, double, double, double, double, double) | Creates a radial gradient given by the coordinates of the two circles represented by the parameters. |
| [DrawFocusIfNeeded](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawfocusifneeded)(Element) | If a given element is focused, this method draws a focus ring around the current path. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage)(HTMLCanvasElement, double, double) | Draws the specified image. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage)(HTMLImageElement, double, double) | Draws the specified image. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage)(HTMLCanvasElement, double, double, double, double) | Draws the specified image. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage)(HTMLImageElement, double, double, double, double) | Draws the specified image. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage)(HTMLCanvasElement, double, double, double, double, double, double, double, double) | Draws the specified image. |
| [DrawImage](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage)(HTMLImageElement, double, double, double, double, double, double, double, double) | Draws the specified image. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill)() | Fills the subpaths with the current fill style and default algorithm CanvasFillRule.Nonzero. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill)(CanvasFillRule) | Fills the subpaths with the current fill style. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill)(Path2D) | Fills the subpaths with the current fill style and default algorithm CanvasFillRule.Nonzero. |
| [Fill](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fill)(Path2D, CanvasFillRule) | Fills the subpaths with the current fill style. |
| [FillRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/fillrect)(double, double, double, double) | Draws a filled rectangle at (x, y) position whose size is determined by width and height. |
| [FillText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext)(string, double, double) | Draws (fills) a given text at the given (x,y) position. |
| [FillText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext)(string, double, double, double) | Draws (fills) a given text at the given (x,y) position. |
| [GetImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata)(double, double, double, double) | Returns an ImageData object representing the underlying pixel data for the area of the canvas denoted by the rectangle which starts at (sx, sy) and has an sw width and sh height. This method is not affected by the canvas transformation matrix. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath)(double, double) | Reports whether or not the specified point is contained in the current path. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath)(double, double, CanvasFillRule) | Reports whether or not the specified point is contained in the current path. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath)(Path2D, double, double) | Reports whether or not the specified point is contained in the current path. |
| [IsPointInPath](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath)(Path2D, double, double, CanvasFillRule) | Reports whether or not the specified point is contained in the current path. |
| [IsPointInStroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke)(double, double) | Reports whether or not the specified point is inside the area contained by the stroking of a path. |
| [IsPointInStroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke)(Path2D, double, double) | Reports whether or not the specified point is inside the area contained by the stroking of a path. |
| [MeasureText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/measuretext)(string) | Returns a TextMetrics object. |
| [PutImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata)(IImageData, double, double) | Paints data from the given ImageData object onto the bitmap. If a dirty rectangle is provided, only the pixels from that rectangle are painted. This method is not affected by the canvas transformation matrix. |
| [PutImageData](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata)(IImageData, double, double, double, double, double, double) | Paints data from the given ImageData object onto the bitmap. If a dirty rectangle is provided, only the pixels from that rectangle are painted. This method is not affected by the canvas transformation matrix. |
| [RemoveHitRegion](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/removehitregion)(string) | Removes the hit region with the specified id from the canvas. |
| [ResetTransform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/resettransform)() | Resets the current transform by the identity matrix. |
| [Restore](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/restore)() | Restores the drawing style state to the last element on the 'state stack' saved by save(). |
| [Rotate](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/rotate)(double) | Adds a rotation to the transformation matrix. The angle argument represents a clockwise rotation angle and is expressed in radians. |
| [Save](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/save)() | Saves the current drawing style state using a stack so you can revert any change you make to it using restore(). |
| [Scale](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/scale)(double, double) | Adds a scaling transformation to the canvas units by x horizontally and by y vertically. |
| [SetTransform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/settransform)(double, double, double, double, double, double) | Resets the current transform to the identity matrix, and then invokes the transform() method with the same arguments. |
| [Stroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke)() | Strokes the subpaths with the current stroke style. |
| [Stroke](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke)(Path2D) | Strokes the subpaths with the current stroke style. |
| [StrokeRect](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/strokerect)(double, double, double, double) | Paints a rectangle which has a starting point at (x, y) and has a w width and an h height onto the canvas, using the current stroke style. |
| [StrokeText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext)(string, double, double) | Draws (strokes) a given text at the given (x, y) position. |
| [StrokeText](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext)(string, double, double, double?) | Draws (strokes) a given text at the given (x, y) position. |
| [Transform](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/transform)(double, double, double, double, double, double) | Multiplies the current transformation matrix with the matrix described by its arguments. |
| [Translate](../../aspose.html.dom.canvas/icanvasrenderingcontext2d/translate)(double, double) | Adds a translation transformation by moving the canvas and its origin x horzontally and y vertically on the grid. |

### See Also

* interface [ICanvasDrawingStyles](../icanvasdrawingstyles)
* interface [ICanvasPathMethods](../icanvaspathmethods)
* namespace [Aspose.Html.Dom.Canvas](../../aspose.html.dom.canvas)
* assembly [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
