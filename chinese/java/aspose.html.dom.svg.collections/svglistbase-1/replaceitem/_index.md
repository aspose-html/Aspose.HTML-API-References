---
title: "SVGListBase-1.ReplaceItem"
second_title: "Aspose.HTML for Java API 参考"
description: "SVGListBase 方法。用新项替换列表中现有的项"
type: docs

url: /zh/java/com.aspose.html.dom.svg.collections/svglistbase-1/replaceitem/
---
## SVGListBase&lt;T&gt;.ReplaceItem method

用新项替换列表中现有的项。

```java
public T ReplaceItem(T newItem, ulong index)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newItem | T | 要插入列表的项。 |
| index | UInt64 | 要替换的项目的索引。第一个项目的编号为 0。 |

### 返回值

被插入的项目。

### 异常

| 异常 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 代码 [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/)。当列表无法被修改时抛出。 |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 代码 [`INDEX_SIZE_ERR`](../../../com.aspose.html.dom/domexception/index_size_err/)。如果索引号大于或等于 numberOfItems，则抛出。 |

### 另请参阅

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
