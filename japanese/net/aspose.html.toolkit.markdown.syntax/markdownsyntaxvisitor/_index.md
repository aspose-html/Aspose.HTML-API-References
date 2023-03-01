---
title: Class MarkdownSyntaxVisitor
second_title: Aspose.HTML for .NET API リファレンス
description: Aspose.Html.Toolkit.Markdown.Syntax.MarkdownSyntaxVisitor クラス. マークダウン構文のビジターの基本クラス.
type: docs
weight: 5230
url: /ja/net/aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/
---
## MarkdownSyntaxVisitor class

マークダウン構文のビジターの基本クラス.

```csharp
public abstract class MarkdownSyntaxVisitor
```

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Visit](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visit/#visit)(MarkdownSyntaxNode) | 訪問ノードのインターフェースを定義します。 |
| [Visit](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visit/#visit_1)(MarkdownSyntaxTree) | 訪問構文ツリーのインターフェースを定義します。 |
| virtual [VisitAtxHeading](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitatxheading/)(AtxHeadingSyntaxNode) | 訪問 AtxHeadingSyntax. のインターフェイスを定義します |
| virtual [VisitBlock](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitblock/)(BlockSyntaxNode) | 訪問ブロックのインターフェイスを定義します。 |
| virtual [VisitBlockQuote](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitblockquote/)(BlockQuoteSyntaxNode) | にアクセスするためのインターフェイスを定義します BlockQuoteSyntax. |
| virtual [VisitCharacterReference](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitcharacterreference/)(CharacterReferenceSyntaxNode) | CharacterReferenceSyntax. にアクセスするためのインターフェイスを定義します。 |
| virtual [VisitCodeSpan](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitcodespan/)(CodeSpanSyntaxNode) | 訪問 CodeSpanSyntax. のインターフェースを定義します |
| virtual [VisitEmphasis](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitemphasis/)(EmphasisSyntaxNode) | Visit EmphasisSyntax. のインターフェイスを定義します |
| virtual [VisitEmptyLine](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitemptyline/)(EmptyLineSyntaxNode) | 訪問テキスト行のインターフェースを定義します. |
| virtual [VisitEscapedCharacter](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitescapedcharacter/)(EscapedCharacterSyntaxNode) | 訪問エスケープ文字のインターフェイスを定義します。 |
| virtual [VisitFencedCodeBlock](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitfencedcodeblock/)(FencedCodeBlockSyntaxNode) | FencedCodeBlockSyntax. にアクセスするためのインターフェースを定義します。 |
| virtual [VisitHtml](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visithtml/)(HTMLFragmentSyntax) | にアクセスするためのインターフェースを定義します HTMLFragmentSyntax. |
| virtual [VisitImage](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitimage/)(InlineImageSyntaxNode) | にアクセスするためのインターフェイスを定義します InlineImageSyntax. |
| virtual [VisitIndentedCodeBlock](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitindentedcodeblock/)(IndentedCodeBlockSyntaxNode) | にアクセスするためのインターフェイスを定義します IndentedCodeBlockSyntax. |
| virtual [VisitLineBreak](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlinebreak/#visitlinebreak)(HardBreakSyntaxNode) | は HardBreakSyntax. にアクセスするためのインターフェイスを定義します |
| virtual [VisitLineBreak](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlinebreak/#visitlinebreak_1)(SoftBreakSyntaxNode) | 訪問 SoftBreakSyntax. のインターフェイスを定義します |
| virtual [VisitLink](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlink/#visitlink)(AutoLinkSyntaxNode) | は AutoLinkSyntax. にアクセスするためのインターフェイスを定義します |
| virtual [VisitLink](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlink/#visitlink_1)(InlineLinkSyntaxNode) | は InlineLinkSyntax. にアクセスするためのインターフェイスを定義します |
| virtual [VisitLinkReferenceDefinition](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlinkreferencedefinition/)(LinkReferenceDefinitionSyntaxNode) | 訪問用のインターフェースを定義します LinkReferenceDefinitionSyntax. |
| virtual [VisitList](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlist/#visitlist)(OrderedListSyntaxNode) | Visit OrderedListSyntax. のインターフェイスを定義します |
| virtual [VisitList](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlist/#visitlist_1)(UnorderedListSyntaxNode) | Visit UnorderedListSyntax. のインターフェイスを定義します |
| virtual [VisitListItem](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlistitem/)(ListItemSyntaxNode) | 訪問 ListItemSyntax. のインターフェイスを定義します |
| virtual [VisitNodeList](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitnodelist/)(NodeList) | 訪問 NodeList. のインターフェイスを定義します |
| virtual [VisitParagraph](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitparagraph/)(ParagraphSyntaxNode) | 訪問段落のインターフェイスを定義します。 |
| virtual [VisitReferenceImage](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitreferenceimage/)(ReferenceImageSyntaxNode) | にアクセスするためのインターフェイスを定義します ReferenceImageSyntax. |
| virtual [VisitReferenceLink](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitreferencelink/)(ReferenceLinkSyntaxNode) | にアクセスするためのインターフェイスを定義します ReferenceLinkSyntax. |
| virtual [VisitSetextHeading](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitsetextheading/)(SetextHeadingSyntaxNode) | にアクセスするためのインターフェイスを定義します SetextHeadingSyntax. |
| virtual [VisitSyntaxNode](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitsyntaxnode/)(MarkdownSyntaxNode) | 訪問ノードのインターフェースを定義します。 |
| virtual [VisitSyntaxTree](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitsyntaxtree/)(MarkdownSyntaxTree) | にアクセスするためのインターフェイスを定義します MarkdownSyntaxTree. |
| virtual [VisitTable](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visittable/)(TableSyntaxNode) | にアクセスするためのインターフェイスを定義します TableSyntax. |
| virtual [VisitText](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visittext/)(TextSyntaxNode) | 訪問テキスト構文のインターフェイスを定義します。 |
| virtual [VisitThematicBreak](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitthematicbreak/)(ThematicBreakSyntaxNode) | 訪問 ThematicBreakSyntax. のインターフェイスを定義します |
| virtual [VisitWhitespace](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitwhitespace/)(WhitespaceSyntaxNode) | 訪問ホワイトスペース構文のインターフェイスを定義します。 |

### 関連項目

* 名前空間 [Aspose.Html.Toolkit.Markdown.Syntax](../../aspose.html.toolkit.markdown.syntax/)
* 組み立て [Aspose.HTML](../../)


