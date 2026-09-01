---
title: "SVGListBase-1.InsertItemBefore"
second_title: "Aspose.HTML for Java API 参考"
description: "SVGListBase 方法。在列表中指定位置插入一个新项。第一个项的编号为 0"
type: docs

url: /zh/java/com.aspose.html.dom.svg.collections/svglistbase-1/insertitembefore/
---
## SVGListBase&lt;T&gt;.InsertItemBefore method

在指定位置向列表插入一个新项。第一个项的编号为 0。

```java
public T InsertItemBefore(T newItem, ulong index)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| newItem | T | 要插入列表的项。 |
| index | UInt64 | 要在其前插入新项的项的索引。第一个项的编号为 0。如果索引等于 0，则新项插入到列表的前端。如果索引大于或等于 numberOfItems，则新项追加到列表末尾。 |

### 返回值

插入的项。

### 异常

| 异常 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | 代码 [`NO_MODIFICATION_ALLOWED_ERR`](../../../com.aspose.html.dom/domexception/no_modification_allowed_err/)。当列表无法被修改时抛出。 |

### 另请参见

* class [SVGListBase&lt;T&gt;](../)
* package [com.aspose.html.dom.svg.collections](../../../com.aspose.html.dom.svg.collections/)
* package [Aspose.HTML](../../../)
