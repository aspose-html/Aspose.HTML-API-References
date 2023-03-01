---
title: Class MarkdownSyntaxTree
second_title: Aspose.HTML per riferimento API .NET
description: Aspose.Html.Toolkit.Markdown.Syntax.MarkdownSyntaxTree classe. Rappresenta lalbero della sintassi Markdown.
type: docs
weight: 5220
url: /it/net/aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/
---
## MarkdownSyntaxTree class

Rappresenta l'albero della sintassi Markdown.

```csharp
public class MarkdownSyntaxTree : MarkdownSyntaxNode
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [MarkdownSyntaxTree](markdownsyntaxtree/#constructor)() | Creato MarkdownSyntaxTree. |
| [MarkdownSyntaxTree](markdownsyntaxtree/#constructor_1)(Configuration) | Crea il MarkdownSyntaxTree |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [FirstChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) { get; } | Ottieni il primo figlio. |
| [LastChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) { get; } | Ottieni l'ultimo figlio. |
| [NextSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) { get; } | Ottieni il prossimo fratello. |
| [Parent](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) { get; } | Ottieni il nodo padre. |
| [PreviousSibling](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) { get; } | Ottieni il fratello precedente. |
| [SyntaxFactory](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/syntaxfactory/) { get; } | Ottieni SyntaxFactory. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Accept](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/accept/)(MarkdownSyntaxVisitor) | Definisce l'interfaccia per visitare i nodi dell'albero della sintassi. |
| [AppendChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(MarkdownSyntaxNode) | Aggiungi nodo figlio. |
| [ChildNodes](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | Ottieni la raccolta dei nodi figlio. |
| [CreateNodeIterator](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator)(MarkdownSyntaxNode) | Definisce l'interfaccia per la creazione dell'iteratore del nodo. |
| [CreateNodeIterator](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator_2)(MarkdownSyntaxNodeFilter) | Definisce l'interfaccia per la creazione dell'iteratore del nodo. |
| [CreateNodeIterator](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator_1)(MarkdownSyntaxNode, MarkdownSyntaxNodeFilter) | Definisce l'interfaccia per la creazione dell'iteratore del nodo. |
| [CreateTreeWalker](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker)(MarkdownSyntaxNode) | Definisce l'interfaccia per creare il tree walker. |
| [CreateTreeWalker](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker_2)(MarkdownSyntaxNodeFilter) | Definisce l'interfaccia per creare il tree walker. |
| [CreateTreeWalker](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker_1)(MarkdownSyntaxNode, MarkdownSyntaxNodeFilter) | Definisce l'interfaccia per creare il tree walker. |
| [GetLeadingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getleadingtrivia/)() | Ottieni le principali curiosità. |
| [GetSyntaxTree](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getsyntaxtree/)() | Ottieni l'albero della sintassi. |
| [GetTrailingTrivia](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/gettrailingtrivia/)() | Ottieni la curiosità finale. |
| [InsertBefore](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/insertbefore/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | Inserisci prima del nodo. |
| [RemoveChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/removechild/)(MarkdownSyntaxNode) | Rimuovi il bambino. |
| [ReplaceChild](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/replacechild/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | Sostituisci il nodo figlio. |
| [Save](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save)(Stream) | Salva l'albero della sintassi nel flusso specificato. |
| [Save](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save_2)(string) | Salva l'albero della sintassi nel percorso specificato. |
| [Save](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save_1)(TextWriter) | Salva l'albero della sintassi nel writer specificato. |
| override [ToString](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/tostring/)() | Sostituisci il metodo ToString. |
| virtual [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(MarkdownTextWriter) | Scrivi su MarkdownTextWriter. |
| [WriteTo](../../aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(TextWriter) | Scrivi nodi su text writer. |

### Guarda anche

* class [MarkdownSyntaxNode](../markdownsyntaxnode/)
* spazio dei nomi [Aspose.Html.Toolkit.Markdown.Syntax](../../aspose.html.toolkit.markdown.syntax/)
* assemblea [Aspose.HTML](../../)


