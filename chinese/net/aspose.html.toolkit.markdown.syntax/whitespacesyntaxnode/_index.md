---
title: Class WhitespaceSyntaxNode
second_title: Aspose.HTML for .NET API 参考
description: Aspose.Html.Toolkit.Markdown.Syntax.WhitespaceSyntaxNode 班级. 表示空白语法节点
type: docs
weight: 5740
url: /zh/net/aspose.html.toolkit.markdown.syntax/whitespacesyntaxnode/
---
## WhitespaceSyntaxNode class

表示空白语法节点。

```csharp
public sealed class WhitespaceSyntaxNode : TextSyntaxNode
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [FirstChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) { get; } | 得到第一个孩子. |
| [LastChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) { get; } | 得到最后一个孩子。 |
| [NextSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) { get; } | 获取下一个兄弟姐妹。 |
| [Parent](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) { get; } | 获取父节点. |
| [PreviousSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) { get; } | 获取前一个兄弟。 |
| virtual [Source](../../aspose.html.toolkit.markdown.syntax/textsyntaxnode/source/) { get; } | 返回源文本。 |
| virtual [Span](../../aspose.html.toolkit.markdown.syntax/textsyntaxnode/span/) { get; } | 定义获取跨度的接口。 |
| [Value](../../aspose.html.toolkit.markdown.syntax/textsyntaxnode/value/) { get; } | 定义获取字符串值的属性。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Accept](../../aspose.html.toolkit.markdown.syntax/whitespacesyntaxnode/accept/)(MarkdownSyntaxVisitor) | 定义访问语法节点的接口。 |
| [AppendChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(MarkdownSyntaxNode) | 追加子节点. |
| [ChildNodes](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | 获取子节点集合。 |
| [GetLeadingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getleadingtrivia/)() | 获取领先的琐事。 |
| [GetSyntaxTree](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getsyntaxtree/)() | 获取语法树。 |
| [GetTrailingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/gettrailingtrivia/)() | 获取尾随的琐事。 |
| [InsertBefore](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/insertbefore/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | 在节点之前插入。 |
| [RemoveChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/removechild/)(MarkdownSyntaxNode) | 删除孩子. |
| [ReplaceChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/replacechild/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | 替换子节点。 |
| override [ToString](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/tostring/)() | 覆盖 ToString 方法。 |
| virtual [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(MarkdownTextWriter) | 写入 MarkdownTextWriter. |
| [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(TextWriter) | 将节点写入文本编写器。 |

### 也可以看看

* class [TextSyntaxNode](../textsyntaxnode/)
* 命名空间 [Aspose.Html.Toolkit.Markdown.Syntax](../../aspose.html.toolkit.markdown.syntax/)
* 部件 [Aspose.HTML](../../)

