---
title: XPathResultType
second_title: Aspose.HTML for .NET API 参考
description: 一个无符号短整数表示这是什么类型的结果如果指定了特定的  类型 则使用 XPath 将结果作为对应的 类型返回在需要和可能的情况下进行类型转换
type: docs
weight: 2720
url: /zh/net/aspose.html.dom.xpath/xpathresulttype/
---
## XPathResultType enumeration

一个无符号短整数，表示这是什么类型的结果。如果指定了特定的 ` 类型` ，则使用 XPath 将结果作为对应的 类型返回在需要和可能的情况下进行类型转换。

```csharp
public enum XPathResultType
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| Any | `0` | 此代码不代表特定类型。 XPath 表达式 的求值永远不会产生这种类型。如果请求此类型，则评估返回 表达式评估自然产生的任何类型。如果自然 结果是在请求` 任何` 类型时设置的节点，则` UnorderedNodeIterator` 始终是结果类型。节点集的任何其他表示必须是 明确请求的。 |
| Number | `1` | 结果是 [XPath 1.0] 定义的数字。文档修改不会 使数字无效，但可能意味着重新评估不会产生相同的数字。 |
| String | `2` | 结果是 [XPath 1.0] 定义的字符串。文档修改不会 使字符串无效，但可能意味着该字符串不再对应于 当前文档。 |
| Boolean | `3` | 结果是 [XPath 1.0] 定义的布尔值。文档修改不会 使布尔值无效，但可能意味着重新评估不会产生相同的布尔值。 |
| UnorderedNodeIterator | `4` | 结果是由 [XPath 1.0] 定义的节点集，将被迭代访问， 可能不会以特定顺序生成节点.文档修改使 迭代无效。如果结果是节点集并且请求了` 任何` 类型，则这是返回的默认类型。 |
| OrderedNodeIterator | `5` | 结果是由 [XPath 1.0] 定义的节点集，将被迭代访问， 将产生文档排序的节点。文档修改使迭代无效。 |
| UnorderedNodeSnapshot | `6` | 结果是由 [XPath 1.0] 定义的节点集，将作为快照访问 可能不在的节点列表一个特定的顺序。文档修改不会 使快照无效，但可能意味着重新评估不会产生相同的快照 并且快照中的节点可能已被更改、移动或从文档中删除。 |
| OrderedNodeSnapshot | `7` | 结果是由 [XPath 1.0] 定义的节点集，将作为快照访问 原始节点列表文件顺序。文档修改不会 使快照无效，但可能意味着重新评估不会产生相同的快照 并且快照中的节点可能已被更改、移动或从文档中删除。 |
| AnyUnorderedNode | `8` | 结果是由 [XPath 1.0] 定义的节点集，并将作为单个节点访问， 可能是` null` 如果节点集为空。文档修改不会使 节点失效，但可能意味着结果节点不再对应于当前文档。 这是一种允许优化的便利，因为一旦找到结果集中的任何 节点，实现就可以停止。如果实际结果中有多个节点， 返回的单个节点可能不是文档顺序中的第一个。 |
| FirstOrderedNode | `9` | 结果是由 [XPath 1.0] 定义的节点集，并将作为单个节点访问， 可能是` null` 如果节点集为空。文档修改不会使 节点失效，但可能意味着结果节点不再对应于当前文档。 这是一种允许优化的便利，因为一旦找到结果集的文档顺序中的 第一个节点，实现就可以停止。如果实际结果中有多个 节点，则返回的单个节点将是文档顺序中的第一个。 |

### 也可以看看

* 命名空间 [Aspose.Html.Dom.XPath](../../aspose.html.dom.xpath)
* 部件 [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
