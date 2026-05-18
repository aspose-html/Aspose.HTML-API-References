---
title: "ICSSValueList.Item"
second_title: "Aspose.HTML for Java API 参考"
description: "ICSSValueList 属性。此方法用于通过序数索引检索 CSSValue。集合中的顺序对应 CSS 样式属性中值的顺序。如果索引大于或等于列表中值的数量，则返回 null。"
type: docs

url: /zh/java/com.aspose.html.dom.css/icssvaluelist/item/
---
## ICSSValueList indexer

此方法用于通过序数索引检索 CSSValue。此集合中的顺序表示 CSS 样式属性中值的顺序。如果索引大于或等于列表中值的数量，则返回 null。

另请参阅 [CSSOM](https://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113/css.html#CSS-CSSValueList)[#CSSValueList](https://www.w3.org/TR/2000/REC-DOM-Level-2-Style-20001113/css.html#CSS-CSSValueList)。

```java
public CSSValue this[int index] { get; }
```

### 返回值

在 [`CSSValue`](../../cssvalue/) 位于 [`CSSValueList`](../../cssvaluelist/) 中的索引位置，若不是有效索引则返回 null。

### Property Value

集合中的索引。

## 备注

此特性最初在 [DOM Style Level 2](https://www.w3.org/TR/DOM-Level-2-Style) 规范中定义，但此后已从所有标准化工作中移除。

它已被现代但不兼容的 [CSS Typed Object Model API](https://developer.mozilla.org/en-US/docs/Web/API/CSS_Typed_OM_API) 取代，该 API 现已进入标准化轨道。

### 另请参阅

* class [CSSValue](../../cssvalue/)
* interface [ICSSValueList](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
