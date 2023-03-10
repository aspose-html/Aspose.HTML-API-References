---
title: IDocumentTraversal.CreateTreeWalker
second_title: Aspose.HTML for .NET API Reference
description: IDocumentTraversal method. Create a new TreeWalker over the subtree rooted at the specified node
type: docs
weight: 20
url: /net/aspose.html.dom.traversal/idocumenttraversal/createtreewalker/
---
## CreateTreeWalker(Node) {#createtreewalker}

Create a new TreeWalker over the subtree rooted at the specified node.

```csharp
public ITreeWalker CreateTreeWalker(Node root)
```

| Parameter | Type | Description |
| --- | --- | --- |
| root | Node | node which will serve as the root for the TreeWalker. The whatToShow flags and the NodeFilter are not considered when setting this value; any node type will be accepted as the root. The currentNode of the TreeWalker is initialized to this node, whether or not it is visible. The root functions as a stopping point for traversal methods that look upward in the document structure, such as parentNode and nextNode. The root must not be null. |

### Return Value

The newly created TreeWalker.

### See Also

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* assembly [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long) {#createtreewalker_1}

Create a new TreeWalker over the subtree rooted at the specified node.

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| Parameter | Type | Description |
| --- | --- | --- |
| root | Node | node which will serve as the root for the TreeWalker. The whatToShow flags and the NodeFilter are not considered when setting this value; any node type will be accepted as the root. The currentNode of the TreeWalker is initialized to this node, whether or not it is visible. The root functions as a stopping point for traversal methods that look upward in the document structure, such as parentNode and nextNode. The root must not be null. |
| whatToShow | Int64 | flag specifies which node types may appear in the logical view of the tree presented by the tree-walker. See the description of NodeFilter for the set of possible SHOW_ values.These flags can be combined using OR. |

### Return Value

The newly created TreeWalker.

### See Also

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* assembly [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long, INodeFilter) {#createtreewalker_2}

Create a new TreeWalker over the subtree rooted at the specified node.

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| Parameter | Type | Description |
| --- | --- | --- |
| root | Node | node which will serve as the root for the TreeWalker. The whatToShow flags and the NodeFilter are not considered when setting this value; any node type will be accepted as the root. The currentNode of the TreeWalker is initialized to this node, whether or not it is visible. The root functions as a stopping point for traversal methods that look upward in the document structure, such as parentNode and nextNode. The root must not be null. |
| whatToShow | Int64 | flag specifies which node types may appear in the logical view of the tree presented by the tree-walker. See the description of NodeFilter for the set of possible SHOW_ values.These flags can be combined using OR. |
| filter | INodeFilter | NodeFilter to be used with this TreeWalker, or null to indicate no filter. |

### Return Value

The newly created TreeWalker.

### See Also

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.html.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* namespace [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* assembly [Aspose.HTML](../../../)
