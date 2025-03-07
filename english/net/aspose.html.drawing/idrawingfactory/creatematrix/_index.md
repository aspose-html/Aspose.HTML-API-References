---
title: IDrawingFactory.CreateMatrix
second_title: Aspose.HTML for .NET API Reference
description: IDrawingFactory CreateMatrix method. Creates a new matrix with the same contents as the specified matrix
type: docs
weight: 30
url: /net/aspose.html.drawing/idrawingfactory/creatematrix/
---
## CreateMatrix(*[IMatrix](../../imatrix/)*) {#creatematrix_1}

Creates a new matrix with the same contents as the specified matrix.

```csharp
public IMatrix CreateMatrix(IMatrix matrix)
```

| Parameter | Type | Description |
| --- | --- | --- |
| matrix | IMatrix | The matrix to copy. |

### Return Value

The created [`IMatrix`](../../imatrix/).

### See Also

* interface [IMatrix](../../imatrix/)
* interface [IDrawingFactory](../)
* namespace [Aspose.Html.Drawing](../../../aspose.html.drawing/)
* assembly [Aspose.HTML](../../../)

---

## CreateMatrix(*float, float, float, float, float, float*) {#creatematrix_2}

Creates a new matrix with the specified elements.

```csharp
public IMatrix CreateMatrix(float m11, float m12, float m21, float m22, float m31, float m32)
```

| Parameter | Type | Description |
| --- | --- | --- |
| m11 | Single | The value in the first row and first column of the matrix. |
| m12 | Single | The value in the first row and second column of the matrix. |
| m21 | Single | The value in the second row and first column of the matrix. |
| m22 | Single | The value in the second row and second column of the matrix. |
| m31 | Single | The value in the third row and first column of the matrix. |
| m32 | Single | The value in the third row and second column of the matrix. |

### Return Value

The created [`IMatrix`](../../imatrix/).

### See Also

* interface [IMatrix](../../imatrix/)
* interface [IDrawingFactory](../)
* namespace [Aspose.Html.Drawing](../../../aspose.html.drawing/)
* assembly [Aspose.HTML](../../../)

---

## CreateMatrix() {#creatematrix}

Creates a new identity matrix.

```csharp
public IMatrix CreateMatrix()
```

### Return Value

The created [`IMatrix`](../../imatrix/).

### See Also

* interface [IMatrix](../../imatrix/)
* interface [IDrawingFactory](../)
* namespace [Aspose.Html.Drawing](../../../aspose.html.drawing/)
* assembly [Aspose.HTML](../../../)
