---
title: Class NodeFilter
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Dom.Traversal.Filters.NodeFilter 班级. 过滤器是知道如何过滤掉节点的对象
type: docs
weight: 2460
url: /zh/net/aspose.html.dom.traversal.filters/nodefilter/
---
## NodeFilter class

过滤器是知道如何“过滤掉”节点的对象。

```csharp
public abstract class NodeFilter : DOMObject, INodeFilter
```

## 方法

| 姓名 | 描述 |
| --- | --- |
| abstract [AcceptNode](../../aspose.html.dom.traversal.filters/nodefilter/acceptnode/)(Node) | 测试指定节点在a TreeWalker 或NodeIterator 的逻辑视图中是否可见。这个函数 将被TreeWalker和 NodeIterator的实现调用；它通常不会直接从 用户代码中调用。 （尽管如果您想使用 same 过滤器来指导您自己的应用程序逻辑，您可以这样做。） |
| override [GetPlatformType](../../aspose.html.dom.traversal.filters/nodefilter/getplatformtype/)() | 此方法用于检索 ECMAScript 对象Type. |

## 字段

| 姓名 | 描述 |
| --- | --- |
| const [FILTER_ACCEPT](../../aspose.html.dom.traversal.filters/nodefilter/filter_accept/) | 接受节点。为 NodeIterator 或 TreeWalker 定义的导航方法将返回此 node. |
| const [FILTER_REJECT](../../aspose.html.dom.traversal.filters/nodefilter/filter_reject/) | 拒绝该节点。为 NodeIterator 或 TreeWalker 定义的导航方法将不会返回 此节点。对于 TreeWalker，此节点 的子节点也将被拒绝。 NodeIterators 将其视为 FILTER_SKIP. 的 同义词 |
| const [FILTER_SKIP](../../aspose.html.dom.traversal.filters/nodefilter/filter_skip/) | 跳过此单个节点。为 NodeIterator 或 TreeWalker 定义的导航方法将不会返回 此节点。对于 NodeIterator 和 TreeWalker，该节点的子节点仍将被 考虑。 |
| const [SHOW_ALL](../../aspose.html.dom.traversal.filters/nodefilter/show_all/) | 显示所有节点。 |
| const [SHOW_ATTRIBUTE](../../aspose.html.dom.traversal.filters/nodefilter/show_attribute/) | 显示属性节点。这仅在创建以属性节点作为其 根的 迭代器或树遍历器时才有意义；在这种情况下，这意味着属性节点 将出现在迭代或遍历的第一个位置。 由于属性永远不是其他节点的子节点，因此在遍历文档树时它们不会 出现。 |
| const [SHOW_CDATA_SECTION](../../aspose.html.dom.traversal.filters/nodefilter/show_cdata_section/) | 显示 CDATASection 节点。 |
| const [SHOW_COMMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_comment/) | 显示注释节点。 |
| const [SHOW_DOCUMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_document/) | 显示文档节点。 |
| const [SHOW_DOCUMENT_FRAGMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_document_fragment/) | 显示 DocumentFragment 节点。 |
| const [SHOW_DOCUMENT_TYPE](../../aspose.html.dom.traversal.filters/nodefilter/show_document_type/) | 显示文档类型节点。 |
| const [SHOW_ELEMENT](../../aspose.html.dom.traversal.filters/nodefilter/show_element/) | 显示元素节点。 |
| const [SHOW_ENTITY](../../aspose.html.dom.traversal.filters/nodefilter/show_entity/) | 显示实体节点。这仅在创建 以实体节点作为其 根的迭代器或树遍历器时才有意义；在这种情况下，意味着 Entity 节点将出现在遍历的第一个位置。由于 实体不是文档树的一部分，因此当 遍历文档树时它们不会出现。 |
| const [SHOW_ENTITY_REFERENCE](../../aspose.html.dom.traversal.filters/nodefilter/show_entity_reference/) | 显示 EntityReference 节点。 |
| const [SHOW_NOTATION](../../aspose.html.dom.traversal.filters/nodefilter/show_notation/) | 显示符号节点。这仅在创建 迭代器或以 Notation 节点作为其 根的树遍历器时才有意义；在这种情况下，这意味着 Notation 节点将出现在 遍历的第一个位置。由于符号不是文档树的一部分，因此在遍历文档树时它们 不会出现。 |
| const [SHOW_PROCESSING_INSTRUCTION](../../aspose.html.dom.traversal.filters/nodefilter/show_processing_instruction/) | 显示 ProcessingInstruction 节点。 |
| const [SHOW_TEXT](../../aspose.html.dom.traversal.filters/nodefilter/show_text/) | 显示文本节点。 |

### 也可以看看

* class [DOMObject](../../aspose.html.dom/domobject/)
* interface [INodeFilter](../../aspose.html.dom.traversal/inodefilter/)
* 命名空间 [Aspose.Html.Dom.Traversal.Filters](../../aspose.html.dom.traversal.filters/)
* 部件 [Aspose.HTML](../../)


