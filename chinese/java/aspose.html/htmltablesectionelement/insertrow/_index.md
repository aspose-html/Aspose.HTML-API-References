---
title: "HTMLTableSectionElement.InsertRow"
second_title: "Aspose.HTML for Java API 参考"
description: "HTMLTableSectionElement 方法。向此节插入一行。新行会立即插入到此节中当前第 index 行之前。如果 index 为 -1 或等于此节中的行数，则在末尾追加新行。"
type: docs

url: /zh/java/com.aspose.html/htmltablesectionelement/insertrow/
---
## HTMLTableSectionElement.InsertRow method

在此节中插入一行。新行会立即插入到当前第 `index` 行之前。如果 `index` 为 -1 或等于此节中的行数，则在末尾追加新行。

```java
public HTMLElement InsertRow(int index)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | Int32 | 要插入新行的行号。此索引从 0 开始，仅相对于此节内部包含的行，而不是表中的所有行。 |

### 返回值

新创建的行。

### 异常

| 异常 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR：如果指定的索引大于行数，或索引是除 -1 之外的负数，则抛出此错误。@version DOM Level 2 |

### 另请参阅

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableSectionElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
