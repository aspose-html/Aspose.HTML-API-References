---
title: "HugoYamlBasedFrontMatterSyntaxNode 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.toolkit.markdown.syntax.extensions.HugoYamlBasedFrontMatterSyntaxNode 类。定义 HugoYamlBasedFrontMatterSyntaxNode"
type: docs

url: /zh/java/com.aspose.html.toolkit.markdown.syntax.extensions/hugoyamlbasedfrontmattersyntaxnode/
---
## HugoYamlBasedFrontMatterSyntaxNode class

定义 HugoYamlBasedFrontMatterSyntaxNode。

```java
public class HugoYamlBasedFrontMatterSyntaxNode : HugoFrontMatterSyntaxNode, 
    IEnumerable<KeyValuePair<ChildFrontMatterSyntaxNode, ChildFrontMatterSyntaxNode>>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [getFirstChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) 获取第一个子节点。 |
| [getFrontMatterRootNode](../../com.aspose.html.toolkit.markdown.syntax.extensions/hugoyamlbasedfrontmattersyntaxnode/frontmatterrootnode/) 获取 RootNode。 |
| [getLastChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) 获取最后一个子节点。 |
| [getNextSibling](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) 获取下一个兄弟节点。 |
| [getParent](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) 获取父节点。 |
| [getPreviousSibling](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) 获取上一个兄弟节点。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [accept](../../com.aspose.html.toolkit.markdown.syntax/blocksyntaxnode/accept/)(MarkdownSyntaxVisitor) | 定义接受访问者的接口。 |
| [appendChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(MarkdownSyntaxNode) | 追加子节点。 |
| [childNodes](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | 获取子节点集合。 |
| [find](../../com.aspose.html.toolkit.markdown.syntax.extensions/hugofrontmattersyntaxnode/find/)(params String[]) | 定义查找 BaseSyntaxNode 的接口 |
| [Find&lt;T&gt;](../../com.aspose.html.toolkit.markdown.syntax.extensions/hugoyamlbasedfrontmattersyntaxnode/find/#find_1)(params String[]) | 定义用于通过 String Path 查找 T 的接口 |
| [getEnumerator](../../com.aspose.html.toolkit.markdown.syntax.extensions/hugoyamlbasedfrontmattersyntaxnode/getenumerator/)() | 获取 Enumerator。 |
| [getLeadingTrivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getleadingtrivia/)() | 获取前导 trivia。 |
| [getSyntaxTree](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getsyntaxtree/)() | 获取语法树。 |
| [getTrailingTrivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/gettrailingtrivia/)() | 获取后置 trivia。 |
| [insertBefore](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/insertbefore/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | 在节点之前插入。 |
| [removeChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/removechild/)(MarkdownSyntaxNode) | 移除子节点。 |
| [replaceChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/replacechild/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | 替换子节点。 |
| [toString](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/toString/)() | 重写 ToString 方法。 |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(MarkdownTextWriter) | 写入 MarkdownTextWriter。 |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(TextWriter) | 将节点写入文本写入器。 |

### 另请参阅

* class [HugoFrontMatterSyntaxNode](../hugofrontmattersyntaxnode/)
* class [ChildFrontMatterSyntaxNode](../childfrontmattersyntaxnode/)
* package [com.aspose.html.toolkit.markdown.syntax.extensions](../../com.aspose.html.toolkit.markdown.syntax.extensions/)
* package [Aspose.HTML](../../)
