---
title: IDocumentTraversal.CreateTreeWalker
second_title: Aspose.HTML for .NET API 参考
description: IDocumentTraversal 方法. 在以 the 指定节点为根的子树上创建一个新的 TreeWalker
type: docs
weight: 20
url: /zh/net/aspose.html.dom.traversal/idocumenttraversal/createtreewalker/
---
## CreateTreeWalker(Node) {#createtreewalker}

在以 the 指定节点为根的子树上创建一个新的 TreeWalker。

```csharp
public ITreeWalker CreateTreeWalker(Node root)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| root | Node | 节点将作为 the TreeWalker 的根节点。设置此值时不考虑 whatToShow 标志和 the NodeFilter； 任何节点类型都将被接受为根。 TreeWalker的 currentNode被 初始化为这个节点，不管它是否可见。 root 作为在文档结构中向上查找的 traversal 方法的停止点，例如 parentNode 和 nextNode。根必须 不为空。 |

### 返回值

新创建的 TreeWalker.

### 也可以看看

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* 命名空间 [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* 部件 [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long) {#createtreewalker_1}

在以 the 指定节点为根的子树上创建一个新的 TreeWalker。

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| root | Node | 节点将作为 the TreeWalker 的根节点。设置此值时不考虑 whatToShow 标志和 the NodeFilter； 任何节点类型都将被接受为根。 TreeWalker的 currentNode被 初始化为这个节点，不管它是否可见。 root 作为在文档结构中向上查找的 traversal 方法的停止点，例如 parentNode 和 nextNode。根必须 不为空。 |
| whatToShow | Int64 | flag 指定哪些节点类型可能出现在 tree-walker 呈现的树的逻辑视图中。有关可能的 SHOW_值集，请参阅 NodeFilter 的 描述。可以使用 OR 组合这些标志。 |

### 返回值

新创建的 TreeWalker.

### 也可以看看

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* 命名空间 [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* 部件 [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long, INodeFilter) {#createtreewalker_2}

在以 the 指定节点为根的子树上创建一个新的 TreeWalker。

```csharp
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| root | Node | 节点将作为 the TreeWalker 的根节点。设置此值时不考虑 whatToShow 标志和 the NodeFilter； 任何节点类型都将被接受为根。 TreeWalker的 currentNode被 初始化为这个节点，不管它是否可见。 root 作为在文档结构中向上查找的 traversal 方法的停止点，例如 parentNode 和 nextNode。根必须 不为空。 |
| whatToShow | Int64 | flag 指定哪些节点类型可能出现在 tree-walker 呈现的树的逻辑视图中。有关可能的 SHOW_值集，请参阅 NodeFilter 的 描述。可以使用 OR 组合这些标志。 |
| filter | INodeFilter | 与 this TreeWalker 一起使用的 NodeFilter，或 null 表示没有过滤器。 |

### 返回值

新创建的 TreeWalker.

### 也可以看看

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../aspose.html.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* 命名空间 [Aspose.Html.Dom.Traversal](../../idocumenttraversal/)
* 部件 [Aspose.HTML](../../../)


