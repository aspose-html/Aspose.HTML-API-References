---
title: Class MarkdownSyntaxNode
second_title: Aspose.HTML für .NET-API-Referenz
description: Aspose.Html.Toolkit.Markdown.Syntax.MarkdownSyntaxNode klas. Basisimplementierung des MarkdownSyntaxNode.
type: docs
weight: 5190
url: /de/net/aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/
---
## MarkdownSyntaxNode class

Basisimplementierung des MarkdownSyntaxNode.

```csharp
public abstract class MarkdownSyntaxNode : IWritable
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [FirstChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) { get; } | Das erste Kind bekommen. |
| [LastChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) { get; } | Hol dir das letzte Kind. |
| [NextSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) { get; } | Hol dir das nächste Geschwister. |
| [Parent](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) { get; } | Holen Sie sich den übergeordneten Knoten. |
| [PreviousSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) { get; } | Holen Sie sich das vorherige Geschwister. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [Accept](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/accept/)(MarkdownSyntaxVisitor) | Akzeptiere den Besucher. |
| [AppendChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(MarkdownSyntaxNode) | Untergeordneten Knoten anhängen. |
| [ChildNodes](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | Abrufen der untergeordneten Knotensammlung. |
| [GetLeadingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getleadingtrivia/)() | Holen Sie sich die führenden Wissenswertes. |
| [GetSyntaxTree](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getsyntaxtree/)() | Holen Sie sich den Syntaxbaum. |
| [GetTrailingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/gettrailingtrivia/)() | Holen Sie sich die abschließenden Wissenswertes. |
| [InsertBefore](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/insertbefore/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | Vor Knoten einfügen. |
| [RemoveChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/removechild/)(MarkdownSyntaxNode) | Entfernen Sie das Kind. |
| [ReplaceChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/replacechild/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | Ersetzen Sie den untergeordneten Knoten. |
| override [ToString](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/tostring/)() | ToString-Methode überschreiben. |
| virtual [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/#writeto)(MarkdownTextWriter) | In MarkdownTextWriter schreiben. |
| [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/#writeto_1)(TextWriter) | Knoten in Textschreiber schreiben. |

### Siehe auch

* interface [IWritable](../iwritable/)
* namensraum [Aspose.Html.Toolkit.Markdown.Syntax](../../aspose.html.toolkit.markdown.syntax/)
* Montage [Aspose.HTML](../../)


