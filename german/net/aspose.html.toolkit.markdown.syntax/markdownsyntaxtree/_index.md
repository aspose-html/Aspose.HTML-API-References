---
title: Class MarkdownSyntaxTree
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.Toolkit.Markdown.Syntax.MarkdownSyntaxTree klas. Repräsentiert den MarkdownSyntaxbaum.
type: docs
weight: 5220
url: /de/net/aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/
---
## MarkdownSyntaxTree class

Repräsentiert den Markdown-Syntaxbaum.

```csharp
public class MarkdownSyntaxTree : MarkdownSyntaxNode
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [MarkdownSyntaxTree](markdownsyntaxtree/#constructor)() | hat den MarkdownSyntaxTree erstellt. |
| [MarkdownSyntaxTree](markdownsyntaxtree/#constructor_1)(Configuration) | Erstellt den MarkdownSyntaxTree |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [FirstChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) { get; } | Das erste Kind bekommen. |
| [LastChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) { get; } | Hol dir das letzte Kind. |
| [NextSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) { get; } | Hol dir das nächste Geschwister. |
| [Parent](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) { get; } | Holen Sie sich den übergeordneten Knoten. |
| [PreviousSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) { get; } | Holen Sie sich das vorherige Geschwister. |
| [SyntaxFactory](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/syntaxfactory/) { get; } | Holen Sie sich die SyntaxFactory. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Accept](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/accept/)(MarkdownSyntaxVisitor) | Definiert die Schnittstelle zum Besuch von Knoten des Syntaxbaums. |
| [AppendChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(MarkdownSyntaxNode) | Untergeordneten Knoten anhängen. |
| [ChildNodes](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | Abrufen der untergeordneten Knotensammlung. |
| [CreateNodeIterator](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator)(MarkdownSyntaxNode) | Definiert die Schnittstelle zum Erstellen des Node-Iterators. |
| [CreateNodeIterator](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator_2)(MarkdownSyntaxNodeFilter) | Definiert die Schnittstelle zum Erstellen des Node-Iterators. |
| [CreateNodeIterator](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator_1)(MarkdownSyntaxNode, MarkdownSyntaxNodeFilter) | Definiert die Schnittstelle zum Erstellen des Node-Iterators. |
| [CreateTreeWalker](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker)(MarkdownSyntaxNode) | Definiert die Schnittstelle zum Erstellen des Treewalkers. |
| [CreateTreeWalker](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker_2)(MarkdownSyntaxNodeFilter) | Definiert die Schnittstelle zum Erstellen des Treewalkers. |
| [CreateTreeWalker](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker_1)(MarkdownSyntaxNode, MarkdownSyntaxNodeFilter) | Definiert die Schnittstelle zum Erstellen des Treewalkers. |
| [GetLeadingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getleadingtrivia/)() | Holen Sie sich die führenden Wissenswertes. |
| [GetSyntaxTree](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getsyntaxtree/)() | Holen Sie sich den Syntaxbaum. |
| [GetTrailingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/gettrailingtrivia/)() | Holen Sie sich die abschließenden Wissenswertes. |
| [InsertBefore](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/insertbefore/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | Vor Knoten einfügen. |
| [RemoveChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/removechild/)(MarkdownSyntaxNode) | Entfernen Sie das Kind. |
| [ReplaceChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/replacechild/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | Ersetzen Sie den untergeordneten Knoten. |
| [Save](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save)(Stream) | Speichert den Syntaxbaum im angegebenen Stream. |
| [Save](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save_2)(string) | Speichert den Syntaxbaum im angegebenen Pfad. |
| [Save](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save_1)(TextWriter) | Speichert den Syntaxbaum im angegebenen Writer. |
| override [ToString](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/tostring/)() | ToString-Methode überschreiben. |
| virtual [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(MarkdownTextWriter) | In MarkdownTextWriter schreiben. |
| [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(TextWriter) | Knoten in Textschreiber schreiben. |

### Siehe auch

* class [MarkdownSyntaxNode](../markdownsyntaxnode/)
* namensraum [Aspose.Html.Toolkit.Markdown.Syntax](../../aspose.html.toolkit.markdown.syntax/)
* Montage [Aspose.HTML](../../)


