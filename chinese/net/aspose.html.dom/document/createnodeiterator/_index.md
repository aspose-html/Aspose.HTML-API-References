---
title: Document.CreateNodeIterator
second_title: Aspose.HTML for .NET API 参考
description: Document 方法. 在以 the 指定节点为根的子树上创建一个新的 NodeIterator
type: docs
weight: 900
url: /zh/net/aspose.html.dom/document/createnodeiterator/
---
## CreateNodeIterator(Node) {#createnodeiterator}

在以 the 指定节点为根的子树上创建一个新的 NodeIterator。

```csharp
public INodeIterator CreateNodeIterator(Node root)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| root | Node | 将与其子节点一起迭代的节点。 迭代器最初位于此节点之前。 whatToShow 标志和过滤器（如果有）在设置此位置时不被 考虑。根不能是 null。 |

### 返回值

新创建的 NodeIterator.

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR：如果指定的根为 null 则引发。 |

### 也可以看看

* interface [INodeIterator](../../../aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* 命名空间 [Aspose.Html.Dom](../../document/)
* 部件 [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long) {#createnodeiterator_1}

在以 the 指定节点为根的子树上创建一个新的 NodeIterator。

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| root | Node | 将与其子节点一起迭代的节点。 迭代器最初位于此节点之前。 whatToShow 标志和过滤器（如果有）在设置此位置时不被 考虑。根不能是 null。 |
| whatToShow | Int64 | flag 指定哪些节点类型可能出现在 迭代器呈现的树的逻辑视图中。有关可能的 SHOW_值集，请参阅 NodeFilter 的 描述。这些标志可以使用 OR 组合。 |

### 返回值

新创建的 NodeIterator.

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR：如果指定的根为 null 则引发。 |

### 也可以看看

* interface [INodeIterator](../../../aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* 命名空间 [Aspose.Html.Dom](../../document/)
* 部件 [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long, INodeFilter) {#createnodeiterator_2}

在以 the 指定节点为根的子树上创建一个新的 NodeIterator。

```csharp
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| root | Node | 将与其子节点一起迭代的节点。 迭代器最初位于此节点之前。 whatToShow 标志和过滤器（如果有）在设置此位置时不被 考虑。根不能是 null。 |
| whatToShow | Int64 | flag 指定哪些节点类型可能出现在 迭代器呈现的树的逻辑视图中。有关可能的 SHOW_值集，请参阅 NodeFilter 的 描述。这些标志可以使用 OR 组合。 |
| filter | INodeFilter | 与 this TreeWalker 一起使用的 NodeFilter，或 null 表示没有过滤器。 |

### 返回值

新创建的 NodeIterator.

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| [DOMException](../../domexception/) | NOT_SUPPORTED_ERR：如果指定的根为 null 则引发。 |

### 也可以看看

* interface [INodeIterator](../../../aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* interface [INodeFilter](../../../aspose.html.dom.traversal/inodefilter/)
* class [Document](../)
* 命名空间 [Aspose.Html.Dom](../../document/)
* 部件 [Aspose.HTML](../../../)


