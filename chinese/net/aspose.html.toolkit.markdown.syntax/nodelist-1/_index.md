---
title: Class NodeListT
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Toolkit.Markdown.Syntax.NodeList1T 班级. NodeList 的基本实现
type: docs
weight: 5280
url: /zh/net/aspose.html.toolkit.markdown.syntax/nodelist-1/
---
## NodeList&lt;T&gt; class

NodeList 的基本实现。

```csharp
public abstract class NodeList<T> : IEnumerable<T>, IWritable
    where T : MarkdownSyntaxNode
```

| 范围 | 描述 |
| --- | --- |
| T | T型。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| abstract [Count](../../aspose.html.toolkit.markdown.syntax/nodelist-1/count/) { get; } | 获取列表中的节点数。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| abstract [Get](../../aspose.html.toolkit.markdown.syntax/nodelist-1/get/)(int) | 获取给定索引处的节点。 |
| abstract [GetEnumerator](../../aspose.html.toolkit.markdown.syntax/nodelist-1/getenumerator/)() | 获取集合中的节点。 |
| [WriteTo](../../aspose.html.toolkit.markdown.syntax/nodelist-1/writeto/)(TextWriter) | 将节点写入文本编写器。 |

### 也可以看看

* interface [IWritable](../iwritable/)
* class [MarkdownSyntaxNode](../markdownsyntaxnode/)
* 命名空间 [Aspose.Html.Toolkit.Markdown.Syntax](../../aspose.html.toolkit.markdown.syntax/)
* 部件 [Aspose.HTML](../../)


