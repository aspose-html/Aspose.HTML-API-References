---
title: "HTMLTableSectionElement.DeleteRow"
second_title: "Aspose.HTML for Java API 参考"
description: "HTMLTableSectionElement 方法。删除本节中的一行"
type: docs

url: /zh/java/com.aspose.html/htmltablesectionelement/deleterow/
---
## HTMLTableSectionElement.DeleteRow method

删除此节中的一行。

```java
public void DeleteRow(int index)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | Int32 | 要删除的行的索引，或使用 -1 删除最后一行。此索引从 0 开始，仅相对于本节内包含的行，而不是表中的所有行。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | INDEX_SIZE_ERR：如果指定的索引大于或等于行数，或索引是除 -1 之外的负数，则会抛出此错误。@version DOM Level 2 |

### 另请参见

* class [HTMLTableSectionElement](../)
* package [com.aspose.html](../../../com.aspose.html/)
* package [Aspose.HTML](../../../)
