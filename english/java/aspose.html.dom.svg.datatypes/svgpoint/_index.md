---
title: SVGPoint Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.dom.svg.datatypes.SVGPoint class. Many of the SVG DOM interfaces refer to objects of class SVGPoint. An SVGPoint is an x y coordinate pair. When used in matrix operations an SVGPoint is treated as a vector of the form x y 1 If an SVGRect object is designated as read only then attempting to assign to one of its attributes will result in an exception being thrown
type: docs
weight: 1260
url: /java/com.aspose.html.dom.svg.datatypes/svgpoint/
---
## SVGPoint class

Many of the SVG DOM interfaces refer to objects of class SVGPoint. An SVGPoint is an (x, y) coordinate pair. When used in matrix operations, an SVGPoint is treated as a vector of the form: [x] [y] [1] If an SVGRect object is designated as read only, then attempting to assign to one of its attributes will result in an exception being thrown.

```java
public class SVGPoint : SVGValueType
```

## Properties

| Name | Description |
| --- | --- |
| [X](../../com.aspose.html.dom.svg.datatypes/svgpoint/x/) { get; set; } | The X coordinate. |
| [Y](../../com.aspose.html.dom.svg.datatypes/svgpoint/y/) { get; set; } | The Y coordinate. |

## Methods

| Name | Description |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Releases unmanaged and - optionally - managed resources. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | This method is used to retrieve the ECMAScript object . |
| [matrixTransform](../../com.aspose.html.dom.svg.datatypes/svgpoint/matrixtransform/)(SVGMatrix) | Applies a 2x3 matrix transformation on this SVGPoint object and returns a new, transformed SVGPoint object: newpoint = matrix* thispoint |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgpoint/toString/)() | Returns a String that represents this instance. |

### See Also

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
