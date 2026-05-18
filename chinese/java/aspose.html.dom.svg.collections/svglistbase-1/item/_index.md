---
title: "SVGListBase-1.Item"
second_title: "Aspose.HTML for Java API 参考"
description: "SVGListBase 属性。返回列表中第 index 项。"
type: docs

url: /zh/java/com.aspose.html.dom.svg.collections/svglistbase-1/item/
---
## SVGListBase&lt;T&gt; indexer

返回列表中第 index 项。

```java
public T this[ulong index] { get; set; }
```

| 参数 | 描述 |
| --- | --- |
| index | 列表中的索引。 |

### 返回值

列表中第 index 位置存储的对象。

### Property Value

列表中存储的项的类型。

### 异常

| 异常 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 代码 [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/)。当列表无法被修改时抛出。 |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 代码 [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/)。如果索引号大于或等于 numberOfItems，则抛出。 |

### 另请参阅

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
