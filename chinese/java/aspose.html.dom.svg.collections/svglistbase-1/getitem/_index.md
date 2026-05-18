---
title: "SVGListBase-1.GetItem"
second_title: "Aspose.HTML for Java API 参考"
description: "SVGListBase 方法。返回列表中指定的项。"
type: docs

url: /zh/java/com.aspose.html.dom.svg.collections/svglistbase-1/getitem/
---
## SVGListBase&lt;T&gt;.GetItem method

返回列表中指定的项。

```java
public T GetItem(ulong index)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | UInt64 | 要返回的列表中项的索引。第一个项的编号为 0。 |

### 返回值

选定的项。

### 异常

| 异常 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 代码 [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/)。如果索引号大于或等于 numberOfItems，则抛出。 |

### 另请参阅

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
