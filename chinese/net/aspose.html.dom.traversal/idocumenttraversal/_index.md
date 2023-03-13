---
title: Interface IDocumentTraversal
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Traversal.IDocumentTraversal 界面. DocumentTraversal包含创建迭代器和 treewalkers的方法以文档顺序遍历节点及其子节点深度 优先前序遍历相当于 开始标记在文本表示中出现的顺序文档在支持遍历功能的 DOM 中DocumentTraversal 将 由实现 Document 接口的相同对象实现
type: docs
weight: 2470
url: /zh/net/aspose.html.dom.traversal/idocumenttraversal/
---
## IDocumentTraversal interface

DocumentTraversal包含创建迭代器和 tree-walkers的方法，以文档顺序遍历节点及其子节点（深度 优先，前序遍历，相当于 开始标记在文本表示中出现的顺序文档）。在支持遍历功能的 DOM 中，DocumentTraversal 将 由实现 Document 接口的相同对象实现。

另见[文档对象模型 (DOM) 级别 2 遍历和范围规范](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM 级别 2

```csharp
public interface IDocumentTraversal
```

## 方法

| 姓名 | 描述 |
| --- | --- |
| [CreateNodeIterator](../../aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator)(Node) | 在以 the 指定节点为根的子树上创建一个新的 NodeIterator。 |
| [CreateNodeIterator](../../aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_1)(Node, long) | 在以 the 指定节点为根的子树上创建一个新的 NodeIterator。 |
| [CreateNodeIterator](../../aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_2)(Node, long, INodeFilter) | 在以 the 指定节点为根的子树上创建一个新的 NodeIterator。 |
| [CreateTreeWalker](../../aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker)(Node) | 在以 the 指定节点为根的子树上创建一个新的 TreeWalker。 |
| [CreateTreeWalker](../../aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_1)(Node, long) | 在以 the 指定节点为根的子树上创建一个新的 TreeWalker。 |
| [CreateTreeWalker](../../aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_2)(Node, long, INodeFilter) | 在以 the 指定节点为根的子树上创建一个新的 TreeWalker。 |

### 也可以看看

* 命名空间 [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* 部件 [Aspose.HTML](../../)


