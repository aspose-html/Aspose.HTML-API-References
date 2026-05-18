---
title: "IDocumentTraversal.CreateTreeWalker"
second_title: "Aspose.HTML for Java API 参考"
description: "IDocumentTraversal 方法。创建一个新的 TreeWalker，遍历以指定节点为根的子树。"
type: docs

url: /zh/java/com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/
---
## CreateTreeWalker(Node) {#createtreewalker}

在指定节点为根的子树上创建一个新的 TreeWalker。

```java
public ITreeWalker CreateTreeWalker(Node root)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 根 | Node | 将作为 TreeWalker 根的节点。设置此值时不考虑 whatToShow 标志和 NodeFilter；任何节点类型都可接受为根。TreeWalker 的 currentNode 初始化为该节点，无论其是否可见。根节点作为向上遍历文档结构的停止点，例如 parentNode 和 nextNode 方法。根节点不能为空。 |

### 返回值

新创建的 TreeWalker。

### 另请参阅

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long) {#createtreewalker_1}

在指定节点为根的子树上创建一个新的 TreeWalker。

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 根 | Node | 将作为 TreeWalker 根的节点。设置此值时不考虑 whatToShow 标志和 NodeFilter；任何节点类型都可接受为根。TreeWalker 的 currentNode 初始化为该节点，无论其是否可见。根节点作为向上遍历文档结构的停止点，例如 parentNode 和 nextNode 方法。根节点不能为空。 |
| whatToShow | Int64 | 标志指定哪些节点类型可以出现在树遍历器呈现的树的逻辑视图中。请参阅 NodeFilter 的描述以获取可能的 SHOW_ 值集合。这些标志可以使用 OR 进行组合。 |

### 返回值

新创建的 TreeWalker。

### 另请参阅

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)

---

## CreateTreeWalker(Node, long, INodeFilter) {#createtreewalker_2}

在指定节点为根的子树上创建一个新的 TreeWalker。

```java
public ITreeWalker CreateTreeWalker(Node root, long whatToShow, INodeFilter filter)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 根 | Node | 将作为 TreeWalker 根的节点。设置此值时不考虑 whatToShow 标志和 NodeFilter；任何节点类型都可接受为根。TreeWalker 的 currentNode 初始化为该节点，无论其是否可见。根节点作为向上遍历文档结构的停止点，例如 parentNode 和 nextNode 方法。根节点不能为空。 |
| whatToShow | Int64 | 标志指定哪些节点类型可以出现在树遍历器呈现的树的逻辑视图中。请参阅 NodeFilter 的描述以获取可能的 SHOW_ 值集合。这些标志可以使用 OR 进行组合。 |
| 过滤器 | INodeFilter | 用于此 TreeWalker 的 NodeFilter，若为 null 则表示没有过滤器。 |

### 返回值

新创建的 TreeWalker。

### 另请参阅

* interface [ITreeWalker](../../itreewalker/)
* class [Node](../../../com.aspose.html.dom/node/)
* interface [INodeFilter](../../inodefilter/)
* interface [IDocumentTraversal](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
