---
title: ICanvasRenderingContext2D Interface
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.Dom.Canvas.ICanvasRenderingContext2D interface. The ICanvasRenderingContext2D interface is used for drawing rectangles text images and other objects onto the canvas element. It provides the 2D rendering context for the drawing surface of a canvas element
type: docs
weight: 270
url: /net/com.aspose.html.dom.canvas/icanvasrenderingcontext2d/
---
## ICanvasRenderingContext2D interface

The ICanvasRenderingContext2D interface is used for drawing rectangles, text, images and other objects onto the canvas element. It provides the 2D rendering context for the drawing surface of a canvas element.

```java
public interface ICanvasRenderingContext2D : ICanvasDrawingStyles, ICanvasPathMethods
```

## Properties

| Name | Description |
| --- | --- |
| [getCanvas](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/canvas/) A read-only back-reference to the HTMLCanvasElement. Might be null if it is not associated with a canvas element. |
[getFillStyle]
[setFillStyle] Color or style to use inside shapes. Default: (black). |
[getGlobalAlpha]
[setGlobalAlpha] Alpha value that is applied to shapes and images before they are composited onto the canvas. Default 1.0 (opaque). |
[getGlobalCompositeOperation]
[setGlobalCompositeOperation] With globalAlpha applied this sets how shapes and images are drawn onto the existing bitmap. Default: (source-over) |
[getImageSmoothingEnabled]
[setImageSmoothingEnabled] Image smoothing mode; if disabled, images will not be smoothed if scaled. |
[getShadowBlur]
[setShadowBlur] Specifies the blurring effect. Default 0 |
[getShadowColor]
[setShadowColor] Color of the shadow. Default fully-transparent black. |
[getShadowOffsetX]
[setShadowOffsetX] Horizontal distance the shadow will be offset. Default 0. |
[getShadowOffsetY]
[setShadowOffsetY] Vertical distance the shadow will be offset. Default 0. |
[getStrokeStyle]
[setStrokeStyle] Color or style to use for the lines around shapes. Default: (black). |

## Methods

