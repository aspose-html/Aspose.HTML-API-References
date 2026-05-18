---
title: "SVGTransform.SetMatrix"
second_title: "Aspose.HTML for Java API 参考"
description: "SVGTransform 方法。将变换类型设置为 SVG_TRANSFORM_MATRIX，参数 matrix 定义新的变换。参数 matrix 的值被复制，matrix 参数不会替换 SVGTransformmatrix"
type: docs

url: /zh/java/com.aspose.html.dom.svg.datatypes/svgtransform/setmatrix/
---
## SVGTransform.SetMatrix method

将变换类型设置为 SVG_TRANSFORM_MATRIX，参数 matrix 定义新的变换。参数 matrix 的值会被复制，matrix 参数不会替换 SVGTransform::matrix。

```java
public void SetMatrix(SVGMatrix matrix)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 矩阵 | SVGMatrix | 用于变换的新矩阵。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 代码 [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/)。在尝试更改只读属性的值时抛出。 |

### 另请参阅

* class [SVGMatrix](../../svgmatrix/)
* class [SVGTransform](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
