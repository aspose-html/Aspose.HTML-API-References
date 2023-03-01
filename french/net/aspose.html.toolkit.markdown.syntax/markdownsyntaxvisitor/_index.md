---
title: Class MarkdownSyntaxVisitor
second_title: Référence de l'API Aspose.HTML pour .NET
description: Aspose.Html.Toolkit.Markdown.Syntax.MarkdownSyntaxVisitor classe. La classe de base pour le visiteur de syntaxe de démarquage.
type: docs
weight: 5230
url: /fr/net/aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/
---
## MarkdownSyntaxVisitor class

La classe de base pour le visiteur de syntaxe de démarquage.

```csharp
public abstract class MarkdownSyntaxVisitor
```

## Méthodes

| Nom | La description |
| --- | --- |
| [Visit](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visit/#visit)(MarkdownSyntaxNode) | Définit l'interface pour le nœud de visite. |
| [Visit](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visit/#visit_1)(MarkdownSyntaxTree) | Définit l'interface pour l'arborescence de syntaxe de visite. |
| virtual [VisitAtxHeading](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitatxheading/)(AtxHeadingSyntaxNode) | Définit l'interface de visite AtxHeadingSyntax. |
| virtual [VisitBlock](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitblock/)(BlockSyntaxNode) | Définit l'interface pour le bloc de visite. |
| virtual [VisitBlockQuote](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitblockquote/)(BlockQuoteSyntaxNode) | Définit l'interface pour visiter BlockQuoteSyntax. |
| virtual [VisitCharacterReference](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitcharacterreference/)(CharacterReferenceSyntaxNode) | Définit l'interface de visite CharacterReferenceSyntax. |
| virtual [VisitCodeSpan](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitcodespan/)(CodeSpanSyntaxNode) | Définit l'interface pour visiter CodeSpanSyntax. |
| virtual [VisitEmphasis](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitemphasis/)(EmphasisSyntaxNode) | Définit l'interface de visite EmphasisSyntax. |
| virtual [VisitEmptyLine](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitemptyline/)(EmptyLineSyntaxNode) | Définit l'interface pour la ligne de texte de visite. |
| virtual [VisitEscapedCharacter](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitescapedcharacter/)(EscapedCharacterSyntaxNode) | Définit l'interface pour le caractère d'échappement de visite. |
| virtual [VisitFencedCodeBlock](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitfencedcodeblock/)(FencedCodeBlockSyntaxNode) | Définit l'interface pour visiter FencedCodeBlockSyntax. |
| virtual [VisitHtml](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visithtml/)(HTMLFragmentSyntax) | Définit l'interface pour visiter HTMLFragmentSyntax. |
| virtual [VisitImage](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitimage/)(InlineImageSyntaxNode) | Définit l'interface de visite InlineImageSyntax. |
| virtual [VisitIndentedCodeBlock](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitindentedcodeblock/)(IndentedCodeBlockSyntaxNode) | Définit l'interface pour visiter IndentedCodeBlockSyntax. |
| virtual [VisitLineBreak](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlinebreak/#visitlinebreak)(HardBreakSyntaxNode) | Définit l'interface pour visiter HardBreakSyntax. |
| virtual [VisitLineBreak](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlinebreak/#visitlinebreak_1)(SoftBreakSyntaxNode) | Définit l'interface pour visiter SoftBreakSyntax. |
| virtual [VisitLink](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlink/#visitlink)(AutoLinkSyntaxNode) | Définit l'interface pour visiter AutoLinkSyntax. |
| virtual [VisitLink](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlink/#visitlink_1)(InlineLinkSyntaxNode) | Définit l'interface de visite InlineLinkSyntax. |
| virtual [VisitLinkReferenceDefinition](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlinkreferencedefinition/)(LinkReferenceDefinitionSyntaxNode) | Définit l'interface de visite LinkReferenceDefinitionSyntax. |
| virtual [VisitList](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlist/#visitlist)(OrderedListSyntaxNode) | Définit l'interface pour la visite OrderedListSyntax. |
| virtual [VisitList](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlist/#visitlist_1)(UnorderedListSyntaxNode) | Définit l'interface pour la visite UnorderedListSyntax. |
| virtual [VisitListItem](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitlistitem/)(ListItemSyntaxNode) | Définit l'interface pour la visite ListItemSyntax. |
| virtual [VisitNodeList](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitnodelist/)(NodeList) | Définit l'interface pour visiter NodeList. |
| virtual [VisitParagraph](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitparagraph/)(ParagraphSyntaxNode) | Définit l'interface pour le paragraphe de visite. |
| virtual [VisitReferenceImage](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitreferenceimage/)(ReferenceImageSyntaxNode) | Définit l'interface pour la visite ReferenceImageSyntax. |
| virtual [VisitReferenceLink](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitreferencelink/)(ReferenceLinkSyntaxNode) | Définit l'interface pour la visite ReferenceLinkSyntax. |
| virtual [VisitSetextHeading](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitsetextheading/)(SetextHeadingSyntaxNode) | Définit l'interface de visite SetextHeadingSyntax. |
| virtual [VisitSyntaxNode](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitsyntaxnode/)(MarkdownSyntaxNode) | Définit l'interface pour le nœud de visite. |
| virtual [VisitSyntaxTree](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitsyntaxtree/)(MarkdownSyntaxTree) | Définit l'interface de visite MarkdownSyntaxTree. |
| virtual [VisitTable](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visittable/)(TableSyntaxNode) | Définit l'interface pour visiter TableSyntax. |
| virtual [VisitText](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visittext/)(TextSyntaxNode) | Définit l'interface pour la syntaxe du texte de visite. |
| virtual [VisitThematicBreak](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitthematicbreak/)(ThematicBreakSyntaxNode) | Définit l'interface de visite ThematicBreakSyntax. |
| virtual [VisitWhitespace](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxvisitor/visitwhitespace/)(WhitespaceSyntaxNode) | Définit l'interface pour la visite Whitespace Syntax. |

### Voir également

* espace de noms [Aspose.Html.Toolkit.Markdown.Syntax](../../aspose.html.toolkit.markdown.syntax/)
* Assemblée [Aspose.HTML](../../)


