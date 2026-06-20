---
title: "SVGListBaseT 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.svg.collections.SVGListBase1T 类。此接口定义所有 SVG 列表的基础列表"
type: docs

url: /zh/java/com.aspose.html.dom.svg.collections/svglistbase-1/
---
## SVGListBase&lt;T&gt; class

此接口定义了所有 SVG 列表的基础列表。

```java
public abstract class SVGListBase<T> : SVGValueType, IEnumerable<T>
```

| 参数 | 描述 |
| --- | --- |
| T | 列表中存储的项的类型。 |

## 属性

| 名称 | 描述 |
| --- | --- |
[getItem]
[setItem] Returns the indexth item in the list. |
| [getLength](../../com.aspose.html.dom.svg.collections/svglistbase-1/length/) 列表中项的数量。 |
| [getNumberOfItems](../../com.aspose.html.dom.svg.collections/svglistbase-1/numberofitems/) 列表中项的数量。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [appendItem](../../com.aspose.html.dom.svg.collections/svglistbase-1/appenditem/)(T) | 在列表末尾插入一个新项。 |
| [clear](../../com.aspose.html.dom.svg.collections/svglistbase-1/clear/)() | 清除列表中所有现有的当前项，结果是一个空列表。 |
| [dispose](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/dispose/)() | 释放非托管资源以及（可选的）托管资源。 |
| [getEnumerator](../../com.aspose.html.dom.svg.collections/svglistbase-1/getenumerator/)() | 获取枚举器。 |
| [getItem](../../com.aspose.html.dom.svg.collections/svglistbase-1/getitem/)(ulong) | 返回列表中指定的项。 |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | 此方法用于检索 ECMAScript 对象。 |
| [initialize](../../com.aspose.html.dom.svg.collections/svglistbase-1/initialize/)(T) | 清除列表中所有现有的当前项，并重新初始化列表以容纳参数指定的单个项。 |
| [insertItemBefore](../../com.aspose.html.dom.svg.collections/svglistbase-1/insertitembefore/)(T, ulong) | 在指定位置向列表插入一个新项。第一个项的编号为 0。 |
| [removeItem](../../com.aspose.html.dom.svg.collections/svglistbase-1/removeitem/)(ulong) | 从列表中移除现有的项。 |
| [replaceItem](../../com.aspose.html.dom.svg.collections/svglistbase-1/replaceitem/)(T, ulong) | 用新项替换列表中现有的项。 |

### 另请参见

* class [SVGValueType](../../com.aspose.html.dom.svg.datatypes/svgvaluetype/)
* package [com.aspose.html.dom.svg.collections](../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../)
