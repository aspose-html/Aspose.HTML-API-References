---
title: Class HugoFrontMatterSyntaxNode
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Toolkit.Markdown.Syntax.Extensions.HugoFrontMatterSyntaxNode klass. Definierar basklassen HugoFrontMatterSyntaxNode
type: docs
weight: 4910
url: /sv/net/aspose.html.toolkit.markdown.syntax.extensions/hugofrontmattersyntaxnode/
---
## HugoFrontMatterSyntaxNode class

Definierar basklassen HugoFrontMatterSyntaxNode

```csharp
public abstract class HugoFrontMatterSyntaxNode : BlockSyntaxNode
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [FirstChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) { get; } | Skaffa det första barnet. |
| abstract [FrontMatterRootNode](../../aspose.html.toolkit.markdown.syntax.extensions/hugofrontmattersyntaxnode/frontmatterrootnode/) { get; } | Hämta och ställ in RootNode |
| [LastChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) { get; } | Skaffa det sista barnet. |
| [NextSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) { get; } | Skaffa nästa syskon. |
| [Parent](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) { get; } | Hämta den överordnade noden. |
| [PreviousSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) { get; } | Skaffa föregående syskon. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [Accept](../../aspose.html.toolkit.markdown.syntax/blocksyntaxnode/accept/)(MarkdownSyntaxVisitor) | Definierar gränssnittet för acceptera besökare. |
| [AppendChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(MarkdownSyntaxNode) | Lägg till underordnad nod. |
| [ChildNodes](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | Hämta samlingen av underordnade noder. |
| [Find](../../aspose.html.toolkit.markdown.syntax.extensions/hugofrontmattersyntaxnode/find/#find)(params string[]) | Definierar gränssnittet för find BaseSyntaxNode |
| abstract [Find&lt;T&gt;](../../aspose.html.toolkit.markdown.syntax.extensions/hugofrontmattersyntaxnode/find/#find_1)(params string[]) | Definierar gränssnittet för hitta T |
| [GetLeadingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getleadingtrivia/)() | Få den ledande trivian. |
| [GetSyntaxTree](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getsyntaxtree/)() | Hämta syntaxträdet. |
| [GetTrailingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/gettrailingtrivia/)() | Skaffa den efterföljande trivian. |
| [InsertBefore](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/insertbefore/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | Infoga före nod. |
| [RemoveChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/removechild/)(MarkdownSyntaxNode) | Ta bort barnet. |
| [ReplaceChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/replacechild/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | Byt ut den underordnade noden. |
| override [ToString](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/tostring/)() | Åsidosätt ToString-metoden. |
| virtual [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(MarkdownTextWriter) | Skriv till MarkdownTextWriter. |
| [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(TextWriter) | Skriv noder till textskrivare. |

### Se även

* class [BlockSyntaxNode](../../aspose.html.toolkit.markdown.syntax/blocksyntaxnode/)
* namnutrymme [Aspose.Html.Toolkit.Markdown.Syntax.Extensions](../../aspose.html.toolkit.markdown.syntax.extensions/)
* hopsättning [Aspose.HTML](../../)


