---
title: "ITraversal Interface"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.traversal.ITraversal 接口。迭代器用于遍历一组节点，例如 NodeList 中的节点、由特定节点管理的文档子树、查询结果或任何其他节点集合。要迭代的节点集合由 NodeIterator 的实现决定。DOM Level 2 为文档子树的文档顺序遍历指定了单一的 NodeIterator 实现。这些迭代器的实例通过调用 DocumentTraversal.createNodeIterator 创建。"
type: docs

url: /zh/java/com.aspose.html.dom.traversal/itraversal/
---
## ITraversal interface

迭代器用于遍历一组节点，例如 NodeList 中的节点集合、由特定节点管理的文档子树、查询结果或任何其他节点集合。要迭代的节点集合由 NodeIterator 的实现决定。DOM Level 2 为文档顺序遍历文档子树指定了单一的 NodeIterator 实现。这些迭代器的实例通过调用 DocumentTraversal .createNodeIterator() 创建。

另请参阅 [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113)。 @since DOM Level 2

```java
public interface ITraversal : IDisposable
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getFilter](../../com.aspose.html.dom.traversal/itraversal/filter/) 用于筛选节点的 NodeFilter。 |
| [getRoot](../../com.aspose.html.dom.traversal/itraversal/root/) NodeIterator 的根节点，在创建时指定。 |
| [getWhatToShow](../../com.aspose.html.dom.traversal/itraversal/whattoshow/) 此属性决定迭代器呈现哪些节点类型。可用的常量集合在 NodeFilter 接口中定义。未被 whatToShow 接受的节点将被跳过，但其子节点仍可能被考虑。请注意，此跳过优先于任何过滤器。 |

### 另请参见

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
