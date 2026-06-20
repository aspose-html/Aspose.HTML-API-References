---
title: "ICSSValueList 接口"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.css.ICSSValueList 接口。CSSValueList 接口继承自 CSSValue 接口，并提供 CSS 值有序集合的抽象。"
type: docs

url: /zh/java/com.aspose.html.dom.css/icssvaluelist/
---
## ICSSValueList interface

CSSValueList 接口继承自 [`CSSValue`](../cssvalue/) 接口，并提供 CSS 值有序集合的抽象。

某些属性在语法中允许空列表。在这种情况下，这些属性使用 none 标识符。因此，空列表表示该属性的值为 none。

CSSValueList 中的项可通过整数索引访问，起始索引为 0。

```java
public interface ICSSValueList
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getItem](../../com.aspose.html.dom.css/icssvaluelist/item/) 此方法用于通过序数索引检索 CSSValue。此集合中的顺序对应 CSS 样式属性中值的顺序。如果索引大于或等于列表中值的数量，则返回 null。 |
| [getLength](../../com.aspose.html.dom.css/icssvaluelist/length/) CSSValueList 接口的 length 只读属性表示列表中 CSSValue 的数量。索引的有效取值范围为 0 到 length-1（含）。 |

## 备注

该接口曾是创建类型化 CSS 对象模型的尝试的一部分。此尝试已被放弃，且大多数浏览器未实现它。

要实现您的目的，您可以使用：

未类型化的 [CSS Object Model](https://drafts.csswg.org/cssom/)，得到广泛支持，或现代的 [CSS Typed Object Model API](https://drafts.css-houdini.org/css-typed-om/#stylevalue-objects)，支持较少且被视为实验性。

### 另请参见

* package [com.aspose.html.dom.css](../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../)
