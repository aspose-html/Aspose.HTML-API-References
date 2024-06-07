---
title: set_matrix method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 30
url: /aspose.html.dom.svg.datatypes/svgtransform/set_matrix/
is_root: false
---

## set_matrix {#aspose.html.dom.svg.datatypes.SVGMatrix}

Sets the transform type to SVG_TRANSFORM_MATRIX, with parameter matrix defining the new transformation. The values from the parameter matrix are copied, the matrix parameter does not replace SVGTransform::matrix.



```python
def set_matrix(self, matrix):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [`SVGMatrix`](/html/python-net/aspose.html.dom.svg.datatypes/svgmatrix) | The new matrix for the transformation. |
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | Code [`DOMException.NO_MODIFICATION_ALLOWED_ERR`](/html/python-net/aspose.html.dom/domexception). <br/>Raised on an attempt to change the value of a read only attribute. |





### See Also
* module [`aspose.html.dom.svg.datatypes`](../../)
* class [`DOMException`](/html/python-net/aspose.html.dom/domexception)
* class [`SVGTransform`](/html/python-net/aspose.html.dom.svg.datatypes/svgtransform)
