---
title: HTMLTableElement.InsertRow
second_title: Aspose.HTML for .NET API 参考
description: HTMLTableElement 方法. 在表中插入一个新的空行新行被插入 紧接在当前 之前并与当前 在同一部分指数表中的第行如果指数是 1 或 等于行数则追加新行此外 当表为空时该行被插入到身体 创建并插入到表中根据 表行不能为 空HTML 4.01.
type: docs
weight: 220
url: /zh/net/aspose.html/htmltableelement/insertrow/
---
## HTMLTableElement.InsertRow method

在表中插入一个新的空行。新行被插入 紧接在当前 之前并与当前 在同一部分`指数`表中的第行。如果`指数`是 -1 或 等于行数，则追加新行。此外， 当表为空时，该行被插入到`身体` 创建并插入到表中。根据 [，表行不能为 空[HTML 4.01](http://www.w3.org/TR/1999/REC-html401-19991224)].

```csharp
public Node InsertRow(int index)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| index | Int32 | 插入新行的行号。这个索引 从 0 开始，并且是相对于表中包含的所有行的逻辑顺序（不是文档 顺序）。 |

### 返回值

新创建的行。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | INDEX_SIZE_ERR：如果指定的索引大于 行数，或者索引是负数而不是 -1. @version DOM 级别 2，则引发 |

### 也可以看看

* class [Node](../../../aspose.html.dom/node/)
* class [HTMLTableElement](../)
* 命名空间 [Aspose.Html](../../htmltableelement/)
* 部件 [Aspose.HTML](../../../)


