---
title: Class MarkdownSyntaxTree
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Toolkit.Markdown.Syntax.MarkdownSyntaxTree 班级. 表示 Markdown 语法树
type: docs
weight: 5220
url: /zh/net/aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/
---
## MarkdownSyntaxTree class

表示 Markdown 语法树。

```csharp
public class MarkdownSyntaxTree : MarkdownSyntaxNode
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [MarkdownSyntaxTree](markdownsyntaxtree/#constructor)() | 创建了 MarkdownSyntaxTree. |
| [MarkdownSyntaxTree](markdownsyntaxtree/#constructor_1)(Configuration) | 创建 MarkdownSyntaxTree |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [FirstChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) { get; } | 得到第一个孩子. |
| [LastChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) { get; } | 得到最后一个孩子。 |
| [NextSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) { get; } | 获取下一个兄弟姐妹。 |
| [Parent](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) { get; } | 获取父节点. |
| [PreviousSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) { get; } | 获取前一个兄弟。 |
| [SyntaxFactory](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/syntaxfactory/) { get; } | 获取 SyntaxFactory. |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Accept](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/accept/)(MarkdownSyntaxVisitor) | 定义访问语法树节点的接口。 |
| [AppendChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(MarkdownSyntaxNode) | 追加子节点. |
| [ChildNodes](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | 获取子节点集合。 |
| [CreateNodeIterator](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator)(MarkdownSyntaxNode) | 定义用于创建节点迭代器的接口。 |
| [CreateNodeIterator](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator_2)(MarkdownSyntaxNodeFilter) | 定义用于创建节点迭代器的接口。 |
| [CreateNodeIterator](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator_1)(MarkdownSyntaxNode, MarkdownSyntaxNodeFilter) | 定义用于创建节点迭代器的接口。 |
| [CreateTreeWalker](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker)(MarkdownSyntaxNode) | 定义用于创建 tree walker 的接口。 |
| [CreateTreeWalker](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker_2)(MarkdownSyntaxNodeFilter) | 定义用于创建 tree walker 的接口。 |
| [CreateTreeWalker](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker_1)(MarkdownSyntaxNode, MarkdownSyntaxNodeFilter) | 定义用于创建 tree walker 的接口。 |
| [GetLeadingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getleadingtrivia/)() | 获取领先的琐事。 |
| [GetSyntaxTree](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getsyntaxtree/)() | 获取语法树。 |
| [GetTrailingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/gettrailingtrivia/)() | 获取尾随的琐事。 |
| [InsertBefore](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/insertbefore/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | 在节点之前插入。 |
| [RemoveChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/removechild/)(MarkdownSyntaxNode) | 删除孩子. |
| [ReplaceChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/replacechild/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | 替换子节点。 |
| [Save](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save)(Stream) | 将语法树保存到指定的流中。 |
| [Save](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save_2)(string) | 将语法树保存到指定路径。 |
| [Save](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save_1)(TextWriter) | 将语法树保存到指定的 writer. |
| override [ToString](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/tostring/)() | 覆盖 ToString 方法。 |
| virtual [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(MarkdownTextWriter) | 写入 MarkdownTextWriter. |
| [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(TextWriter) | 将节点写入文本编写器。 |

### 也可以看看

* class [MarkdownSyntaxNode](../markdownsyntaxnode/)
* 命名空间 [Aspose.Html.Toolkit.Markdown.Syntax](../../aspose.html.toolkit.markdown.syntax/)
* 部件 [Aspose.HTML](../../)


