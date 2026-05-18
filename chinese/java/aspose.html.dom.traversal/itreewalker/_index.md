---
title: "ITreeWalker Interface"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.traversal.ITreeWalker 接口。TreeWalker 对象用于使用其 whatToShow 标志和（如果有）过滤器定义的文档视图来导航文档树或子树。任何使用 TreeWalker 执行导航的函数都会自动支持 TreeWalker 定义的视图。"
type: docs

url: /zh/java/com.aspose.html.dom.traversal/itreewalker/
---
## ITreeWalker interface

TreeWalker 对象用于使用其 whatToShow 标志和过滤器（如果有）定义的文档视图来导航文档树或子树。任何使用 TreeWalker 执行导航的函数都将自动支持 TreeWalker 定义的任何视图。

从子树的逻辑视图中省略节点可能导致结构与完整未过滤文档中的同一子树有显著差异。在 TreeWalker 视图中是兄弟关系的节点，在原始视图中可能是不同、相距甚远的节点的子节点。例如，考虑一个只保留 Text 节点和文档根节点的 NodeFilter。在由此产生的逻辑视图中，所有文本节点将成为兄弟节点，并作为根节点的直接子节点出现，无论原始文档的结构多么深层嵌套。

另请参阅 [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113)。 @since DOM Level 2

```java
public interface ITreeWalker : ITraversal
```

## 属性

| 名称 | 描述 |
| --- | --- |
[getCurrentNode]
[setCurrentNode] The node at which the TreeWalker is currently positioned. Alterations to the DOM tree may cause the current node to no longer be accepted by the TreeWalker's associated filter. currentNode may also be explicitly set to any node, whether or not it is within the subtree specified by the root node or would be accepted by the filter and whatToShow flags. Further traversal occurs relative to currentNode even if it is not part of the current view, by applying the filters in the requested direction; if no traversal is possible, currentNode is not changed. |

## 方法

| 名称 | 描述 |
| --- | --- |
| [firstChild](../../com.aspose.html.dom.traversal/itreewalker/firstchild/)() | 将 TreeWalker 移动到当前节点的第一个可见子节点，并返回该新节点。如果当前节点没有可见子节点，则返回 null，并保持当前节点不变。 |
| [lastChild](../../com.aspose.html.dom.traversal/itreewalker/lastchild/)() | 将 TreeWalker 移动到当前节点的最后一个可见子节点，并返回该新节点。如果当前节点没有可见子节点，则返回 null，并保持当前节点不变。 |
| [nextNode](../../com.aspose.html.dom.traversal/itreewalker/nextnode/)() | 将 TreeWalker 按文档顺序移动到相对于当前节点的下一个可见节点，并返回该新节点。如果当前节点没有下一个节点，或在从 TreeWalker 根节点向上搜索 nextNode 时，返回 null，并保持当前节点不变。 |
| [nextSibling](../../com.aspose.html.dom.traversal/itreewalker/nextsibling/)() | 将 TreeWalker 移动到当前节点的下一个可见兄弟节点，并返回该新节点。如果当前节点没有可见的下一个兄弟节点，则返回 null，并保持当前节点不变。 |
| [parentNode](../../com.aspose.html.dom.traversal/itreewalker/parentnode/)() | 移动到并返回当前节点最近的可见祖先节点。如果在搜索 parentNode 时尝试从 TreeWalker 的根节点向上移动，或未能找到可见的祖先节点，则此方法保持当前位置并返回 null。 |
| [previousNode](../../com.aspose.html.dom.traversal/itreewalker/previousnode/)() | 将 TreeWalker 移动到相对于当前节点的文档顺序中前一个可见节点，并返回该新节点。如果当前节点没有前一个节点，或在搜索 previousNode 时尝试从 TreeWalker 的根节点向上移动，则返回 null，并保留当前节点。 |
| [previousSibling](../../com.aspose.html.dom.traversal/itreewalker/previoussibling/)() | 将 TreeWalker 移动到当前节点的前一个兄弟节点，并返回该新节点。如果当前节点没有可见的前一个兄弟节点，则返回 null，并保留当前节点。 |

### 另请参阅

* interface [ITraversal](../itraversal/)
* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
