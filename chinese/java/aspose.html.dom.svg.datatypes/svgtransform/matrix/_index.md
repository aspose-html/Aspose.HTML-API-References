---
title: "SVGTransform.Matrix"
second_title: "Aspose.HTML for Java API 参考"
description: "SVGTransform 属性。表示此变换的矩阵。矩阵对象是实时的，这意味着对 SVGTransform 对象所做的任何更改都会立即反映在矩阵对象中，反之亦然。如果直接更改矩阵对象（即不使用 SVGTransform 接口本身的方法），则 SVGTransform 的类型会变为 SVG_TRANSFORM_MATRIX。对于 SVG_TRANSFORM_MATRIX，矩阵包含用户提供的 a、b、c、d、e、f 值。对于 SVG_TRANSFORM_TRANSLATE，e 和 f 表示平移量（a=1，b=0，c=0，d=1）。对于 SVG_TRANSFORM_SCALE，a 和 d 表示缩放量（b=0，c=0，e=0，f=0）。对于 SVG_TRANSFORM_SKEWX 和 SVG_TRANSFORM_SKEWY，a、b、c 和 d 表示将产生给定倾斜的矩阵（e=0，f=0）。对于 SVG_TRANSFORM_ROTATE，a、b、c、d、e 和 f 共同表示将产生给定旋转的矩阵。当旋转围绕中心点 (0,0) 时，e 和 f 为零。"
type: docs

url: /zh/java/com.aspose.html.dom.svg.datatypes/svgtransform/matrix/
---
## SVGTransform.Matrix property

表示此变换的矩阵。矩阵对象是实时的，这意味着对 SVGTransform 对象所做的任何更改都会立即反映在矩阵对象中，反之亦然。如果直接更改矩阵对象（即不使用 SVGTransform 接口本身的方法），则 SVGTransform 的类型会变为 SVG_TRANSFORM_MATRIX。对于 SVG_TRANSFORM_MATRIX，矩阵包含用户提供的 a、b、c、d、e、f 值。对于 SVG_TRANSFORM_TRANSLATE，e 和 f 表示平移量（a=1，b=0，c=0，d=1）。对于 SVG_TRANSFORM_SCALE，a 和 d 表示缩放量（b=0，c=0，e=0，f=0）。对于 SVG_TRANSFORM_SKEWX 和 SVG_TRANSFORM_SKEWY，a、b、c 和 d 表示将产生给定倾斜的矩阵（e=0，f=0）。对于 SVG_TRANSFORM_ROTATE，a、b、c、d、e 和 f 共同表示将产生给定旋转的矩阵。当旋转围绕中心点 (0, 0) 时，e 和 f 为零。

```java
public SVGMatrix Matrix { get; }
```

### Property Value

表示此变换的矩阵。

### 另请参见

* class [SVGMatrix](../../svgmatrix/)
* class [SVGTransform](../)
* package [com.aspose.html.dom.svg.datatypes](../../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../../)
