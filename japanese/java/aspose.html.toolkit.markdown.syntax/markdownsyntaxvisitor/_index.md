---
title: "MarkdownSyntaxVisitor クラス"
second_title: "Aspose.HTML for Java API リファレンス"
description: "com.aspose.html.toolkit.markdown.syntax.MarkdownSyntaxVisitor クラス。Markdown 構文ビジターの基底クラスです"
type: docs

url: /ja/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/
---
## MarkdownSyntaxVisitor class

Markdown構文ビジターの基底クラスです。

```java
public abstract class MarkdownSyntaxVisitor
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [visit](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visit/#visit)(MarkdownSyntaxNode) | ノード訪問のためのインターフェイスを定義します。 |
| [visit](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visit/#visit_1)(MarkdownSyntaxTree) | 構文ツリー訪問のためのインターフェイスを定義します。 |
| [visitAtxHeading](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitatxheading/)(AtxHeadingSyntaxNode) | AtxHeadingSyntax 訪問のためのインターフェイスを定義します。 |
| [visitBlock](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitblock/)(BlockSyntaxNode) | ブロック訪問のためのインターフェイスを定義します。 |
| [visitBlockQuote](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitblockquote/)(BlockQuoteSyntaxNode) | BlockQuoteSyntax 訪問のためのインターフェイスを定義します。 |
| [visitCharacterReference](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitcharacterreference/)(CharacterReferenceSyntaxNode) | CharacterReferenceSyntax 訪問のためのインターフェイスを定義します。 |
| [visitCodeSpan](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitcodespan/)(CodeSpanSyntaxNode) | CodeSpanSyntax 訪問のためのインターフェイスを定義します。 |
| [visitEmphasis](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitemphasis/)(EmphasisSyntaxNode) | EmphasisSyntax 訪問のためのインターフェイスを定義します。 |
| [visitEmptyLine](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitemptyline/)(EmptyLineSyntaxNode) | テキスト行訪問のためのインターフェイスを定義します。 |
| [visitEscapedCharacter](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitescapedcharacter/)(EscapedCharacterSyntaxNode) | エスケープ文字訪問のためのインターフェイスを定義します。 |
| [visitFencedCodeBlock](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitfencedcodeblock/)(FencedCodeBlockSyntaxNode) | FencedCodeBlockSyntax の訪問インターフェイスを定義します。 |
| [visitHtml](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visithtml/)(HTMLFragmentSyntax) | HTMLFragmentSyntax の訪問インターフェイスを定義します。 |
| [visitImage](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitimage/)(InlineImageSyntaxNode) | InlineImageSyntax の訪問インターフェイスを定義します。 |
| [visitIndentedCodeBlock](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitindentedcodeblock/)(IndentedCodeBlockSyntaxNode) | IndentedCodeBlockSyntax の訪問インターフェイスを定義します。 |
| [visitLineBreak](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlinebreak/#visitlinebreak)(HardBreakSyntaxNode) | HardBreakSyntax の訪問インターフェイスを定義します。 |
| [visitLineBreak](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlinebreak/#visitlinebreak_1)(SoftBreakSyntaxNode) | SoftBreakSyntax の訪問インターフェイスを定義します。 |
| [visitLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlink/#visitlink)(AutoLinkSyntaxNode) | AutoLinkSyntax の訪問インターフェイスを定義します。 |
| [visitLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlink/#visitlink_1)(InlineLinkSyntaxNode) | InlineLinkSyntax の訪問インターフェイスを定義します。 |
| [visitLinkReferenceDefinition](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlinkreferencedefinition/)(LinkReferenceDefinitionSyntaxNode) | LinkReferenceDefinitionSyntax の訪問インターフェイスを定義します。 |
| [visitList](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlist/#visitlist)(OrderedListSyntaxNode) | OrderedListSyntax の訪問インターフェイスを定義します。 |
| [visitList](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlist/#visitlist_1)(UnorderedListSyntaxNode) | UnorderedListSyntax の訪問インターフェイスを定義します。 |
| [visitListItem](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlistitem/)(ListItemSyntaxNode) | ListItemSyntax の訪問インターフェイスを定義します。 |
| [visitNodeList](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitnodelist/)(NodeList) | NodeList の訪問インターフェイスを定義します。 |
| [visitParagraph](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitparagraph/)(ParagraphSyntaxNode) | paragraph の訪問インターフェイスを定義します。 |
| [visitReferenceImage](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitreferenceimage/)(ReferenceImageSyntaxNode) | ReferenceImageSyntax の訪問インターフェイスを定義します。 |
| [visitReferenceLink](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitreferencelink/)(ReferenceLinkSyntaxNode) | ReferenceLinkSyntax の訪問インターフェイスを定義します。 |
| [visitSetextHeading](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitsetextheading/)(SetextHeadingSyntaxNode) | SetextHeadingSyntax の訪問インターフェイスを定義します。 |
| [visitSyntaxNode](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitsyntaxnode/)(MarkdownSyntaxNode) | ノード訪問のためのインターフェイスを定義します。 |
| [visitSyntaxTree](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitsyntaxtree/)(MarkdownSyntaxTree) | MarkdownSyntaxTree の訪問インターフェイスを定義します。 |
| [visitTable](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visittable/)(TableSyntaxNode) | TableSyntax の訪問インターフェイスを定義します。 |
| [visitText](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visittext/)(TextSyntaxNode) | text syntax の訪問インターフェイスを定義します。 |
| [visitThematicBreak](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitthematicbreak/)(ThematicBreakSyntaxNode) | ThematicBreakSyntax の訪問インターフェイスを定義します。 |
| [visitWhitespace](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitwhitespace/)(WhitespaceSyntaxNode) | Whitespace Syntax の訪問インターフェイスを定義します。 |

### 関連項目

* package [com.aspose.html.toolkit.markdown.syntax](../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../)
