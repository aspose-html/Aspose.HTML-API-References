---
title: "HTMLTableRowElement.DeleteCell"
second_title: "Aspose.HTML for Java API 参考"
description: "HTMLTableRowElement 方法。删除当前行中的一个单元格"
type: docs

url: /zh/java/com.aspose.html/htmltablerowelement/deletecell/
---
## HTMLTableRowElement.DeleteCell method

从当前行删除一个单元格。

```java
public void DeleteCell(int index)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | Int32 | 要删除的单元格索引，从 0 开始。如果索引为 -1，则删除行中的最后一个单元格。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR：如果指定的 `index` 大于或等于单元格数量，或 `index` 为除 -1 之外的负数，则抛出此错误。@version DOM Level 2 |

### 另请参见

* class [HTMLTableRowElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
