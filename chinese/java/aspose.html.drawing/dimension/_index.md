---
title: "Dimension 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.drawing.Dimension 类。提供维度的基类。一般术语维度指带有单位的数值，并由 UnitType 表示。"
type: docs

url: /zh/java/com.aspose.html.drawing/dimension/
---
## Dimension class

提供维度的基类。一般术语 'dimension' 指带有单位的数值，并由 [`UnitType`](../unittype/) 表示。

```java
public abstract class Dimension : Numeric
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getUnitType](../../com.aspose.html.drawing/unit/unittype/) 获取 [`Unit`](../unit/) 的单位类型。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [compareTo](../../com.aspose.html.drawing/numeric/compareto/)(Numeric) | 比较当前实例与同类型的另一个对象，并返回一个整数，指示当前实例是在排序顺序中位于另一个对象之前、之后，还是相同位置。 |
| [equals](../../com.aspose.html.drawing/unit/equals/)(object) | 确定指定的 Object 是否等于此实例。 |
| [equals](../../com.aspose.html.drawing/numeric/equals/)(Unit) | 确定指定的 [`Unit`](../unit/) 是否等于此实例。 |
| [getHashCode](../../com.aspose.html.drawing/numeric/gethashcode/)() | 返回此实例的哈希码。 |
| [getValue](../../com.aspose.html.drawing/numeric/getvalue/)() | 获取单位值。 |
| [getValue](../../com.aspose.html.drawing/numeric/getvalue/)(UnitType) | 获取转换为指定的 [`UnitType`](../unittype/) 的值。 |
| [toString](../../com.aspose.html.drawing/dimension/toString/)() | 返回表示此实例的字符串。 |

### 另请参见

* class [Unit](../unit/)
* class [Numeric](../numeric/)
* package [com.aspose.html.drawing](../../com.aspose.html.drawing/)
* package [Aspose.HTML](../../)
