---
title: Class CSSValueList
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Css.CSSValueList 班级. CSSValueList 接口提供了 CSS 值有序集合的抽象
type: docs
weight: 350
url: /zh/net/aspose.html.dom.css/cssvaluelist/
---
## CSSValueList class

CSSValueList 接口提供了 CSS 值有序集合的抽象。

```csharp
public class CSSValueList : CSSValue, ICSSValueList, IEnumerable<CSSValue>
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [CSSValueList](cssvaluelist/#constructor)() | 初始化一个新的实例`CSSValueList`类. |
| [CSSValueList](cssvaluelist/#constructor_1)(params CSSValue[]) | 初始化一个新的实例`CSSValueList`类. |
| [CSSValueList](cssvaluelist/#constructor_2)(IEnumerable&lt;CSSValue&gt;) | 初始化一个新的实例`CSSValueList`类. |

## 特性

| 姓名 | 描述 |
| --- | --- |
| override [CSSText](../../aspose.html.dom.css/cssvaluelist/csstext/) { get; set; } | 当前值的字符串表示。 |
| [CSSValueType](../../aspose.html.dom.css/cssvalue/cssvaluetype/) { get; } | 定义值类型的代码。 |
| [Item](../../aspose.html.dom.css/cssvaluelist/item/) { get; } | 获取[`CSSValue`](../cssvalue/)在指定的索引处. |
| [Length](../../aspose.html.dom.css/cssvaluelist/length/) { get; } | 列表中 CSSValues 的数量。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Equals](../../aspose.html.dom.css/cssvalue/equals/)(object) | 判断指定的是否Object等于这个实例. |
| [GetEnumerator](../../aspose.html.dom.css/cssvaluelist/getenumerator/)() | 返回一个遍历集合的枚举器。 |
| override [GetHashCode](../../aspose.html.dom.css/cssvalue/gethashcode/)() | 返回此实例的哈希码。 |
| override [GetPlatformType](../../aspose.html.dom.css/cssvaluelist/getplatformtype/)() | 此方法用于检索 ECMAScript 对象Type. |
| override [ToString](../../aspose.html.dom.css/cssvalue/tostring/)() | 返回一个String代表这个实例. |

### 也可以看看

* class [CSSValue](../cssvalue/)
* interface [ICSSValueList](../icssvaluelist/)
* 命名空间 [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* 部件 [Aspose.HTML](../../)