| Name | Description |
| --- | --- |
| [addHitRegion](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/addhitregion/)(Dictionary&lt;String, String&gt;) |  |
| [beginPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/beginpath/)() | Starts a new path by emptying the list of sub-paths. Call this method when you want to create a new path. |
| [clearHitRegions](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clearhitregions/)() | Removes all hit regions from the canvas. |
| [clearRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clearrect/)(double, double, double, double) | Sets all pixels in the rectangle defined by starting point (x, y) and size (width, height) to transparent black, erasing any previously drawn content. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip)() | Creates a new clipping region by calculating the intersection of the current clipping region and the area described by the path, using the non-zero winding number rule. Open subpaths must be implicitly closed when computing the clipping region, without affecting the actual subpaths. The new clipping region replaces the current clipping region. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_1)(CanvasFillRule) | Creates a new clipping region by calculating the intersection of the current clipping region and the area described by the path, using the non-zero winding number rule. Open subpaths must be implicitly closed when computing the clipping region, without affecting the actual subpaths. The new clipping region replaces the current clipping region. |
| [clip](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/clip/#clip_2)(Path2D, CanvasFillRule) | Creates a new clipping region by calculating the intersection of the current clipping region and the area described by the path, using the non-zero winding number rule. Open subpaths must be implicitly closed when computing the clipping region, without affecting the actual subpaths. The new clipping region replaces the current clipping region. |
| [createImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata)(IImageData) | Creates a new, blank ImageData object with the specified dimensions. All of the pixels in the new object are transparent black. |
| [createImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createimagedata/#createimagedata_1)(double, double) | Creates a new, blank ImageData object with the specified dimensions. All of the pixels in the new object are transparent black. |
| [createLinearGradient](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createlineargradient/)(double, double, double, double) | Creates a linear gradient along the line given by the coordinates represented by the parameters. |
| [createPattern](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern)(HTMLCanvasElement, String) | Creates a pattern using the specified image (a CanvasImageSource). It repeats the source in the directions specified by the repetition argument. |
| [createPattern](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createpattern/#createpattern_1)(HTMLImageElement, String) | Creates a pattern using the specified image (a CanvasImageSource). It repeats the source in the directions specified by the repetition argument. |
| [createRadialGradient](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/createradialgradient/)(double, double, double, double, double, double) | Creates a radial gradient given by the coordinates of the two circles represented by the parameters. |
| [drawFocusIfNeeded](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawfocusifneeded/)(Element) | If a given element is focused, this method draws a focus ring around the current path. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage)(HTMLCanvasElement, double, double) | Draws the specified image. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_3)(HTMLImageElement, double, double) | Draws the specified image. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_1)(HTMLCanvasElement, double, double, double, double) | Draws the specified image. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_4)(HTMLImageElement, double, double, double, double) | Draws the specified image. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_2)(HTMLCanvasElement, double, double, double, double, double, double, double, double) | Draws the specified image. |
| [drawImage](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/drawimage/#drawimage_5)(HTMLImageElement, double, double, double, double, double, double, double, double) | Draws the specified image. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill)() | Fills the subpaths with the current fill style and default algorithm CanvasFillRule.Nonzero. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_1)(CanvasFillRule) | Fills the subpaths with the current fill style. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_2)(Path2D) | Fills the subpaths with the current fill style and default algorithm CanvasFillRule.Nonzero. |
| [fill](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fill/#fill_3)(Path2D, CanvasFillRule) | Fills the subpaths with the current fill style. |
| [fillRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/fillrect/)(double, double, double, double) | Draws a filled rectangle at (x, y) position whose size is determined by width and height. |
| [fillText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext)(String, double, double) | Draws (fills) a given text at the given (x,y) position. |
| [fillText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/filltext/#filltext_1)(String, double, double, double) | Draws (fills) a given text at the given (x,y) position. |
| [getImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/getimagedata/)(double, double, double, double) | Returns an ImageData object representing the underlying pixel data for the area of the canvas denoted by the rectangle which starts at (sx, sy) and has an sw width and sh height. This method is not affected by the canvas transformation matrix. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_2)(double, double) | Reports whether or not the specified point is contained in the current path. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_3)(double, double, CanvasFillRule) | Reports whether or not the specified point is contained in the current path. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath)(Path2D, double, double) | Reports whether or not the specified point is contained in the current path. |
| [isPointInPath](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinpath/#ispointinpath_1)(Path2D, double, double, CanvasFillRule) | Reports whether or not the specified point is contained in the current path. |
| [isPointInStroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke_1)(double, double) | Reports whether or not the specified point is inside the area contained by the stroking of a path. |
| [isPointInStroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/ispointinstroke/#ispointinstroke)(Path2D, double, double) | Reports whether or not the specified point is inside the area contained by the stroking of a path. |
| [measureText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/measuretext/)(String) | Returns a TextMetrics object. |
| [putImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata)(IImageData, double, double) | Paints data from the given ImageData object onto the bitmap. If a dirty rectangle is provided, only the pixels from that rectangle are painted. This method is not affected by the canvas transformation matrix. |
| [putImageData](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/putimagedata/#putimagedata_1)(IImageData, double, double, double, double, double, double) | Paints data from the given ImageData object onto the bitmap. If a dirty rectangle is provided, only the pixels from that rectangle are painted. This method is not affected by the canvas transformation matrix. |
| [removeHitRegion](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/removehitregion/)(String) | Removes the hit region with the specified id from the canvas. |
| [resetTransform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/resettransform/)() | Resets the current transform by the identity matrix. |
| [restore](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/restore/)() | Restores the drawing style state to the last element on the 'state stack' saved by save(). |
| [rotate](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/rotate/)(double) | Adds a rotation to the transformation matrix. The angle argument represents a clockwise rotation angle and is expressed in radians. |
| [save](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/save/)() | Saves the current drawing style state using a stack so you can revert any change you make to it using restore(). |
| [scale](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/scale/)(double, double) | Adds a scaling transformation to the canvas units by x horizontally and by y vertically. |
| [setTransform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/settransform/)(double, double, double, double, double, double) | Resets the current transform to the identity matrix, and then invokes the transform() method with the same arguments. |
| [stroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke)() | Strokes the subpaths with the current stroke style. |
| [stroke](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroke/#stroke_1)(Path2D) | Strokes the subpaths with the current stroke style. |
| [strokeRect](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/strokerect/)(double, double, double, double) | Paints a rectangle which has a starting point at (x, y) and has a w width and an h height onto the canvas, using the current stroke style. |
| [strokeText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext)(String, double, double) | Draws (strokes) a given text at the given (x, y) position. |
| [strokeText](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/stroketext/#stroketext_1)(String, double, double, double?) | Draws (strokes) a given text at the given (x, y) position. |
| [transform](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/transform/)(double, double, double, double, double, double) | Multiplies the current transformation matrix with the matrix described by its arguments. |
| [translate](../../com.aspose.html.dom.canvas/icanvasrenderingcontext2d/translate/)(double, double) | Adds a translation transformation by moving the canvas and its origin x horzontally and y vertically on the grid. |

### See Also

* interface [ICanvasDrawingStyles](../icanvasdrawingstyles/)
* interface [ICanvasPathMethods](../icanvaspathmethods/)
* package [com.aspose.html.Dom.Canvas](../../com.aspose.html.dom.canvas/)
* package [Aspose.HTML](../../)
