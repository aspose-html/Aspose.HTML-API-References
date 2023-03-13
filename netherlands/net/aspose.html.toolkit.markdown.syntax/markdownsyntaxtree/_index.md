---
title: Class MarkdownSyntaxTree
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Toolkit.Markdown.Syntax.MarkdownSyntaxTree klas. Vertegenwoordigen de Markdownsyntaxisstructuur.
type: docs
weight: 5220
url: /nl/net/aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/
---
## MarkdownSyntaxTree class

Vertegenwoordigen de Markdown-syntaxisstructuur.

```csharp
public class MarkdownSyntaxTree : MarkdownSyntaxNode
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [MarkdownSyntaxTree](markdownsyntaxtree/#constructor)() | De MarkdownSyntaxTree gemaakt. |
| [MarkdownSyntaxTree](markdownsyntaxtree/#constructor_1)(Configuration) | Maakt de MarkdownSyntaxTree |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [FirstChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) { get; } | Krijg het eerste kind. |
| [LastChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) { get; } | Haal het laatste kind. |
| [NextSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) { get; } | Haal de volgende broer of zus. |
| [Parent](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) { get; } | Haal het bovenliggende knooppunt op. |
| [PreviousSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) { get; } | Haal de vorige broer of zus. |
| [SyntaxFactory](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/syntaxfactory/) { get; } | Download de SyntaxFactory. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| override [Accept](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/accept/)(MarkdownSyntaxVisitor) | Definieert de interface voor het bezoeken van knooppunten van de syntaxisboom. |
| [AppendChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(MarkdownSyntaxNode) | Onderliggend knooppunt toevoegen. |
| [ChildNodes](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | Haal de verzameling onderliggende knooppunten op. |
| [CreateNodeIterator](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator)(MarkdownSyntaxNode) | Definieert de interface voor het maken van de knooppuntiterator. |
| [CreateNodeIterator](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator_2)(MarkdownSyntaxNodeFilter) | Definieert de interface voor het maken van de knooppuntiterator. |
| [CreateNodeIterator](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator_1)(MarkdownSyntaxNode, MarkdownSyntaxNodeFilter) | Definieert de interface voor het maken van de knooppuntiterator. |
| [CreateTreeWalker](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker)(MarkdownSyntaxNode) | Definieert de interface voor het maken van de boomwandelaar. |
| [CreateTreeWalker](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker_2)(MarkdownSyntaxNodeFilter) | Definieert de interface voor het maken van de boomwandelaar. |
| [CreateTreeWalker](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker_1)(MarkdownSyntaxNode, MarkdownSyntaxNodeFilter) | Definieert de interface voor het maken van de boomwandelaar. |
| [GetLeadingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getleadingtrivia/)() | Verkrijg de belangrijkste trivia. |
| [GetSyntaxTree](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getsyntaxtree/)() | Haal de syntaxisstructuur op. |
| [GetTrailingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/gettrailingtrivia/)() | Verkrijg de Trailing trivia. |
| [InsertBefore](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/insertbefore/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | Invoegen voor knooppunt. |
| [RemoveChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/removechild/)(MarkdownSyntaxNode) | Verwijder het kind. |
| [ReplaceChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/replacechild/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | Vervang het onderliggende knooppunt. |
| [Save](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save)(Stream) | Slaat de syntaxisstructuur op in de opgegeven stream. |
| [Save](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save_2)(string) | Slaat de syntaxisstructuur op in het opgegeven pad. |
| [Save](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save_1)(TextWriter) | Slaat de syntaxisstructuur op in de opgegeven schrijver. |
| override [ToString](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/tostring/)() | ToString-methode overschrijven. |
| virtual [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(MarkdownTextWriter) | Schrijf naar MarkdownTextWriter. |
| [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(TextWriter) | Schrijf knooppunten naar tekstschrijver. |

### Zie ook

* class [MarkdownSyntaxNode](../markdownsyntaxnode/)
* naamruimte [Aspose.Html.Toolkit.Markdown.Syntax](../../aspose.html.toolkit.markdown.syntax/)
* montage [Aspose.HTML](../../)


