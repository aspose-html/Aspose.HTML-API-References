---
title: "MarkdownSyntaxNode 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.toolkit.markdown.syntax.MarkdownSyntaxNode 类。MarkdownSyntaxNode 的基础实现"
type: docs

url: /zh/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/
---
## MarkdownSyntaxNode class

MarkdownSyntaxNode 的基础实现。

```java
public abstract class MarkdownSyntaxNode : IWritable
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getFirstChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) 获取第一个子节点。 |
| [getLastChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) 获取最后一个子节点。 |
| [getNextSibling](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) 获取下一个兄弟节点。 |
| [getParent](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) 获取父节点。 |
| [getPreviousSibling](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) 获取上一个兄弟节点。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [accept](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/accept/)(MarkdownSyntaxVisitor) | 接受访问者。 |
| [appendChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(MarkdownSyntaxNode) | 追加子节点。 |
| [childNodes](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | 获取子节点集合。 |
| [getLeadingTrivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getleadingtrivia/)() | 获取前导 trivia。 |
| [getSyntaxTree](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getsyntaxtree/)() | 获取语法树。 |
| [getTrailingTrivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/gettrailingtrivia/)() | 获取后置 trivia。 |
| [insertBefore](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/insertbefore/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | 在节点之前插入。 |
| [removeChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/removechild/)(MarkdownSyntaxNode) | 移除子节点。 |
| [replaceChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/replacechild/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | 替换子节点。 |
| [toString](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/toString/)() | 重写 ToString 方法。 |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/#writeto)(MarkdownTextWriter) | 写入 MarkdownTextWriter。 |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/#writeto_1)(TextWriter) | 将节点写入文本写入器。 |

### 另请参阅

* interface [IWritable](../iwritable/)
* package [com.aspose.html.toolkit.markdown.syntax](../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../)
