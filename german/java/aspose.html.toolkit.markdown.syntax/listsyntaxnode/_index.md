---
title: "ListSyntaxNode Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.toolkit.markdown.syntax.ListSyntaxNode Klasse. Basiskomponente des ListSyntaxNode"
type: docs

url: /de/java/com.aspose.html.toolkit.markdown.syntax/listsyntaxnode/
---
## ListSyntaxNode class

Basisimplementierung des ListSyntaxNode.

```java
public abstract class ListSyntaxNode : ContainerBlockSyntaxNode
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getFirstChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) Gibt das erste Kind zurück. |
| [getLastChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) Gibt das letzte Kind zurück. |
| [getNextSibling](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) Gibt das nächste Geschwisterelement zurück. |
| [getParent](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) Gibt den übergeordneten Knoten zurück. |
| [getPreviousSibling](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) Gibt das vorherige Geschwisterelement zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [accept](../../com.aspose.html.toolkit.markdown.syntax/blocksyntaxnode/accept/)(MarkdownSyntaxVisitor) | Definiert die Schnittstelle für das Akzeptieren des Besuchers. |
| [appendChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(MarkdownSyntaxNode) | Füge ein Kindknoten hinzu. |
| [childNodes](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | Gibt die Sammlung der Kindknoten zurück. |
| [getLeadingTrivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getleadingtrivia/)() | Gibt die führenden Trivia zurück. |
| [getSyntaxTree](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getsyntaxtree/)() | Gibt den Syntaxbaum zurück. |
| [getTrailingTrivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/gettrailingtrivia/)() | Gibt die nachfolgenden Trivia zurück. |
| [insertBefore](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/insertbefore/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | Füge vor dem Knoten ein. |
| [isTight](../../com.aspose.html.toolkit.markdown.syntax/listsyntaxnode/istight/)() | Definiert die Schnittstelle zum Abrufen, ob es eng ist. |
| [removeChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/removechild/)(MarkdownSyntaxNode) | Entferne das Kind. |
| [replaceChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/replacechild/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | Ersetze den Kindknoten. |
| [toString](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/toString/)() | Überschreibe die ToString-Methode. |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(MarkdownTextWriter) | Schreibe in MarkdownTextWriter. |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(TextWriter) | Schreibe Knoten in den Textwriter. |

### Siehe auch

* class [ContainerBlockSyntaxNode](../containerblocksyntaxnode/)
* package [com.aspose.html.toolkit.markdown.syntax](../../com.aspose.html.toolkit.markdown.syntax/)
* package [Aspose.HTML](../../)
