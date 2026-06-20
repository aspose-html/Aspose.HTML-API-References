---
title: "NodeFilter 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.dom.traversal.filters.NodeFilter 类。过滤器是能够过滤节点的对象"
type: docs

url: /zh/java/com.aspose.html.dom.traversal.filters/nodefilter/
---
## NodeFilter class

过滤器是能够 "filter out" 节点的对象。

```java
public abstract class NodeFilter : DOMObject, INodeFilter
```

## 方法

| 名称 | 描述 |
| --- | --- |
| abstract [AcceptNode](../../com.aspose.html.dom.traversal.filters/nodefilter/acceptnode/)(Node) | 测试指定节点在 TreeWalker 或 NodeIterator 的逻辑视图中是否可见。此函数将由 TreeWalker 和 NodeIterator 的实现调用；通常不会直接从用户代码中调用。（如果您想使用相同的过滤器来指导自己的应用逻辑，也可以这样做。） |
| [getPlatformType](../../com.aspose.html.dom.traversal.filters/nodefilter/getplatformtype/)() | 此方法用于检索 ECMAScript 对象的 Type。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [FILTER_ACCEPT](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_accept/) | 接受该节点。为 NodeIterator 或 TreeWalker 定义的导航方法将返回此节点。 |
| const [FILTER_REJECT](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_reject/) | 拒绝该节点。为 NodeIterator 或 TreeWalker 定义的导航方法将不返回此节点。对于 TreeWalker，此节点的子节点也将被拒绝。NodeIterators 将其视为 FILTER_SKIP 的同义词。 |
| const [FILTER_SKIP](../../com.aspose.html.dom.traversal.filters/nodefilter/filter_skip/) | 跳过此单个节点。为 NodeIterator 或 TreeWalker 定义的导航方法将不返回此节点。对于 NodeIterator 和 TreeWalker，仍会考虑此节点的子节点。 |
| const [SHOW_ALL](../../com.aspose.html.dom.traversal.filters/nodefilter/show_all/) | 显示所有节点。 |
| const [SHOW_ATTRIBUTE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_attribute/) | 显示属性节点。仅在以属性节点作为根创建迭代器或树遍历器时才有意义；在这种情况下，属性节点将在迭代或遍历的首位出现。由于属性永远不是其他节点的子节点，在遍历文档树时它们不会出现。 |
| const [SHOW_CDATA_SECTION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_cdata_section/) | 显示 CDATASection 节点。 |
| const [SHOW_COMMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_comment/) | 显示注释节点。 |
| const [SHOW_DOCUMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document/) | 显示文档节点。 |
| const [SHOW_DOCUMENT_FRAGMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document_fragment/) | 显示 DocumentFragment 节点。 |
| const [SHOW_DOCUMENT_TYPE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_document_type/) | 显示 DocumentType 节点。 |
| const [SHOW_ELEMENT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_element/) | 显示元素节点。 |
| const [SHOW_ENTITY](../../com.aspose.html.dom.traversal.filters/nodefilter/show_entity/) | 显示实体节点。仅在以 Entity 节点作为根创建迭代器或树遍历器时才有意义；在这种情况下，Entity 节点将在遍历的首位出现。由于实体不属于文档树的一部分，在遍历文档树时它们不会出现。 |
| const [SHOW_ENTITY_REFERENCE](../../com.aspose.html.dom.traversal.filters/nodefilter/show_entity_reference/) | 显示 EntityReference 节点。 |
| const [SHOW_NOTATION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_notation/) | 显示 Notation 节点。仅在使用 Notation 节点作为根创建迭代器或树遍历器时才有意义；在这种情况下，这意味着 Notation 节点将在遍历的首位出现。由于 Notation 不属于文档树的一部分，它们在遍历文档树时不会出现。 |
| const [SHOW_PROCESSING_INSTRUCTION](../../com.aspose.html.dom.traversal.filters/nodefilter/show_processing_instruction/) | 显示 ProcessingInstruction 节点。 |
| const [SHOW_TEXT](../../com.aspose.html.dom.traversal.filters/nodefilter/show_text/) | 显示 Text 节点。 |

### 另请参见

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* interface [INodeFilter](../../com.aspose.html.dom.traversal/inodefilter/)
* package [com.aspose.html.dom.traversal.filters](../../com.aspose.html.dom.traversal.filters/)
* package [Aspose.HTML](../../)
