---
title: create_matrix method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 40
url: /python-net/aspose.html.drawing/idrawingfactory/create_matrix/
is_root: false
---

## create_matrix {#}

Creates a new identity matrix.


### Returns 


The created [`IMatrix`](/html/python-net/aspose.html.drawing/imatrix).


```python
def create_matrix(self):
    ...
```




## create_matrix {#aspose.html.drawing.IMatrix}

Creates a new matrix with the same contents as the specified matrix.


### Returns 


The created [`IMatrix`](/html/python-net/aspose.html.drawing/imatrix).


```python
def create_matrix(self, matrix):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| matrix | [`IMatrix`](/html/python-net/aspose.html.drawing/imatrix) | The matrix to copy. |


## create_matrix {#float-float-float-float-float-float}

Creates a new matrix with the specified elements.


### Returns 


The created [`IMatrix`](/html/python-net/aspose.html.drawing/imatrix).


```python
def create_matrix(self, m11, m12, m21, m22, m31, m32):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| m11 | float | The value in the first row and first column of the matrix. |
| m12 | float | The value in the first row and second column of the matrix. |
| m21 | float | The value in the second row and first column of the matrix. |
| m22 | float | The value in the second row and second column of the matrix. |
| m31 | float | The value in the third row and first column of the matrix. |
| m32 | float | The value in the third row and second column of the matrix. |



### See Also
* module [`aspose.html.drawing`](../../)
* class [`IDrawingFactory`](/html/python-net/aspose.html.drawing/idrawingfactory)
* class [`IMatrix`](/html/python-net/aspose.html.drawing/imatrix)
