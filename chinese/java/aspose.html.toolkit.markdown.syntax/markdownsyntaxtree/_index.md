---
title: "MarkdownSyntaxTree 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.toolkit.markdown.syntax.MarkdownSyntaxTree 类。表示 Markdown 语法树"
type: docs

url: /zh/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/
---
## MarkdownSyntaxTree class

表示 Markdown 语法树。

```java
public class MarkdownSyntaxTree : MarkdownSyntaxNode
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MarkdownSyntaxTree](markdownsyntaxtree/#constructor)() | 已创建 MarkdownSyntaxTree。 |
| [MarkdownSyntaxTree](markdownsyntaxtree/#constructor_1)(Configuration) | 创建 MarkdownSyntaxTree |

## 属性

| 名称 | 描述 |
| --- | --- |
| [getFirstChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) 获取第一个子节点。 |
| [getLastChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) 获取最后一个子节点。 |
| [getNextSibling](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) 获取下一个兄弟节点。 |
| [getParent](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) 获取父节点。 |
| [getPreviousSibling](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) 获取上一个兄弟节点。 |
| [getSyntaxFactory](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/syntaxfactory/) 获取 SyntaxFactory。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [accept](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/accept/)(MarkdownSyntaxVisitor) | 定义访问语法树节点的接口。 |
| [appendChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(MarkdownSyntaxNode) | 追加子节点。 |
| [childNodes](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | 获取子节点集合。 |
| [createNodeIterator](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator)(MarkdownSyntaxNode) | 定义创建节点迭代器的接口。 |
| [createNodeIterator](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator_2)(MarkdownSyntaxNodeFilter) | 定义创建节点迭代器的接口。 |
| [createNodeIterator](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator_1)(MarkdownSyntaxNode, MarkdownSyntaxNodeFilter) | 定义创建节点迭代器的接口。 |
| [createTreeWalker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker)(MarkdownSyntaxNode) | 定义创建树遍历器的接口。 |
| [createTreeWalker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker_2)(MarkdownSyntaxNodeFilter) | 定义创建树遍历器的接口。 |
| [createTreeWalker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker_1)(MarkdownSyntaxNode, MarkdownSyntaxNodeFilter) | 定义创建树遍历器的接口。 |
| [getLeadingTrivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getleadingtrivia/)() | 获取前导 trivia。 |
| [getSyntaxTree](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getsyntaxtree/)() | 获取语法树。 |
| [getTrailingTrivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/gettrailingtrivia/)() | 获取后置 trivia。 |
| [insertBefore](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/insertbefore/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | 在节点前插入。 |
| [removeChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/removechild/)(MarkdownSyntaxNode) | 移除子节点。 |
| [replaceChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/replacechild/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | 替换子节点。 |
| [save](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save)(Stream) | 将语法树保存到指定的流。 |
| [save](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save_2)(String) | 将语法树保存到指定的路径。 |
| [save](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save_1)(TextWriter) | 将语法树保存到指定的 writer。 |
| [toString](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/toString/)() | 重写 ToString 方法。 |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(MarkdownTextWriter) | 写入 MarkdownTextWriter。 |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(TextWriter) | 将节点写入文本写入器。 |

### 另请参见

* class [MarkdownSyntaxNode](../markdownsyntaxnode/)
* package [com.aspose.html.toolkit.markdown.syntax](../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../)
