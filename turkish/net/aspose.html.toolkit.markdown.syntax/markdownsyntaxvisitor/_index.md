---
title: Class MarkdownSyntaxVisitor
second_title: Aspose.HTML for .NET API Referansı
description: Aspose.Html.Toolkit.Markdown.Syntax.MarkdownSyntaxVisitor sınıf. Markdown sözdizimi ziyaretçisi için temel sınıf.
type: docs
weight: 5230
url: /tr/net/aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/
---
## MarkdownSyntaxVisitor class

Markdown sözdizimi ziyaretçisi için temel sınıf.

```csharp
public abstract class MarkdownSyntaxVisitor
```

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Visit](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visit/#visit)(MarkdownSyntaxNode) | ziyaret düğümü için arabirimi tanımlar. |
| [Visit](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visit/#visit_1)(MarkdownSyntaxTree) | Ziyaret sözdizimi ağacı için arabirimi tanımlar. |
| virtual [VisitAtxHeading](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitatxheading/)(AtxHeadingSyntaxNode) | Ziyaret için arayüzü tanımlar AtxHeadingSyntax. |
| virtual [VisitBlock](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitblock/)(BlockSyntaxNode) | Ziyaret bloğu için arayüzü tanımlar. |
| virtual [VisitBlockQuote](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitblockquote/)(BlockQuoteSyntaxNode) | BlockQuoteSyntax. ziyareti için arayüzü tanımlar. |
| virtual [VisitCharacterReference](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitcharacterreference/)(CharacterReferenceSyntaxNode) | Ziyaret için arabirimi tanımlar CharacterReferenceSyntax. |
| virtual [VisitCodeSpan](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitcodespan/)(CodeSpanSyntaxNode) | Ziyaret için arayüzü tanımlar CodeSpanSyntax. |
| virtual [VisitEmphasis](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitemphasis/)(EmphasisSyntaxNode) | Ziyaret için arayüzü tanımlar EmphasisSyntax. |
| virtual [VisitEmptyLine](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitemptyline/)(EmptyLineSyntaxNode) | Ziyaret metin satırı için arayüzü tanımlar. |
| virtual [VisitEscapedCharacter](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitescapedcharacter/)(EscapedCharacterSyntaxNode) | Ziyaret kaçış karakteri için arabirimi tanımlar. |
| virtual [VisitFencedCodeBlock](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitfencedcodeblock/)(FencedCodeBlockSyntaxNode) | Ziyaret için arabirimi tanımlar FencedCodeBlockSyntax. |
| virtual [VisitHtml](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visithtml/)(HTMLFragmentSyntax) | Ziyaret için arabirimi tanımlar HTMLFragmentSyntax. |
| virtual [VisitImage](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitimage/)(InlineImageSyntaxNode) | InlineImageSyntax. ziyareti için arabirimi tanımlar |
| virtual [VisitIndentedCodeBlock](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitindentedcodeblock/)(IndentedCodeBlockSyntaxNode) | IndentedCodeBlockSyntax. ziyareti için arabirimi tanımlar |
| virtual [VisitLineBreak](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlinebreak/#visitlinebreak)(HardBreakSyntaxNode) | Ziyaret için arayüzü tanımlar HardBreakSyntax. |
| virtual [VisitLineBreak](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlinebreak/#visitlinebreak_1)(SoftBreakSyntaxNode) | SoftBreakSyntax. ziyareti için arayüzü tanımlar. |
| virtual [VisitLink](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlink/#visitlink)(AutoLinkSyntaxNode) | AutoLinkSyntax. ziyareti için arayüzü tanımlar. |
| virtual [VisitLink](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlink/#visitlink_1)(InlineLinkSyntaxNode) | InlineLinkSyntax. ziyareti için arayüzü tanımlar |
| virtual [VisitLinkReferenceDefinition](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlinkreferencedefinition/)(LinkReferenceDefinitionSyntaxNode) | Ziyaret için arayüzü tanımlar LinkReferenceDefinitionSyntax. |
| virtual [VisitList](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlist/#visitlist)(OrderedListSyntaxNode) | OrderedListSyntax. ziyareti için arayüzü tanımlar |
| virtual [VisitList](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlist/#visitlist_1)(UnorderedListSyntaxNode) | Ziyaret için arayüzü tanımlar UnorderedListSyntax. |
| virtual [VisitListItem](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlistitem/)(ListItemSyntaxNode) | ListItemSyntax. ziyareti için arayüzü tanımlar. |
| virtual [VisitNodeList](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitnodelist/)(NodeList) | NodeList. ziyareti için arabirimi tanımlar. |
| virtual [VisitParagraph](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitparagraph/)(ParagraphSyntaxNode) | Ziyaret paragrafı için arayüzü tanımlar. |
| virtual [VisitReferenceImage](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitreferenceimage/)(ReferenceImageSyntaxNode) | Ziyaret için arabirimi tanımlar ReferenceImageSyntax. |
| virtual [VisitReferenceLink](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitreferencelink/)(ReferenceLinkSyntaxNode) | Ziyaret için arabirimi tanımlar ReferenceLinkSyntax. |
| virtual [VisitSetextHeading](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitsetextheading/)(SetextHeadingSyntaxNode) | Ziyaret için arayüzü tanımlar SetextHeadingSyntax. |
| virtual [VisitSyntaxNode](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitsyntaxnode/)(MarkdownSyntaxNode) | ziyaret düğümü için arabirimi tanımlar. |
| virtual [VisitSyntaxTree](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitsyntaxtree/)(MarkdownSyntaxTree) | MarkdownSyntaxTree. ziyareti için arayüzü tanımlar |
| virtual [VisitTable](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visittable/)(TableSyntaxNode) | Ziyaret için arabirimi tanımlar TableSyntax. |
| virtual [VisitText](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visittext/)(TextSyntaxNode) | Ziyaret metni sözdizimi için arabirimi tanımlar. |
| virtual [VisitThematicBreak](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitthematicbreak/)(ThematicBreakSyntaxNode) | ThematicBreakSyntax. ziyareti için arayüzü tanımlar |
| virtual [VisitWhitespace](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitwhitespace/)(WhitespaceSyntaxNode) | Beyaz Boşluk Sözdizimi ziyareti için arabirimi tanımlar. |

### Ayrıca bakınız

* ad alanı [Aspose.Html.Toolkit.Markdown.Syntax](../../aspose.html.toolkit.markdown.syntax/)
* toplantı [Aspose.HTML](../../)


