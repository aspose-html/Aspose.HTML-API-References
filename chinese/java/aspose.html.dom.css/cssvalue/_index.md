---
title: "CSSValue 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.css.CSSValue 类。表示简单或复杂的值。CSSValue 对象仅在 CSS 属性的上下文中出现。"
type: docs

url: /zh/java/com.aspose.html.dom.css/cssvalue/
---
## CSSValue class

表示一个简单或复合值。CSSValue 对象仅出现在 CSS 属性的上下文中。

```java
public abstract class CSSValue : DOMObject
```

## 属性

| 名称 | 描述 |
| --- | --- |
| abstract [CSSText](../../com.aspose.html.dom.css/cssvalue/csstext/) { get; set; } | `CSSValue` 接口的 cssText 属性表示当前计算的 CSS 属性值。 |
| [getCSSValueType](../../com.aspose.html.dom.css/cssvalue/cssvaluetype/) 定义该值类型的代码。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [equals](../../com.aspose.html.dom.css/cssvalue/equals/)(object) | 确定指定的 Object 是否等于此实例。 |
| [getHashCode](../../com.aspose.html.dom.css/cssvalue/gethashcode/)() | 返回此实例的哈希码。 |
| [getPlatformType](../../com.aspose.html.dom.css/cssvalue/getplatformtype/)() | 此方法用于检索 ECMAScript 对象的 Type。 |
| [toString](../../com.aspose.html.dom.css/cssvalue/toString/)() | 返回表示此实例的字符串。 |
| [operator ==](../../com.aspose.html.dom.css/cssvalue/op_equality/) |  |
| [operator !=](../../com.aspose.html.dom.css/cssvalue/op_inequality/) |  |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [CSS_CUSTOM](../../com.aspose.html.dom.css/cssvalue/css_custom/) | 该值是自定义值。 |
| const [CSS_INHERIT](../../com.aspose.html.dom.css/cssvalue/css_inherit/) | 该值是继承的，且 cssText 包含 "inherit"。 |
| const [CSS_PRIMITIVE_VALUE](../../com.aspose.html.dom.css/cssvalue/css_primitive_value/) | 该值是原始值，可以通过在此 `CSSValue` 接口实例上使用绑定特定的强制转换方法获取 CSSPrimitiveValue 接口的实例。 |
| const [CSS_VALUE_LIST](../../com.aspose.html.dom.css/cssvalue/css_value_list/) | 该值是 CSSValue 列表，并且可以通过在此 CSSValue 接口实例上使用特定绑定的强制转换方法来获取 CSSValueList 接口的实例。 |

### 另请参见

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
