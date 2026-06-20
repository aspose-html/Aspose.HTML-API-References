---
title: "HTMLTableRowElement.InsertCell"
second_title: "Aspose.HTML for Java API 参考"
description: "HTMLTableRowElement 方法。向此行插入一个空的 TD 单元格。如果 index 为 -1 或等于单元格数量，则在末尾追加新单元格"
type: docs

url: /zh/java/com.aspose.html/htmltablerowelement/insertcell/
---
## HTMLTableRowElement.InsertCell method

在此行插入一个空的 `TD` 单元格。如果 `index` 为 -1 或等于单元格数量，则在末尾追加新单元格。

```java
public HTMLElement InsertCell(int index)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | Int32 | 插入单元格的位置，从 0 开始。 |

### 返回值

新创建的单元格。

### 异常

| 异常 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR：如果指定的 `index` 大于单元格数量，或 `index` 为除 -1 之外的负数，则抛出此错误。@version DOM Level 2 |

### 另请参见

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableRowElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
