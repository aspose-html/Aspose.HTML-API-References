---
title: SVGMarkerElement
second_title: Aspose.HTML for .NET API Reference
description: 
type: docs
weight: 2270
url: /net/aspose.html.dom.svg/svgmarkerelement/
---
## SVGMarkerElement class

The SVGMarkerElement interface corresponds to the ‘marker’ element.

```csharp
public class SVGMarkerElement : SVGElement, ISVGFitToViewBox
```

## Properties

| Name | Description |
| --- | --- |
| [MarkerHeight](markerheight) { get; } | Corresponds to attribute ‘markerHeight’ on the given ‘marker’ element. |
| [MarkerUnits](markerunits) { get; } | Corresponds to attribute ‘markerUnits’ on the given ‘marker’ element. One of the Marker Unit Types defined on this interface. |
| [MarkerWidth](markerwidth) { get; } | Corresponds to attribute ‘markerWidth’ on the given ‘marker’ element. |
| [OrientAngle](orientangle) { get; } | Corresponds to attribute ‘orient’ on the given ‘marker’ element. If markerUnits is SVG_MARKER_ORIENT_ANGLE, the angle value for attribute ‘orient’; otherwise, it will be set to zero. |
| [OrientType](orienttype) { get; } | Corresponds to attribute ‘orient’ on the given ‘marker’ element. One of the Marker Orientation Types defined on this interface. |
| [PreserveAspectRatio](preserveaspectratio) { get; } | Corresponds to attribute ‘preserveAspectRatio’ on the given element. |
| [RefX](refx) { get; } | Corresponds to attribute ‘refX’ on the given ‘marker’ element. |
| [RefY](refy) { get; } | Corresponds to attribute ‘refY’ on the given ‘marker’ element. |
| [ViewBox](viewbox) { get; } | Corresponds to attribute ‘viewBox’ on the given element. |

## Methods

| Name | Description |
| --- | --- |
| [SetOrientToAngle](setorienttoangle)(SVGAngle) | Sets the value of attribute ‘orient’ to the given angle. |
| [SetOrientToAuto](setorienttoauto)() | Sets the value of attribute ‘orient’ to 'auto'. |

## Other Members

| Name | Description |
| --- | --- |
| const [SVG_MARKERUNITS_STROKEWIDTH](svg_markerunits_strokewidth) | The value of attribute ‘markerUnits’ is 'strokeWidth'. |
| const [SVG_MARKERUNITS_UNKNOWN](svg_markerunits_unknown) | The marker unit type is not one of predefined types. It is invalid to attempt to define a new value of this type or to attempt to switch an existing value to this type. |
| const [SVG_MARKERUNITS_USERSPACEONUSE](svg_markerunits_userspaceonuse) | The value of attribute ‘markerUnits’ is 'userSpaceOnUse'. |
| const [SVG_MARKER_ORIENT_ANGLE](svg_marker_orient_angle) | Attribute ‘orient’ has an angle value. |
| const [SVG_MARKER_ORIENT_AUTO](svg_marker_orient_auto) | Attribute ‘orient’ has value 'auto'. |
| const [SVG_MARKER_ORIENT_UNKNOWN](svg_marker_orient_unknown) | The marker orientation is not one of predefined types. It is invalid to attempt to define a new value of this type or to attempt to switch an existing value to this type. |

### See Also

* class [SVGElement](../svgelement)
* interface [ISVGFitToViewBox](../isvgfittoviewbox)
* namespace [Aspose.Html.Dom.Svg](../../aspose.html.dom.svg)
* assembly [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->