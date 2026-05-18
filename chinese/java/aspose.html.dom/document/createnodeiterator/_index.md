---
title: "Document.CreateNodeIterator"
second_title: "Aspose.HTML for Java API 参考"
description: "Document 方法。创建一个新的 NodeIterator，遍历以指定节点为根的子树"
type: docs

url: /zh/java/com.aspose.html.dom/document/createnodeiterator/
---
## CreateNodeIterator(Node) {#createnodeiterator}

在指定节点为根的子树上创建一个新的 NodeIterator。

```java
public INodeIterator CreateNodeIterator(Node root)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 根 | Node | 将与其子节点一起迭代的节点。迭代器最初定位在该节点之前。设置此位置时不考虑 whatToShow 标志和过滤器（如果有）。根节点不能为空。 |

### 返回值

新创建的 NodeIterator。

### 异常

| 异常 | 条件 |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR：如果指定的根为 null 则抛出此错误。 |

### 另请参阅

* interface [INodeIterator](../../../com.aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long) {#createnodeiterator_1}

在指定节点为根的子树上创建一个新的 NodeIterator。

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 根 | Node | 将与其子节点一起迭代的节点。迭代器最初定位在该节点之前。设置此位置时不考虑 whatToShow 标志和过滤器（如果有）。根节点不能为空。 |
| whatToShow | Int64 | 标志指定哪些节点类型可以出现在迭代器呈现的树的逻辑视图中。请参阅 NodeFilter 的描述以获取可能的 SHOW_ 值集合。这些标志可以使用 OR 进行组合。 |

### 返回值

新创建的 NodeIterator。

### 异常

| 异常 | 条件 |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR：如果指定的根为 null 则抛出此错误。 |

### 另请参阅

* interface [INodeIterator](../../../com.aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## CreateNodeIterator(Node, long, INodeFilter) {#createnodeiterator_2}

在指定节点为根的子树上创建一个新的 NodeIterator。

```java
public INodeIterator CreateNodeIterator(Node root, long whatToShow, INodeFilter filter)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 根 | Node | 将与其子节点一起迭代的节点。迭代器最初定位在该节点之前。设置此位置时不考虑 whatToShow 标志和过滤器（如果有）。根节点不能为空。 |
| whatToShow | Int64 | 标志指定哪些节点类型可以出现在迭代器呈现的树的逻辑视图中。请参阅 NodeFilter 的描述以获取可能的 SHOW_ 值集合。这些标志可以使用 OR 进行组合。 |
| 过滤器 | INodeFilter | 用于此 TreeWalker 的 NodeFilter，若为 null 则表示没有过滤器。 |

### 返回值

新创建的 NodeIterator。

### 异常

| 异常 | 条件 |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR：如果指定的根为 null 则抛出此错误。 |

### 另请参阅

* interface [INodeIterator](../../../com.aspose.html.dom.traversal/inodeiterator/)
* class [Node](../../node/)
* interface [INodeFilter](../../../com.aspose.html.dom.traversal/inodefilter/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
