---
title: ParentNode
second_title: Aspose.HTML for .NET API Reference
description: 
type: docs
weight: 60
url: /net/aspose.html.dom.traversal/itreewalker/parentnode/
---
## ITreeWalker.ParentNode method

Moves to and returns the closest visible ancestor node of the current node. If the search for parentNode attempts to step upward from the TreeWalker's root node, or if it fails to find a visible ancestor node, this method retains the current position and returns null.

```csharp
public Node ParentNode()
```

## Return Value

The new parent node, or null if the current node has no parent in the TreeWalker's logical view.

### See Also

* class [Node](../../../aspose.html.dom/node)
* interface [ITreeWalker](../../itreewalker)
* namespace [Aspose.Html.Dom.Traversal](../../itreewalker)
* assembly [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->