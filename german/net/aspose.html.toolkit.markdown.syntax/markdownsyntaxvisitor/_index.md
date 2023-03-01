---
title: Class MarkdownSyntaxVisitor
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.Toolkit.Markdown.Syntax.MarkdownSyntaxVisitor klas. Die Basisklasse für MarkdownSyntaxBesucher.
type: docs
weight: 5230
url: /de/net/aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/
---
## MarkdownSyntaxVisitor class

Die Basisklasse für Markdown-Syntax-Besucher.

```csharp
public abstract class MarkdownSyntaxVisitor
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Visit](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visit/#visit)(MarkdownSyntaxNode) | Definiert die Schnittstelle für den Besuchsknoten. |
| [Visit](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visit/#visit_1)(MarkdownSyntaxTree) | Definiert die Schnittstelle für den Besuch des Syntaxbaums. |
| virtual [VisitAtxHeading](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitatxheading/)(AtxHeadingSyntaxNode) | Definiert die Schnittstelle für den Besuch von AtxHeadingSyntax. |
| virtual [VisitBlock](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitblock/)(BlockSyntaxNode) | Definiert die Schnittstelle für den Besuchsblock. |
| virtual [VisitBlockQuote](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitblockquote/)(BlockQuoteSyntaxNode) | Definiert die Schnittstelle für den Besuch von BlockQuoteSyntax. |
| virtual [VisitCharacterReference](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitcharacterreference/)(CharacterReferenceSyntaxNode) | Definiert die Schnittstelle für den Besuch CharacterReferenceSyntax. |
| virtual [VisitCodeSpan](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitcodespan/)(CodeSpanSyntaxNode) | Definiert die Schnittstelle für den Besuch von CodeSpanSyntax. |
| virtual [VisitEmphasis](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitemphasis/)(EmphasisSyntaxNode) | Definiert die Schnittstelle für den Besuch EmphasisSyntax. |
| virtual [VisitEmptyLine](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitemptyline/)(EmptyLineSyntaxNode) | Definiert die Schnittstelle für die Besuchstextzeile. |
| virtual [VisitEscapedCharacter](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitescapedcharacter/)(EscapedCharacterSyntaxNode) | Definiert die Schnittstelle für das Besuchs-Escape-Zeichen. |
| virtual [VisitFencedCodeBlock](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitfencedcodeblock/)(FencedCodeBlockSyntaxNode) | Definiert die Schnittstelle für den Besuch von FencedCodeBlockSyntax. |
| virtual [VisitHtml](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visithtml/)(HTMLFragmentSyntax) | Definiert die Schnittstelle für den Besuch HTMLFragmentSyntax. |
| virtual [VisitImage](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitimage/)(InlineImageSyntaxNode) | Definiert die Schnittstelle für den Besuch von InlineImageSyntax. |
| virtual [VisitIndentedCodeBlock](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitindentedcodeblock/)(IndentedCodeBlockSyntaxNode) | Definiert die Schnittstelle für den Besuch IndentedCodeBlockSyntax. |
| virtual [VisitLineBreak](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlinebreak/#visitlinebreak)(HardBreakSyntaxNode) | Definiert die Schnittstelle für den Besuch von HardBreakSyntax. |
| virtual [VisitLineBreak](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlinebreak/#visitlinebreak_1)(SoftBreakSyntaxNode) | Definiert die Schnittstelle für den Besuch von SoftBreakSyntax. |
| virtual [VisitLink](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlink/#visitlink)(AutoLinkSyntaxNode) | Definiert die Schnittstelle für den Besuch von AutoLinkSyntax. |
| virtual [VisitLink](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlink/#visitlink_1)(InlineLinkSyntaxNode) | Definiert die Schnittstelle für den Besuch von InlineLinkSyntax. |
| virtual [VisitLinkReferenceDefinition](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlinkreferencedefinition/)(LinkReferenceDefinitionSyntaxNode) | Definiert die Schnittstelle für den Besuch LinkReferenceDefinitionSyntax. |
| virtual [VisitList](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlist/#visitlist)(OrderedListSyntaxNode) | Definiert die Schnittstelle für den Besuch OrderedListSyntax. |
| virtual [VisitList](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlist/#visitlist_1)(UnorderedListSyntaxNode) | Definiert die Schnittstelle für den Besuch von UnorderedListSyntax. |
| virtual [VisitListItem](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlistitem/)(ListItemSyntaxNode) | Definiert die Schnittstelle für den Besuch ListItemSyntax. |
| virtual [VisitNodeList](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitnodelist/)(NodeList) | Definiert die Schnittstelle für den Besuch von NodeList. |
| virtual [VisitParagraph](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitparagraph/)(ParagraphSyntaxNode) | Definiert die Schnittstelle für den Besuchsabschnitt. |
| virtual [VisitReferenceImage](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitreferenceimage/)(ReferenceImageSyntaxNode) | Definiert die Schnittstelle für den Besuch ReferenceImageSyntax. |
| virtual [VisitReferenceLink](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitreferencelink/)(ReferenceLinkSyntaxNode) | Definiert die Schnittstelle für den Besuch ReferenceLinkSyntax. |
| virtual [VisitSetextHeading](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitsetextheading/)(SetextHeadingSyntaxNode) | Definiert die Schnittstelle für den Besuch von SetextHeadingSyntax. |
| virtual [VisitSyntaxNode](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitsyntaxnode/)(MarkdownSyntaxNode) | Definiert die Schnittstelle für den Besuchsknoten. |
| virtual [VisitSyntaxTree](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitsyntaxtree/)(MarkdownSyntaxTree) | Definiert die Schnittstelle für den Besuch von MarkdownSyntaxTree. |
| virtual [VisitTable](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visittable/)(TableSyntaxNode) | Definiert die Schnittstelle für den Besuch TableSyntax. |
| virtual [VisitText](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visittext/)(TextSyntaxNode) | Definiert die Schnittstelle für die Besuchstextsyntax. |
| virtual [VisitThematicBreak](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitthematicbreak/)(ThematicBreakSyntaxNode) | Definiert die Schnittstelle für den Besuch von ThematicBreakSyntax. |
| virtual [VisitWhitespace](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitwhitespace/)(WhitespaceSyntaxNode) | Definiert die Schnittstelle für den Besuch Whitespace-Syntax. |

### Siehe auch

* namensraum [Aspose.Html.Toolkit.Markdown.Syntax](../../aspose.html.toolkit.markdown.syntax/)
* Montage [Aspose.HTML](../../)


