---
title: matrix property
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 180
url: /python-net/aspose.html.dom.svg.datatypes/svgtransform/matrix/
is_root: false
---

## matrix property


The matrix that represents this transformation. The matrix object is live, meaning that any changes made to the SVGTransform object are immediately reflected in the matrix object and vice versa. In case the matrix object is changed directly (i.e., without using the methods on the SVGTransform interface itself) then the type of the SVGTransform changes to SVG_TRANSFORM_MATRIX.
For SVG_TRANSFORM_MATRIX, the matrix contains the a, b, c, d, e, f values supplied by the user.
For SVG_TRANSFORM_TRANSLATE, e and f represent the translation amounts(a= 1, b= 0, c= 0 and d = 1).
For SVG_TRANSFORM_SCALE, a and d represent the scale amounts(b= 0, c= 0, e= 0 and f = 0).
For SVG_TRANSFORM_SKEWX and SVG_TRANSFORM_SKEWY, a, b, c and d represent the matrix which will result in the given skew(e= 0 and f = 0).
For SVG_TRANSFORM_ROTATE, a, b, c, d, e and f together represent the matrix which will result in the given rotation.When the rotation is around the center point(0, 0), e and f will be zero.
### Definition:
```python
@property
def matrix(self):
    ...
```

### See Also
* module [`aspose.html.dom.svg.datatypes`](../../)
* class [`SVGMatrix`](/html/python-net/aspose.html.dom.svg.datatypes/svgmatrix)
* class [`SVGTransform`](/html/python-net/aspose.html.dom.svg.datatypes/svgtransform)
