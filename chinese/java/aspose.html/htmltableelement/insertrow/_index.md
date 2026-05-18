---
title: "HTMLTableElement.InsertRow"
second_title: "Aspose.HTML for Java API 参考"
description: "HTMLTableElement 方法。向表格中插入一个新的空行。新行会立即插入在表格中当前第 index 行之前，并位于同一节中。如果 index 为 -1 或等于行数，则在表格末尾追加新行。此外，当表格为空时，行会插入到一个已创建并插入表格的 TBODY 中。根据 HTML 4.01，表格行不能为空。"
type: docs

url: /zh/java/com.aspose.html/htmltableelement/insertrow/
---
## HTMLTableElement.InsertRow method

在表格中插入一个新的空行。新行会立即插入在当前第 `index` 行之前，并位于同一节中。如果 `index` 为 -1 或等于行数，则在表格末尾追加新行。此外，当表格为空时，行会插入到一个新创建并插入表格的 `TBODY` 中。根据 [[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224)]，表格行不能为空。

```java
public Node InsertRow(int index)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | Int32 | 要插入新行的行号。此索引从 0 开始，并相对于表格内部所有行的逻辑顺序（而非文档顺序）。 |

### 返回值

新创建的行。

### 异常

| 异常 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR：如果指定的索引大于行数，或索引是除 -1 之外的负数，则会抛出此错误。 @version DOM Level 2 |

### 另请参阅

* class [Node](../../../com.aspose.html.dom/node/)
* class [HTMLTableElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
