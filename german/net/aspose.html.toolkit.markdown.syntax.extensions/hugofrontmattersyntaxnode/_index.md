---
title: Class HugoFrontMatterSyntaxNode
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.Toolkit.Markdown.Syntax.Extensions.HugoFrontMatterSyntaxNode klas. Definiert die Basisklasse HugoFrontMatterSyntaxNode
type: docs
weight: 4910
url: /de/net/aspose.html.toolkit.markdown.syntax.extensions/hugofrontmattersyntaxnode/
---
## HugoFrontMatterSyntaxNode class

Definiert die Basisklasse HugoFrontMatterSyntaxNode

```csharp
public abstract class HugoFrontMatterSyntaxNode : BlockSyntaxNode
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [FirstChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) { get; } | Das erste Kind bekommen. |
| abstract [FrontMatterRootNode](../../aspose.html.toolkit.markdown.syntax.extensions/hugofrontmattersyntaxnode/frontmatterrootnode/) { get; } | Holen und setzen Sie den RootNode |
| [LastChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) { get; } | Hol dir das letzte Kind. |
| [NextSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) { get; } | Hol dir das nächste Geschwister. |
| [Parent](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) { get; } | Holen Sie sich den übergeordneten Knoten. |
| [PreviousSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) { get; } | Holen Sie sich das vorherige Geschwister. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Accept](../../aspose.html.toolkit.markdown.syntax/blocksyntaxnode/accept/)(MarkdownSyntaxVisitor) | Definiert die Schnittstelle zum Akzeptieren von Besuchern. |
| [AppendChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(MarkdownSyntaxNode) | Untergeordneten Knoten anhängen. |
| [ChildNodes](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | Abrufen der untergeordneten Knotensammlung. |
| [Find](../../aspose.html.toolkit.markdown.syntax.extensions/hugofrontmattersyntaxnode/find/#find)(params string[]) | Definiert die Schnittstelle für find BaseSyntaxNode |
| abstract [Find&lt;T&gt;](../../aspose.html.toolkit.markdown.syntax.extensions/hugofrontmattersyntaxnode/find/#find_1)(params string[]) | Definiert die Schnittstelle für find T |
| [GetLeadingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getleadingtrivia/)() | Holen Sie sich die führenden Wissenswertes. |
| [GetSyntaxTree](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getsyntaxtree/)() | Holen Sie sich den Syntaxbaum. |
| [GetTrailingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/gettrailingtrivia/)() | Holen Sie sich die abschließenden Wissenswertes. |
| [InsertBefore](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/insertbefore/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | Vor Knoten einfügen. |
| [RemoveChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/removechild/)(MarkdownSyntaxNode) | Entfernen Sie das Kind. |
| [ReplaceChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/replacechild/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | Ersetzen Sie den untergeordneten Knoten. |
| override [ToString](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/tostring/)() | ToString-Methode überschreiben. |
| virtual [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(MarkdownTextWriter) | In MarkdownTextWriter schreiben. |
| [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(TextWriter) | Knoten in Textschreiber schreiben. |

### Siehe auch

* class [BlockSyntaxNode](../../aspose.html.toolkit.markdown.syntax/blocksyntaxnode/)
* namensraum [Aspose.Html.Toolkit.Markdown.Syntax.Extensions](../../aspose.html.toolkit.markdown.syntax.extensions/)
* Montage [Aspose.HTML](../../)


