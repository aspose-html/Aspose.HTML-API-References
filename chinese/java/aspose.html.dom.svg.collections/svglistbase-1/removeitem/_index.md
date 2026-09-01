---
title: "SVGListBase-1.RemoveItem"
second_title: "Aspose.HTML for Java API 参考"
description: "SVGListBase 方法。从列表中移除已有的项"
type: docs

url: /zh/java/com.aspose.html.dom.svg.collections/svglistbase-1/removeitem/
---
## SVGListBase&lt;T&gt;.RemoveItem method

从列表中移除现有的项。

```java
public T RemoveItem(ulong index)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | UInt64 | 要移除的项的索引。第一个项的编号为 0。 |

### 返回值

被移除的项。

### 异常

| 异常 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 代码 [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/)。当列表无法被修改时抛出。 |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 代码 [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/)。如果索引号大于或等于 numberOfItems 时抛出。 |

### 另请参见

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
