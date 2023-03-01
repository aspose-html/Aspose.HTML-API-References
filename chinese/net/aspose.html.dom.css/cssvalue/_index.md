---
title: Class CSSValue
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Css.CSSValue 班级. 表示简单值或复杂值 CSSValue 对象仅出现在 CSS 属性的上下文中
type: docs
weight: 340
url: /zh/net/aspose.html.dom.css/cssvalue/
---
## CSSValue class

表示简单值或复杂值。 CSSValue 对象仅出现在 CSS 属性的上下文中。

```csharp
public abstract class CSSValue : DOMObject
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| abstract [CSSText](../../aspose.html.dom.css/cssvalue/csstext/) { get; set; } | 当前值的字符串表示。 |
| [CSSValueType](../../aspose.html.dom.css/cssvalue/cssvaluetype/) { get; } | 定义值类型的代码。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Equals](../../aspose.html.dom.css/cssvalue/equals/)(object) | 判断指定的是否Object等于这个实例. |
| override [GetHashCode](../../aspose.html.dom.css/cssvalue/gethashcode/)() | 返回此实例的哈希码。 |
| override [GetPlatformType](../../aspose.html.dom.css/cssvalue/getplatformtype/)() | 此方法用于检索 ECMAScript 对象Type. |
| override [ToString](../../aspose.html.dom.css/cssvalue/tostring/)() | 返回一个String代表这个实例. |
| [operator ==](../../aspose.html.dom.css/cssvalue/op_equality/) | 实现运算符 ==. |
| [operator !=](../../aspose.html.dom.css/cssvalue/op_inequality/) | 实现运算符 !=. |

## 字段

| 姓名 | 描述 |
| --- | --- |
| const [CSS_CUSTOM](../../aspose.html.dom.css/cssvalue/css_custom/) | 该值为自定义值。 |
| const [CSS_INHERIT](../../aspose.html.dom.css/cssvalue/css_inherit/) | 值被继承，cssText包含“inherit”. |
| const [CSS_PRIMITIVE_VALUE](../../aspose.html.dom.css/cssvalue/css_primitive_value/) | 该值是原始值，可以通过在 CSSValue 接口的这个实例上使用特定于绑定的转换方法来获得 CSSPrimitiveValue 接口的实例。 |
| const [CSS_VALUE_LIST](../../aspose.html.dom.css/cssvalue/css_value_list/) | 该值是一个 CSSValue 列表，可以通过在 CSSValue 接口的这个实例上使用特定于绑定的转换方法来获取 CSSValueList 接口的实例。 |

### 也可以看看

* class [DOMObject](../../aspose.html.dom/domobject/)
* 命名空间 [Aspose.Html.Dom.Css](../../aspose.html.dom.css/)
* 部件 [Aspose.HTML](../../)


