---
title: Class Dimension
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Drawing.Dimension 班级. 提供维度的基类 通用术语维度指的是附有单位的数字并表示为UnitType.
type: docs
weight: 2660
url: /zh/net/aspose.html.drawing/dimension/
---
## Dimension class

提供维度的基类。 通用术语“维度”指的是附有单位的数字，并表示为[`UnitType`](../unittype/).

```csharp
public abstract class Dimension : Numeric
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [UnitType](../../aspose.html.drawing/unit/unittype/) { get; } | 获取单位类型[`Unit`](../unit/). |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [CompareTo](../../aspose.html.drawing/numeric/compareto/)(Numeric) | 将当前实例与另一个相同类型的对象进行比较，并返回一个整数，该整数指示当前实例是否在排序顺序中与另一个对象之前、之后或出现在相同位置。 |
| override [Equals](../../aspose.html.drawing/unit/equals/)(object) | 判断指定的是否Object 等于这个实例. |
| override [Equals](../../aspose.html.drawing/numeric/equals/)(Unit) | 判断指定的是否[`Unit`](../unit/) 等于这个实例. |
| override [GetHashCode](../../aspose.html.drawing/numeric/gethashcode/)() | 返回此实例的哈希码。 |
| [GetValue](../../aspose.html.drawing/numeric/getvalue/)() | 获取单位值。 |
| [GetValue](../../aspose.html.drawing/numeric/getvalue/)(UnitType) | 获取转换为指定的值[`UnitType`](../unittype/). |
| override [ToString](../../aspose.html.drawing/dimension/tostring/)() | 返回一个String代表这个实例. |

### 也可以看看

* class [Unit](../unit/)
* class [Numeric](../numeric/)
* 命名空间 [Aspose.Html.Drawing](../../aspose.html.drawing/)
* 部件 [Aspose.HTML](../../)


