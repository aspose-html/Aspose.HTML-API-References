---
title: SyntaxNodeCollectionT Class
second_title: Aspose.HTML for .NET API Reference
description: Aspose.Html.Toolkit.Markdown.Syntax.SyntaxNodeCollection1T class. Represents a collection of syntax nodes
type: docs
weight: 5810
url: /net/aspose.html.toolkit.markdown.syntax/syntaxnodecollection-1/
---
## SyntaxNodeCollection<T> class

Represents a collection of syntax nodes.

```csharp
public class SyntaxNodeCollection<T> : NodeList<T>, IList<T>
    where T : MarkdownSyntaxNode
```

| Parameter | Description |
| --- | --- |
| T | The type of the collection values. |

## Constructors

| Name | Description |
| --- | --- |
| [SyntaxNodeCollection](syntaxnodecollection/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| override [Count](../../aspose.html.toolkit.markdown.syntax/syntaxnodecollection-1/count/) { get; } | Gets the number of values in the collection. |
| [IsReadOnly](../../aspose.html.toolkit.markdown.syntax/syntaxnodecollection-1/isreadonly/) { get; } | Get the readonly flag. |
| [Item](../../aspose.html.toolkit.markdown.syntax/syntaxnodecollection-1/item/) { get; set; } | Gets or sets the value at the given index. |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../aspose.html.toolkit.markdown.syntax/syntaxnodecollection-1/add/)(*T*) | Adds the given item to the collection. |
| [Clear](../../aspose.html.toolkit.markdown.syntax/syntaxnodecollection-1/clear/)() | Removes all items from the collection. |
| [Contains](../../aspose.html.toolkit.markdown.syntax/syntaxnodecollection-1/contains/)(*T*) | Determines whether the given item exists in the collection. |
| [CopyTo](../../aspose.html.toolkit.markdown.syntax/syntaxnodecollection-1/copyto/)(*T[], int*) |  |
| override [Get](../../aspose.html.toolkit.markdown.syntax/syntaxnodecollection-1/get/)(*int*) | Gets the item at the given index. |
| override [GetEnumerator](../../aspose.html.toolkit.markdown.syntax/syntaxnodecollection-1/getenumerator/)() | Gets the values in the collection. |
| [IndexOf](../../aspose.html.toolkit.markdown.syntax/syntaxnodecollection-1/indexof/)(*T*) | Gets the index of the given item. |
| [Insert](../../aspose.html.toolkit.markdown.syntax/syntaxnodecollection-1/insert/)(*int, T*) | Inserts the given item at the specified index. |
| [Remove](../../aspose.html.toolkit.markdown.syntax/syntaxnodecollection-1/remove/)(*T*) | Removes the item from the collection. |
| [RemoveAt](../../aspose.html.toolkit.markdown.syntax/syntaxnodecollection-1/removeat/)(*int*) | Removes the item at the given index. |
| [WriteTo](../../aspose.html.toolkit.markdown.syntax/nodelist-1/writeto/)(*TextWriter*) |  |

### See Also

* class [NodeList&lt;T&gt;](../nodelist-1/)
* class [MarkdownSyntaxNode](../markdownsyntaxnode/)
* namespace [Aspose.Html.Toolkit.Markdown.Syntax](../../aspose.html.toolkit.markdown.syntax/)
* assembly [Aspose.HTML](../../)
