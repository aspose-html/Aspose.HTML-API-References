---
title: Node.TextContent
second_title: Aspose.HTML for .NET API Reference
description: Node TextContent property. Represents the text content of the node and its descendants
type: docs
weight: 160
url: /net/aspose.html.dom/node/textcontent/
---
## Node.TextContent property

Represents the text content of the node and its descendants.

```csharp
public virtual string TextContent { get; set; }
```

### Property Value

A string, or null. Its value depends on the situation:

If the node is a document or a doctype, `TextContent` returns null.Note: To get all the text and CDATA data for the whole document, use

```csharp
document.DocumentElement.TextContent
```

.If the node is a CDATA section, a comment, a processing instruction, or a text node, `TextContent` returns, or sets, the text inside the node, i.e., the [`NodeValue`](../nodevalue/).For other node types, `TextContent` returns the concatenation of the `TextContent` of every child node, excluding comments and processing instructions.

## Remarks

Reference:

[DOM Standard](https://dom.spec.whatwg.org/#dom-node-textcontent).

### See Also

* class [Node](../)
* namespace [Aspose.Html.Dom](../../../aspose.html.dom/)
* assembly [Aspose.HTML](../../../)
