---
title: NodeListT Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Toolkit.Markdown.Syntax.NodeList1T class. Base implementation of the NodeList
type: docs
weight: 5530
url: /net/aspose.html.toolkit.markdown.syntax/nodelist-1/
---
## NodeList&lt;T&gt; class

Base implementation of the NodeList.

```csharp
public abstract class NodeList<T> : IEnumerable<T>, IWritable
    where T : MarkdownSyntaxNode
```

| Parameter | Description |
| --- | --- |
| T | The T type. |

## Properties

| Name | Description |
| --- | --- |
| abstract [Count](../../aspose.html.toolkit.markdown.syntax/nodelist-1/count/) { get; } | Gets the number of node in the list. |

## Methods

| Name | Description |
| --- | --- |
| abstract [Get](../../aspose.html.toolkit.markdown.syntax/nodelist-1/get/)(int) | Gets the node at the given index. |
| abstract [GetEnumerator](../../aspose.html.toolkit.markdown.syntax/nodelist-1/getenumerator/)() | Gets the nodes in the collection. |
| [WriteTo](../../aspose.html.toolkit.markdown.syntax/nodelist-1/writeto/)(TextWriter) | Write nodes to text writer. |

### See Also

* interface [IWritable](../iwritable/)
* class [MarkdownSyntaxNode](../markdownsyntaxnode/)
* namespace [Aspose.Html.Toolkit.Markdown.Syntax](../../aspose.html.toolkit.markdown.syntax/)
* assembly [Aspose.HTML](../../)
