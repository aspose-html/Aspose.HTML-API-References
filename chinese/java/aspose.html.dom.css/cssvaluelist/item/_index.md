---
title: "CSSValueList.Item"
second_title: "Aspose.HTML for Java API 参考"
description: "CSSValueList 属性。CSSValueList 接口的 item 方法用于通过顺序索引检索 CSSValue。"
type: docs

url: /zh/java/com.aspose.html.dom.css/cssvaluelist/item/
---
## CSSValueList indexer

CSSValueList 接口的 item() 方法用于通过顺序索引检索 CSSValue。

此集合中的顺序对应 CSS 样式属性中值的顺序。如果索引大于或等于列表中的值数量，此方法返回 null。

```java
public CSSValue this[int index] { get; }
```

### 返回值

CSSValueList 中索引位置的 CSSValue 对象，如果不是有效索引则返回 null。

### Property Value

一个无符号长整数，表示集合中 CSS 值的索引。

### 另请参见

* class [CSSValue](../../cssvalue/)
* class [CSSValueList](../)
* package [com.aspose.html.dom.css](../../../com.aspose.html.dom.css/)
* package [Aspose.HTML](../../../)
