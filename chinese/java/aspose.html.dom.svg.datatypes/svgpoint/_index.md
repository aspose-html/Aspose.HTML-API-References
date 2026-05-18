---
title: "SVGPoint 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.svg.datatypes.SVGPoint 类。许多 SVG DOM 接口引用 SVGPoint 类的对象。SVGPoint 是一个 x y 坐标对。当在矩阵运算中使用时，SVGPoint 被视为形式为 x y 1 的向量。如果 SVGRect 对象被标记为只读，则尝试为其属性赋值将导致抛出异常。"
type: docs

url: /zh/java/com.aspose.html.dom.svg.datatypes/svgpoint/
---
## SVGPoint class

许多 SVG DOM 接口引用类 SVGPoint 的对象。SVGPoint 是一个 (x, y) 坐标对。在矩阵运算中，SVGPoint 被视为形式为 [x] [y] [1] 的向量。如果 SVGRect 对象被指定为只读，则尝试为其属性赋值将抛出异常。

```java
public class SVGPoint : SVGValueType
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [X](../../com.aspose.html.dom.svg.datatypes/svgpoint/x/) { get; set; } | X 坐标。 |
| [Y](../../com.aspose.html.dom.svg.datatypes/svgpoint/y/) { get; set; } | Y 坐标。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | 释放非托管资源以及（可选的）托管资源。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象。 |
| [matrixTransform](../../com.aspose.html.dom.svg.datatypes/svgpoint/matrixtransform/)(SVGMatrix) | 对该 SVGPoint 对象应用 2x3 矩阵变换，并返回一个新的、已变换的 SVGPoint 对象：newpoint = matrix* thispoint |
| [toString](../../com.aspose.html.dom.svg.datatypes/svgpoint/toString/)() | 返回表示此实例的字符串。 |

### 另请参阅

* class [SVGValueType](../svgvaluetype/)
* package [com.aspose.html.dom.svg.datatypes](../../com.aspose.html.dom.svg.datatypes/)
* package [Aspose.HTML](../../)
