---
title: Class LeafBlockSyntaxNode
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Toolkit.Markdown.Syntax.LeafBlockSyntaxNode klas. Basisimplementatie van de LeafBlockSyntaxNode.
type: docs
weight: 5090
url: /nl/net/aspose.html.toolkit.markdown.syntax/leafblocksyntaxnode/
---
## LeafBlockSyntaxNode class

Basisimplementatie van de LeafBlockSyntaxNode.

```csharp
public abstract class LeafBlockSyntaxNode : BlockSyntaxNode
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [FirstChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) { get; } | Krijg het eerste kind. |
| [LastChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) { get; } | Haal het laatste kind. |
| [NextSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) { get; } | Haal de volgende broer of zus. |
| [Parent](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) { get; } | Haal het bovenliggende knooppunt op. |
| [PreviousSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) { get; } | Haal de vorige broer of zus. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| override [Accept](../../aspose.html.toolkit.markdown.syntax/blocksyntaxnode/accept/)(MarkdownSyntaxVisitor) | Definieert de interface voor het accepteren van bezoekers. |
| [AppendChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(MarkdownSyntaxNode) | Onderliggend knooppunt toevoegen. |
| [ChildNodes](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | Haal de verzameling onderliggende knooppunten op. |
| [GetLeadingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getleadingtrivia/)() | Verkrijg de belangrijkste trivia. |
| [GetSyntaxTree](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getsyntaxtree/)() | Haal de syntaxisstructuur op. |
| [GetTrailingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/gettrailingtrivia/)() | Verkrijg de Trailing trivia. |
| [InsertBefore](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/insertbefore/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | Invoegen voor knooppunt. |
| [RemoveChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/removechild/)(MarkdownSyntaxNode) | Verwijder het kind. |
| [ReplaceChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/replacechild/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | Vervang het onderliggende knooppunt. |
| override [ToString](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/tostring/)() | ToString-methode overschrijven. |
| virtual [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(MarkdownTextWriter) | Schrijf naar MarkdownTextWriter. |
| [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(TextWriter) | Schrijf knooppunten naar tekstschrijver. |

### Zie ook

* class [BlockSyntaxNode](../blocksyntaxnode/)
* naamruimte [Aspose.Html.Toolkit.Markdown.Syntax](../../aspose.html.toolkit.markdown.syntax/)
* montage [Aspose.HTML](../../)

