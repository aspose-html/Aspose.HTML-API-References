---
title: "SVGMatrix 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.svg.datatypes.SVGMatrix 类。许多 SVG 图形操作使用形式为 a c e b d f 的 2x3 矩阵，在展开为用于矩阵运算的 3x3 矩阵时变为 a c e b d f 0 0 1"
type: docs

url: /zh/java/com.aspose.html.dom.svg.datatypes/svgmatrix/
---
## SVGMatrix class

许多 SVG 的图形操作使用形式为 [a c e] [b d f] 的 2x3 矩阵，在进行矩阵运算时会展开为 3x3 矩阵，即 [a c e] [b d f] [0 0 1]。

```java
public class SVGMatrix : SVGValueType
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [A](../../com.aspose.html.dom.svg.datatypes/svgmatrix/a/) { get; set; } | 矩阵的 A 分量。 |
| [B](../../com.aspose.html.dom.svg.datatypes/svgmatrix/b/) { get; set; } | 矩阵的 B 分量。 |
| [C](../../com.aspose.html.dom.svg.datatypes/svgmatrix/c/) { get; set; } | 矩阵的 C 分量。 |
| [D](../../com.aspose.html.dom.svg.datatypes/svgmatrix/d/) { get; set; } | 矩阵的 D 分量。 |
| [E](../../com.aspose.html.dom.svg.datatypes/svgmatrix/e/) { get; set; } | 矩阵的 E 分量。 |
| [F](../../com.aspose.html.dom.svg.datatypes/svgmatrix/f/) { get; set; } | 矩阵的 F 分量。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | 释放非托管资源以及（可选的）托管资源。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象。 |
| [multiply](../../com.aspose.html.dom.svg.datatypes/svgmatrix/multiply/)(SVGMatrix) | 执行矩阵乘法。此矩阵被另一个矩阵后乘，返回生成的新矩阵。 |
| [rotate](../../com.aspose.html.dom.svg.datatypes/svgmatrix/rotate/)(float) | 在当前矩阵上后乘旋转变换并返回结果矩阵。 |
| [scale](../../com.aspose.html.dom.svg.datatypes/svgmatrix/scale/)(float) | 在当前矩阵上后乘统一缩放变换并返回结果矩阵。 |
| [scaleNonUniform](../../com.aspose.html.dom.svg.datatypes/svgmatrix/scalenonuniform/)(float, float) | 在当前矩阵上后乘非统一缩放变换并返回结果矩阵。 |
| [skewX](../../com.aspose.html.dom.svg.datatypes/svgmatrix/skewx/)(float) | 在当前矩阵上后乘一个 skewX 变换，并返回结果矩阵。 |
| [skewY](../../com.aspose.html.dom.svg.datatypes/svgmatrix/skewy/)(float) | 在当前矩阵上后乘一个 skewY 变换，并返回结果矩阵。 |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgmatrix/toString/)() | 返回表示此实例的字符串。 |
| [translate](../../com.aspose.html.dom.svg.datatypes/svgmatrix/translate/)(float, float) | 在当前矩阵上后乘一个平移变换，并返回结果矩阵。 |

### 另请参阅

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
