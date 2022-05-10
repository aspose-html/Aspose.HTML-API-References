---
title: SVGSVGElement
second_title: Aspose.HTML for .NET API Reference
description: 
type: docs
weight: 2370
url: /net/aspose.html.dom.svg/svgsvgelement/
---
## SVGSVGElement class

A key interface definition is the SVGSVGElement interface, which is the interface that corresponds to the ‘svg’ element. This interface contains various miscellaneous commonly-used utility methods, such as matrix operations and the ability to control the time of redraw on visual rendering devices.

```csharp
public class SVGSVGElement : SVGGraphicsElement, IDocumentEvent, ISVGFitToViewBox, ISVGZoomAndPan
```

## Properties

| Name | Description |
| --- | --- |
| [CurrentScale](currentscale) { get; set; } | On an outermost svg element, this attribute indicates the current scale factor relative to the initial view to take into account user magnification and panning operations, as described under Magnification and panning. DOM attributes currentScale and currentTranslate are equivalent to the 2x3 matrix [a b c d e f] = [currentScale 0 0 currentScale currentTranslate.x currentTranslate.y]. If "magnification" is enabled (i.e., zoomAndPan="magnify"), then the effect is as if an extra transformation were placed at the outermost level on the SVG document fragment (i.e., outside the outermost svg element). When accessed on an ‘svg’ element that is not an outermost svg element, it is undefined what behavior this attribute has. |
| [CurrentTranslate](currenttranslate) { get; } | On an outermost svg element, the corresponding translation factor that takes into account user "magnification". When accessed on an ‘svg’ element that is not an outermost svg element, it is undefined what behavior this attribute has. |
| [Height](height) { get; } | Corresponds to attribute ‘height’ on the given ‘svg’ element. |
| [PreserveAspectRatio](preserveaspectratio) { get; } | Corresponds to attribute ‘preserveAspectRatio’ on the given element. |
| [ViewBox](viewbox) { get; } | Corresponds to attribute ‘viewBox’ on the given element. |
| [Width](width) { get; } | Corresponds to attribute ‘width’ on the given ‘svg’ element. |
| [X](x) { get; } | Corresponds to attribute ‘x’ on the given ‘svg’ element. |
| [Y](y) { get; } | Corresponds to attribute ‘y’ on the given ‘svg’ element. |
| [ZoomAndPan](zoomandpan) { get; set; } | Corresponds to attribute ‘zoomAndPan’ on the given element. The value must be one of the SVG_ZOOMANDPAN_* constants defined on this interface. |

## Methods

| Name | Description |
| --- | --- |
| [AnimationsPaused](animationspaused)() | Returns true if this SVG document fragment is in a paused state. |
| [CreateEvent](createevent)(string) | Creates an [`Event`](../../aspose.html.dom.events/event) of a type supported by the implementation. |
| [CreateSVGAngle](createsvgangle)() | Creates an SVGAngle object outside of any document trees. The object is initialized to the value 0 degrees (unitless). |
| [CreateSVGLength](createsvglength)() | Creates an SVGLength object outside of any document trees. The object is initialized to the value of 0 user units. |
| [CreateSVGMatrix](createsvgmatrix)() | Creates an SVGMatrix object outside of any document trees. The object is initialized to the identity matrix. |
| [CreateSVGNumber](createsvgnumber)() | Creates an SVGNumber object outside of any document trees. The object is initialized to a value of zero. |
| [CreateSVGPoint](createsvgpoint)() | Creates an SVGPoint object outside of any document trees. The object is initialized to the point (0,0) in the user coordinate system. |
| [CreateSVGRect](createsvgrect)() | Creates an SVGRect object outside of any document trees. The object is initialized such that all values are set to 0 user units. |
| [CreateSVGTransform](createsvgtransform)() | Creates an SVGTransform object outside of any document trees. The object is initialized to an identity matrix transform (SVG_TRANSFORM_MATRIX). |
| [CreateSVGTransformFromMatrix](createsvgtransformfrommatrix)(SVGMatrix) | Creates an SVGTransform object outside of any document trees. The object is initialized to the given matrix transform (i.e., SVG_TRANSFORM_MATRIX). The values from the parameter matrix are copied, the matrix parameter is not adopted as SVGTransform::matrix. |
| [GetCurrentTime](getcurrenttime)() | Returns the current time in seconds relative to the start time for the current SVG document fragment. If getCurrentTime is called before the document timeline has begun (for example, by script running in a ‘script’ element before the document's SVGLoad event is dispatched), then 0 is returned. |
| [GetElementById](getelementbyid)(string) | Searches this SVG document fragment (i.e., the search is restricted to a subset of the document tree) for an Element whose id is given by elementId. If an Element is found, that Element is returned. If no such element exists, returns null. Behavior is not defined if more than one element has this id. |
| [PauseAnimations](pauseanimations)() | Suspends (i.e., pauses) all currently running animations that are defined within the SVG document fragment corresponding to this ‘svg’ element, causing the animation clock corresponding to this document fragment to stand still until it is unpaused. |
| [SetCurrentTime](setcurrenttime)(float) | Adjusts the clock for this SVG document fragment, establishing a new current time. If setCurrentTime is called before the document timeline has begun (for example, by script running in a ‘script’ element before the document's SVGLoad event is dispatched), then the value of seconds in the last invocation of the method gives the time that the document will seek to once the document timeline has begun. |
| [UnpauseAnimations](unpauseanimations)() | Unsuspends (i.e., unpauses) currently running animations that are defined within the SVG document fragment, causing the animation clock to continue from the time at which it was suspended. |

### See Also

* class [SVGGraphicsElement](../svggraphicselement)
* interface [ISVGFitToViewBox](../isvgfittoviewbox)
* interface [IDocumentEvent](../../aspose.html.dom.events/idocumentevent)
* interface [IViewCSS](../../aspose.html.dom.css/iviewcss)
* interface [IDocumentCSS](../../aspose.html.dom.css/idocumentcss)
* interface [ISVGZoomAndPan](../isvgzoomandpan)
* namespace [Aspose.Html.Dom.Svg](../../aspose.html.dom.svg)
* assembly [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
