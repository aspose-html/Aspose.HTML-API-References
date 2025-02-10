---
title: IDocumentTraversal.CreateNodeIterator
second_title: Aspose.HTML for Java API Reference
description: IDocumentTraversal method. Create a new NodeIterator over the subtree rooted at the specified node
type: docs
weight: 10
url: /java/com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/
---
## CreateNodeIterator(Node) {#createnodeiterator}

Create a new NodeIterator over the subtree rooted at the specified node.

```java
public INodeIterator CreateNodeIterator(Node root)
```

| Parameter | Type | Description |
| --- | --- | --- |
| root | Node | node which will be iterated together with its children. The iterator is initially positioned just before this node. The whatToShow flags and the filter, if any, are not considered when setting this position. The root must not be null. |

### Return Value

The newly created NodeIterator.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Raised if the specified root is null. |

### See Also

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long) {#createnodeiterator_1}

Create a new NodeIterator over the subtree rooted at the specified node.

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| Parameter | Type | Description |
| --- | --- | --- |
| root | Node | node which will be iterated together with its children. The iterator is initially positioned just before this node. The whatToShow flags and the filter, if any, are not considered when setting this position. The root must not be null. |
| whatToShow | Int64 | flag specifies which node types may appear in the logical view of the tree presented by the iterator. See the description of NodeFilter for the set of possible SHOW_ values.These flags can be combined using OR. |

### Return Value

The newly created NodeIterator.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Raised if the specified root is null. |

### See Also

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long, INodeFilter) {#createnodeiterator_2}

Create a new NodeIterator over the subtree rooted at the specified node.

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| Parameter | Type | Description |
| --- | --- | --- |
| root | Node | node which will be iterated together with its children. The iterator is initially positioned just before this node. The whatToShow flags and the filter, if any, are not considered when setting this position. The root must not be null. |
| whatToShow | Int64 | flag specifies which node types may appear in the logical view of the tree presented by the iterator. See the description of NodeFilter for the set of possible SHOW_ values.These flags can be combined using OR. |
| filter | INodeFilter | NodeFilter to be used with this TreeWalker, or null to indicate no filter. |

### Return Value

The newly created NodeIterator.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Raised if the specified root is null. |

### See Also

* interface [INodeIterator](../../inodeiterator/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
