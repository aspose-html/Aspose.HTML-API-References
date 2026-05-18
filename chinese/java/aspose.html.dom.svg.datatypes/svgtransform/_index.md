---
title: "SVGTransform 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.svg.datatypes.SVGTransform 类。SVGTransform 是 SVGTransformList 中组件变换之一的接口，因此 SVGTransform 对象对应于变换属性规范中的单个组件，例如 scale（缩放）或 matrix（矩阵）。"
type: docs

url: /zh/java/com.aspose.html.dom.svg.datatypes/svgtransform/
---
## SVGTransform class

SVGTransform 是 SVGTransformList 中某个组件变换的接口；因此，SVGTransform 对象对应于 ‘transform’ 属性规范中的单个组件（例如 'scale(…)' 或 'matrix(…)')。

```java
public class SVGTransform : SVGValueType
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getAngle](../../com.aspose.html.dom.svg.datatypes/svgtransform/angle/) 是针对 SVG_TRANSFORM_ROTATE、SVG_TRANSFORM_SKEWX 和 SVG_TRANSFORM_SKEWY 的便利属性。它保存指定的角度。对于 SVG_TRANSFORM_MATRIX、SVG_TRANSFORM_TRANSLATE 和 SVG_TRANSFORM_SCALE，angle 将为零。 |
| [getMatrix](../../com.aspose.html.dom.svg.datatypes/svgtransform/matrix/) 表示此变换的矩阵。矩阵对象是实时的，这意味着对 SVGTransform 对象所做的任何更改会立即反映在矩阵对象中，反之亦然。如果直接更改矩阵对象（即未使用 SVGTransform 接口本身的方法），则 SVGTransform 的类型会变为 SVG_TRANSFORM_MATRIX。对于 SVG_TRANSFORM_MATRIX，矩阵包含用户提供的 a、b、c、d、e、f 值。对于 SVG_TRANSFORM_TRANSLATE，e 和 f 表示平移量（a=1，b=0，c=0，d=1）。对于 SVG_TRANSFORM_SCALE，a 和 d 表示缩放量（b=0，c=0，e=0，f=0）。对于 SVG_TRANSFORM_SKEWX 和 SVG_TRANSFORM_SKEWY，a、b、c、d 表示将产生给定倾斜的矩阵（e=0 且 f=0）。对于 SVG_TRANSFORM_ROTATE，a、b、c、d、e、f 共同表示将产生给定旋转的矩阵。当旋转围绕中心点 (0, 0) 时，e 和 f 为零。 |
| [getType](../../com.aspose.html.dom.svg.datatypes/svgtransform/type/) 该值的类型，由此接口上定义的 SVG_TRANSFORM_* 常量之一指定。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | 释放非托管资源以及（可选的）托管资源。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象。 |
| [setMatrix](../../com.aspose.html.dom.svg.datatypes/svgtransform/setmatrix/)(SVGMatrix) | 将变换类型设置为 SVG_TRANSFORM_MATRIX，参数 matrix 定义新的变换。参数 matrix 的值会被复制，matrix 参数不会替换 SVGTransform::matrix。 |
| [setRotate](../../com.aspose.html.dom.svg.datatypes/svgtransform/setrotate/)(float, float, float) | 将变换类型设置为 SVG_TRANSFORM_ROTATE，参数 angle 定义旋转角度，参数 cx 和 cy 定义可选的旋转中心。 |
| [setScale](../../com.aspose.html.dom.svg.datatypes/svgtransform/setscale/)(float, float) | 将变换类型设置为 SVG_TRANSFORM_SCALE，参数 sx 和 sy 定义缩放量。 |
| [setSkewX](../../com.aspose.html.dom.svg.datatypes/svgtransform/setskewx/)(float) | 将变换类型设置为 SVG_TRANSFORM_SKEWX，参数 angle 定义倾斜量。 |
| [setSkewY](../../com.aspose.html.dom.svg.datatypes/svgtransform/setskewy/)(float) | 将变换类型设置为 SVG_TRANSFORM_SKEWY，参数 angle 定义倾斜量。 |
| [setTranslate](../../com.aspose.html.dom.svg.datatypes/svgtransform/settranslate/)(float, float) | 将变换类型设置为 SVG_TRANSFORM_TRANSLATE，参数 tx 和 ty 定义平移量。 |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgtransform/toString/)() | 返回表示此实例的字符串。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [SVG_TRANSFORM_MATRIX](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_matrix/) | 一个 'matrix(…)' 变换。 |
| const [SVG_TRANSFORM_ROTATE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_rotate/) | 一个 'rotate(…)' 变换。 |
| const [SVG_TRANSFORM_SCALE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_scale/) | 一个 'scale(…)' 转换。 |
| const [SVG_TRANSFORM_SKEWX](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewx/) | 一个 'skewX(…)' 转换。 |
| const [SVG_TRANSFORM_SKEWY](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_skewy/) | 一个 'skewY(…)' 转换。 |
| const [SVG_TRANSFORM_TRANSLATE](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_translate/) | 一个 'translate(…)' 转换。 |
| const [SVG_TRANSFORM_UNKNOWN](../../com.aspose.html.dom.svg.datatypes/svgtransform/svg_transform_unknown/) | 单位类型不是预定义类型之一。尝试定义此类型的新值或尝试将现有值切换到此类型都是无效的。 |

### 另请参阅

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
