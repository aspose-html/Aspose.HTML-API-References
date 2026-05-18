---
title: "MarkdownSyntaxTree Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.toolkit.markdown.syntax.MarkdownSyntaxTree Klasse. Stellt den Markdown‑Syntaxbaum dar"
type: docs

url: /de/java/com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/
---
## MarkdownSyntaxTree class

Stellt den Markdown Syntax Tree dar.

```java
public class MarkdownSyntaxTree : MarkdownSyntaxNode
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [MarkdownSyntaxTree](markdownsyntaxtree/#constructor)() | Erstellte den MarkdownSyntaxTree. |
| [MarkdownSyntaxTree](markdownsyntaxtree/#constructor_1)(Configuration) | Erstellt den MarkdownSyntaxTree |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getFirstChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) Gibt das erste Kind zurück. |
| [getLastChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) Gibt das letzte Kind zurück. |
| [getNextSibling](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) Gibt das nächste Geschwisterelement zurück. |
| [getParent](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) Gibt den übergeordneten Knoten zurück. |
| [getPreviousSibling](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) Gibt das vorherige Geschwisterelement zurück. |
| [getSyntaxFactory](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/syntaxfactory/) Ruft die SyntaxFactory ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [accept](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/accept/)(MarkdownSyntaxVisitor) | Definiert die Schnittstelle zum Durchlaufen von Knoten des Syntaxbaums. |
| [appendChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(MarkdownSyntaxNode) | Füge ein Kindknoten hinzu. |
| [childNodes](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | Gibt die Sammlung der Kindknoten zurück. |
| [createNodeIterator](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator)(MarkdownSyntaxNode) | Definiert die Schnittstelle zur Erstellung des Knoten‑Iterators. |
| [createNodeIterator](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator_2)(MarkdownSyntaxNodeFilter) | Definiert die Schnittstelle zur Erstellung des Knoten‑Iterators. |
| [createNodeIterator](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createnodeiterator/#createnodeiterator_1)(MarkdownSyntaxNode, MarkdownSyntaxNodeFilter) | Definiert die Schnittstelle zur Erstellung des Knoten‑Iterators. |
| [createTreeWalker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker)(MarkdownSyntaxNode) | Definiert die Schnittstelle zur Erstellung des Baum‑Walkers. |
| [createTreeWalker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker_2)(MarkdownSyntaxNodeFilter) | Definiert die Schnittstelle zur Erstellung des Baum‑Walkers. |
| [createTreeWalker](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/createtreewalker/#createtreewalker_1)(MarkdownSyntaxNode, MarkdownSyntaxNodeFilter) | Definiert die Schnittstelle zur Erstellung des Baum‑Walkers. |
| [getLeadingTrivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getleadingtrivia/)() | Gibt die führenden Trivia zurück. |
| [getSyntaxTree](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getsyntaxtree/)() | Gibt den Syntaxbaum zurück. |
| [getTrailingTrivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/gettrailingtrivia/)() | Gibt die nachfolgenden Trivia zurück. |
| [insertBefore](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/insertbefore/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | Vor dem Knoten einfügen. |
| [removeChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/removechild/)(MarkdownSyntaxNode) | Entferne das Kind. |
| [replaceChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/replacechild/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | Ersetze den Kindknoten. |
| [save](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save)(Stream) | Speichert den Syntaxbaum in den angegebenen Stream. |
| [save](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save_2)(String) | Speichert den Syntaxbaum im angegebenen Pfad. |
| [save](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxtree/save/#save_1)(TextWriter) | Speichert den Syntaxbaum im angegebenen Writer. |
| [toString](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/toString/)() | Überschreibe die ToString-Methode. |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(MarkdownTextWriter) | In MarkdownTextWriter schreiben. |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(TextWriter) | Knoten in TextWriter schreiben. |

### Siehe auch

* class [MarkdownSyntaxNode](../markdownsyntaxnode/)
* package [com.aspose.html.toolkit.markdown.syntax](../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../)
