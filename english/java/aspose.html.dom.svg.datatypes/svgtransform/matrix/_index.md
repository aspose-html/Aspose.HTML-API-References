---
title: SVGTransform.Matrix
second_title: Aspose.HTML for Java API Reference
description: SVGTransform property. The matrix that represents this transformation. The matrix object is live meaning that any changes made to the SVGTransform object are immediately reflected in the matrix object and vice versa. In case the matrix object is changed directly i.e. without using the methods on the SVGTransform interface itself then the type of the SVGTransform changes to SVG_TRANSFORM_MATRIX. For SVG_TRANSFORM_MATRIX the matrix contains the a b c d e f values supplied by the user. For SVG_TRANSFORM_TRANSLATE e and f represent the translation amountsa 1 b 0 c 0 and d  1. For SVG_TRANSFORM_SCALE a and d represent the scale amountsb 0 c 0 e 0 and f  0. For SVG_TRANSFORM_SKEWX and SVG_TRANSFORM_SKEWY a b c and d represent the matrix which will result in the given skewe 0 and f  0. For SVG_TRANSFORM_ROTATE a b c d e and f together represent the matrix which will result in the given rotation.When the rotation is around the center point0 0 e and f will be zero
type: docs
weight: 20
url: /java/com.aspose.html.dom.svg.datatypes/svgtransform/matrix/
---
## SVGTransform.Matrix property

The matrix that represents this transformation. The matrix object is live, meaning that any changes made to the SVGTransform object are immediately reflected in the matrix object and vice versa. In case the matrix object is changed directly (i.e., without using the methods on the SVGTransform interface itself) then the type of the SVGTransform changes to SVG_TRANSFORM_MATRIX. For SVG_TRANSFORM_MATRIX, the matrix contains the a, b, c, d, e, f values supplied by the user. For SVG_TRANSFORM_TRANSLATE, e and f represent the translation amounts(a= 1, b= 0, c= 0 and d = 1). For SVG_TRANSFORM_SCALE, a and d represent the scale amounts(b= 0, c= 0, e= 0 and f = 0). For SVG_TRANSFORM_SKEWX and SVG_TRANSFORM_SKEWY, a, b, c and d represent the matrix which will result in the given skew(e= 0 and f = 0). For SVG_TRANSFORM_ROTATE, a, b, c, d, e and f together represent the matrix which will result in the given rotation.When the rotation is around the center point(0, 0), e and f will be zero.

```java
public SVGMatrix Matrix { get; }
```

### Property Value

The matrix that represents this transformation.

### See Also

* class [SVGMatrix](../../svgmatrix/)
* class [SVGTransform](../)
* package [com.aspose.html.dom.svg.datatypes](../../svgtransform/)
* package [Aspose.HTML](../../../)
