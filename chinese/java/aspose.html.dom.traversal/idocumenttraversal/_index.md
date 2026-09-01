---
title: "IDocumentTraversal 接口"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.traversal.IDocumentTraversal 接口。DocumentTraversal 包含创建迭代器和 tree-walker 的方法，用于以文档顺序深度优先的前序遍历方式遍历节点及其子节点，这等同于文档文本表示中开始标签出现的顺序。在支持 Traversal 功能的 DOM 中，DocumentTraversal 将由实现 Document 接口的同一对象实现。"
type: docs

url: /zh/java/com.aspose.html.dom.traversal/idocumenttraversal/
---
## IDocumentTraversal interface

DocumentTraversal 包含用于创建迭代器和树遍历器的方法，以按文档顺序（深度优先、先序遍历，这等同于文档文本表示中起始标签出现的顺序）遍历节点及其子节点。在支持 Traversal 功能的 DOM 中，DocumentTraversal 将由实现 Document 接口的同一对象实现。

另请参阅 [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113)。 @since DOM Level 2

```java
public interface IDocumentTraversal
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator)(Node) | 在以指定节点为根的子树上创建一个新的 NodeIterator。 |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_1)(Node, long) | 在以指定节点为根的子树上创建一个新的 NodeIterator。 |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_2)(Node, long, INodeFilter) | 在以指定节点为根的子树上创建一个新的 NodeIterator。 |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker)(Node) | 在以指定节点为根的子树上创建一个新的 TreeWalker。 |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_1)(Node, long) | 在以指定节点为根的子树上创建一个新的 TreeWalker。 |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_2)(Node, long, INodeFilter) | 在以指定节点为根的子树上创建一个新的 TreeWalker。 |

### 另请参见

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
