---
title: "HTMLTableElement.DeleteRow"
second_title: "Aspose.HTML for Java API 参考"
description: "HTMLTableElement 方法。删除表格行"
type: docs

url: /zh/java/com.aspose.html/htmltableelement/deleterow/
---
## HTMLTableElement.DeleteRow method

删除表格行。

```java
public void DeleteRow(int index)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | Int32 | 要删除的行的索引。该索引从 0 开始，并相对于表格内所有行的逻辑顺序（而非文档顺序）。如果索引为 -1，则删除表格中的最后一行。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR：如果指定的索引大于或等于行数，或索引是除 -1 之外的负数，则抛出此错误。@version DOM Level 2 |

### 另请参阅

* class [HTMLTableElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
