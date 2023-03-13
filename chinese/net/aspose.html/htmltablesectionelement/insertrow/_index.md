---
title: HTMLTableSectionElement.InsertRow
second_title: Aspose.HTML for .NET API 参考
description: HTMLTableSectionElement 方法. 在此部分中插入一行新行立即插入当前行之前 指数本节第 th 行如果 指数是 1 或等于此 部分中的行数则追加新行
type: docs
weight: 70
url: /zh/net/aspose.html/htmltablesectionelement/insertrow/
---
## HTMLTableSectionElement.InsertRow method

在此部分中插入一行。新行立即插入当前行之前 `指数`本节第 th 行。如果 `指数`是 -1 或等于此 部分中的行数，则追加新行。

```csharp
public HTMLElement InsertRow(int index)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | Int32 | 插入新行的行号。这个索引 从 0 开始，并且只与 这个部分中包含的行相关，而不是表中的所有行。 |

### 返回值

新创建的行。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR：如果指定索引大于 行数则引发，如果索引是负数而不是 -1. @version DOM Level 2 |

### 也可以看看

* class [HTMLElement](../../htmlelement/)
* class [HTMLTableSectionElement](../)
* 命名空间 [Aspose.Html](../../htmltablesectionelement/)
* 部件 [Aspose.HTML](../../../)


