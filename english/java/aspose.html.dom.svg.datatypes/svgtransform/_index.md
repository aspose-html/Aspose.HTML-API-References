---
title: SVGTransform Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.dom.svg.datatypes.SVGTransform class. SVGTransform is the interface for one of the component transformations within an SVGTransformList thus an SVGTransform object corresponds to a single component e.g. scale or matrix within a transform attribute specification
type: docs
weight: 1310
url: /java/com.aspose.html.dom.svg.datatypes/svgtransform/
---
## SVGTransform class

SVGTransform is the interface for one of the component transformations within an SVGTransformList; thus, an SVGTransform object corresponds to a single component (e.g., 'scale(…)' or 'matrix(…)') within a ‘transform’ attribute specification.

```java
public class SVGTransform : SVGValueType
```

## Properties

| Name | Description |
| --- | --- |
| [getAngle](../../com.aspose.html.dom.svg.datatypes/svgtransform/angle/) A convenience attribute for SVG_TRANSFORM_ROTATE, SVG_TRANSFORM_SKEWX and SVG_TRANSFORM_SKEWY. It holds the angle that was specified. For SVG_TRANSFORM_MATRIX, SVG_TRANSFORM_TRANSLATE and SVG_TRANSFORM_SCALE, angle will be zero. |
| [getMatrix](../../com.aspose.html.dom.svg.datatypes/svgtransform/matrix/) The matrix that represents this transformation. The matrix object is live, meaning that any changes made to the SVGTransform object are immediately reflected in the matrix object and vice versa. In case the matrix object is changed directly (i.e., without using the methods on the SVGTransform interface itself) then the type of the SVGTransform changes to SVG_TRANSFORM_MATRIX. For SVG_TRANSFORM_MATRIX, the matrix contains the a, b, c, d, e, f values supplied by the user. For SVG_TRANSFORM_TRANSLATE, e and f represent the translation amounts(a= 1, b= 0, c= 0 and d = 1). For SVG_TRANSFORM_SCALE, a and d represent the scale amounts(b= 0, c= 0, e= 0 and f = 0). For SVG_TRANSFORM_SKEWX and SVG_TRANSFORM_SKEWY, a, b, c and d represent the matrix which will result in the given skew(e= 0 and f = 0). For SVG_TRANSFORM_ROTATE, a, b, c, d, e and f together represent the matrix which will result in the given rotation.When the rotation is around the center point(0, 0), e and f will be zero. |
| [getType](../../com.aspose.html.dom.svg.datatypes/svgtransform/type/) The type of the value as specified by one of the SVG_TRANSFORM_* constants defined on this interface. |

## Methods

| Name | Description |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | Releases unmanaged and - optionally - managed resources. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | This method is used to retrieve the ECMAScript object . |
| [setMatrix](../../com.aspose.html.dom.svg.datatypes/svgtransform/setmatrix/)(SVGMatrix) | Sets the transform type to SVG_TRANSFORM_MATRIX, with parameter matrix defining the new transformation. The values from the parameter matrix are copied, the matrix parameter does not replace SVGTransform::matrix. |
| [setRotate](../../com.aspose.html.dom.svg.datatypes/svgtransform/setrotate/)(float, float, float) | Sets the transform type to SVG_TRANSFORM_ROTATE, with parameter angle defining the rotation angle and parameters cx and cy defining the optional center of rotation. |
| [setScale](../../com.aspose.html.dom.svg.datatypes/svgtransform/setscale/)(float, float) | Sets the transform type to SVG_TRANSFORM_SCALE, with parameters sx and sy defining the scale amounts. |
| [setSkewX](../../com.aspose.html.dom.svg.datatypes/svgtransform/setskewx/)(float) | Sets the transform type to SVG_TRANSFORM_SKEWX, with parameter angle defining the amount of skew. |
| [setSkewY](../../com.aspose.html.dom.svg.datatypes/svgtransform/setskewy/)(float) | Sets the transform type to SVG_TRANSFORM_SKEWY, with parameter angle defining the amount of skew. |
| [setTranslate](../../com.aspose.html.dom.svg.datatypes/svgtransform/settranslate/)(float, float) | Sets the transform type to SVG_TRANSFORM_TRANSLATE, with parameters tx and ty defining the translation amounts. |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgtransform/toString/)() | Returns a String that represents this instance. |

## Fields

| Name | Description |
| --- | --- |
| const [SVG_TRANSFORM_MATRIX](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_matrix/) | A 'matrix(…)' transformation. |
| const [SVG_TRANSFORM_ROTATE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_rotate/) | A 'rotate(…)' transformation. |
| const [SVG_TRANSFORM_SCALE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_scale/) | A 'scale(…)' transformation. |
| const [SVG_TRANSFORM_SKEWX](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewx/) | A 'skewX(…)' transformation. |
| const [SVG_TRANSFORM_SKEWY](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewy/) | A 'skewY(…)' transformation. |
| const [SVG_TRANSFORM_TRANSLATE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_translate/) | A 'translate(…)' transformation. |
| const [SVG_TRANSFORM_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_unknown/) | The unit type is not one of predefined types. It is invalid to attempt to define a new value of this type or to attempt to switch an existing value to this type. |

### See Also

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
