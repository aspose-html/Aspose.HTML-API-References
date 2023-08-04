---
title: NodeListT Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.Toolkit.Markdown.Syntax.NodeList1T class. Base implementation of the NodeList
type: docs
weight: 5280
url: /java/com.aspose.html.toolkit.markdown.syntax/nodelist-1/
---
## NodeList&lt;T&gt; class

Base implementation of the NodeList.

```java
public abstract class NodeList<T> : IEnumerable<T>, IWritable
    where T : MarkdownSyntaxNode
```

| Parameter | Description |
| --- | --- |
| T | The T type. |

## Properties

| Name | Description |
| --- | --- |
| abstract [getCount](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/count/) Gets the number of node in the list. |

## Methods

| Name | Description |
| --- | --- |
| abstract [Get](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/get/)(int) | Gets the node at the given index. |
| abstract [GetEnumerator](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/getenumerator/)() | Gets the nodes in the collection. |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/nodelist-1/writeto/)(TextWriter) | Write nodes to text writer. |

### See Also

* interface [IWritable](../iwritable/)
* class [MarkdownSyntaxNode](../markdownsyntaxnode/)
* package [com.aspose.html.Toolkit.Markdown.Syntax](../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../)
