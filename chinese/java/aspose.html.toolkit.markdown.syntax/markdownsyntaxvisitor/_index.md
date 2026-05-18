---
title: "MarkdownSyntaxVisitor 类"
second_title: "Aspose.HTML for Java API 参考"
description: "com.aspose.html.toolkit.markdown.syntax.MarkdownSyntaxVisitor 类。markdown 语法访问者的基类"
type: docs

url: /zh/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/
---
## MarkdownSyntaxVisitor class

markdown 语法访问器的基类。

```java
public abstract class MarkdownSyntaxVisitor
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [visit](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visit/#visit)(MarkdownSyntaxNode) | 定义访问节点的接口。 |
| [visit](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visit/#visit_1)(MarkdownSyntaxTree) | 定义访问语法树的接口。 |
| [visitAtxHeading](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitatxheading/)(AtxHeadingSyntaxNode) | 定义访问 AtxHeadingSyntax 的接口。 |
| [visitBlock](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitblock/)(BlockSyntaxNode) | 定义访问块的接口。 |
| [visitBlockQuote](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitblockquote/)(BlockQuoteSyntaxNode) | 定义访问 BlockQuoteSyntax 的接口。 |
| [visitCharacterReference](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitcharacterreference/)(CharacterReferenceSyntaxNode) | 定义访问 CharacterReferenceSyntax 的接口。 |
| [visitCodeSpan](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitcodespan/)(CodeSpanSyntaxNode) | 定义访问 CodeSpanSyntax 的接口。 |
| [visitEmphasis](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitemphasis/)(EmphasisSyntaxNode) | 定义访问 EmphasisSyntax 的接口。 |
| [visitEmptyLine](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitemptyline/)(EmptyLineSyntaxNode) | 定义访问文本行的接口。 |
| [visitEscapedCharacter](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitescapedcharacter/)(EscapedCharacterSyntaxNode) | 定义访问转义字符的接口。 |
| [visitFencedCodeBlock](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitfencedcodeblock/)(FencedCodeBlockSyntaxNode) | 定义用于访问 FencedCodeBlockSyntax 的接口。 |
| [visitHtml](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visithtml/)(HTMLFragmentSyntax) | 定义用于访问 HTMLFragmentSyntax 的接口。 |
| [visitImage](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitimage/)(InlineImageSyntaxNode) | 定义用于访问 InlineImageSyntax 的接口。 |
| [visitIndentedCodeBlock](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitindentedcodeblock/)(IndentedCodeBlockSyntaxNode) | 定义用于访问 IndentedCodeBlockSyntax 的接口。 |
| [visitLineBreak](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlinebreak/#visitlinebreak)(HardBreakSyntaxNode) | 定义用于访问 HardBreakSyntax 的接口。 |
| [visitLineBreak](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlinebreak/#visitlinebreak_1)(SoftBreakSyntaxNode) | 定义用于访问 SoftBreakSyntax 的接口。 |
| [visitLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlink/#visitlink)(AutoLinkSyntaxNode) | 定义用于访问 AutoLinkSyntax 的接口。 |
| [visitLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlink/#visitlink_1)(InlineLinkSyntaxNode) | 定义用于访问 InlineLinkSyntax 的接口。 |
| [visitLinkReferenceDefinition](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlinkreferencedefinition/)(LinkReferenceDefinitionSyntaxNode) | 定义用于访问 LinkReferenceDefinitionSyntax 的接口。 |
| [visitList](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlist/#visitlist)(OrderedListSyntaxNode) | 定义用于访问 OrderedListSyntax 的接口。 |
| [visitList](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlist/#visitlist_1)(UnorderedListSyntaxNode) | 定义用于访问 UnorderedListSyntax 的接口。 |
| [visitListItem](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlistitem/)(ListItemSyntaxNode) | 定义用于访问 ListItemSyntax 的接口。 |
| [visitNodeList](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitnodelist/)(NodeList) | 定义用于访问 NodeList 的接口。 |
| [visitParagraph](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitparagraph/)(ParagraphSyntaxNode) | 定义用于访问段落的接口。 |
| [visitReferenceImage](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitreferenceimage/)(ReferenceImageSyntaxNode) | 定义用于访问 ReferenceImageSyntax 的接口。 |
| [visitReferenceLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitreferencelink/)(ReferenceLinkSyntaxNode) | 定义用于访问 ReferenceLinkSyntax 的接口。 |
| [visitSetextHeading](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitsetextheading/)(SetextHeadingSyntaxNode) | 定义用于访问 SetextHeadingSyntax 的接口。 |
| [visitSyntaxNode](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitsyntaxnode/)(MarkdownSyntaxNode) | 定义访问节点的接口。 |
| [visitSyntaxTree](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitsyntaxtree/)(MarkdownSyntaxTree) | 定义用于访问 MarkdownSyntaxTree 的接口。 |
| [visitTable](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visittable/)(TableSyntaxNode) | 定义用于访问 TableSyntax 的接口。 |
| [visitText](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visittext/)(TextSyntaxNode) | 定义用于访问文本语法的接口。 |
| [visitThematicBreak](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitthematicbreak/)(ThematicBreakSyntaxNode) | 定义用于访问 ThematicBreakSyntax 的接口。 |
| [visitWhitespace](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitwhitespace/)(WhitespaceSyntaxNode) | 定义用于访问空白语法的接口。 |

### 另请参阅

* package [com.aspose.html.toolkit.markdown.syntax](../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../)
