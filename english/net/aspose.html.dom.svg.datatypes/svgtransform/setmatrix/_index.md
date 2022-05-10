---
title: SetMatrix
second_title: Aspose.HTML for .NET API Reference
description: 
type: docs
weight: 40
url: /net/aspose.html.dom.svg.datatypes/svgtransform/setmatrix/
---
## SVGTransform.SetMatrix method

Sets the transform type to SVG_TRANSFORM_MATRIX, with parameter matrix defining the new transformation. The values from the parameter matrix are copied, the matrix parameter does not replace SVGTransform::matrix.

```csharp
public void SetMatrix(SVGMatrix matrix)
```

| Parameter | Type | Description |
| --- | --- | --- |
| matrix | SVGMatrix | The new matrix for the transformation. |

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception) | Code [`NO_MODIFICATION_ALLOWED_ERR`](../../../aspose.html.dom/domexception/no_modification_allowed_err). Raised on an attempt to change the value of a read only attribute. |

### See Also

* class [SVGMatrix](../../svgmatrix)
* class [SVGTransform](../../svgtransform)
* namespace [Aspose.Html.Dom.Svg.DataTypes](../../svgtransform)
* assembly [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->