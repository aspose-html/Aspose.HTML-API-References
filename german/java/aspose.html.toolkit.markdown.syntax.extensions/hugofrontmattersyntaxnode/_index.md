---
title: "HugoFrontMatterSyntaxNode-Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.toolkit.markdown.syntax.extensions.HugoFrontMatterSyntaxNode Klasse. Definiert die Basisklasse HugoFrontMatterSyntaxNode"
type: docs

url: /de/java/com.aspose.html.toolkit.markdown.syntax.extensions/hugofrontmattersyntaxnode/
---
## HugoFrontMatterSyntaxNode class

Definiert die Basisklasse HugoFrontMatterSyntaxNode.

```java
public abstract class HugoFrontMatterSyntaxNode : BlockSyntaxNode
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getFirstChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/firstchild/) Gibt das erste Kind zurück. |
| abstract [getFrontMatterRootNode](../../com.aspose.html.toolkit.markdown.syntax.extensions/hugofrontmattersyntaxnode/frontmatterrootnode/) Gibt den RootNode zurück und setzt ihn |
| [getLastChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/lastchild/) Gibt das letzte Kind zurück. |
| [getNextSibling](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/nextsibling/) Gibt das nächste Geschwisterelement zurück. |
| [getParent](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/parent/) Gibt den übergeordneten Knoten zurück. |
| [getPreviousSibling](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/previoussibling/) Gibt das vorherige Geschwisterelement zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [accept](../../com.aspose.html.toolkit.markdown.syntax/blocksyntaxnode/accept/)(MarkdownSyntaxVisitor) | Definiert die Schnittstelle zum Akzeptieren des Besuchers. |
| [appendChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/appendchild/)(MarkdownSyntaxNode) | Füge ein Kindknoten hinzu. |
| [childNodes](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/childnodes/)() | Gibt die Sammlung der Kindknoten zurück. |
| [find](../../com.aspose.html.toolkit.markdown.syntax.extensions/hugofrontmattersyntaxnode/find/#find)(params String[]) | Definiert die Schnittstelle zum Finden von BaseSyntaxNode |
| abstract [Find&lt;T&gt;](../../com.aspose.html.toolkit.markdown.syntax.extensions/hugofrontmattersyntaxnode/find/#find_1)(params String[]) | Definiert die Schnittstelle zum Finden von T |
| [getLeadingTrivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getleadingtrivia/)() | Gibt die führenden Trivia zurück. |
| [getSyntaxTree](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/getsyntaxtree/)() | Gibt den Syntaxbaum zurück. |
| [getTrailingTrivia](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/gettrailingtrivia/)() | Gibt die nachfolgenden Trivia zurück. |
| [insertBefore](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/insertbefore/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | Vor dem Knoten einfügen. |
| [removeChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/removechild/)(MarkdownSyntaxNode) | Entferne das Kind. |
| [replaceChild](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/replacechild/)(MarkdownSyntaxNode, MarkdownSyntaxNode) | Ersetze den Kindknoten. |
| [toString](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/toString/)() | Überschreibe die ToString-Methode. |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(MarkdownTextWriter) | In MarkdownTextWriter schreiben. |
| [writeTo](../../com.aspose.html.toolkit.markdown.syntax/markdownsyntaxnode/writeto/)(TextWriter) | Knoten in TextWriter schreiben. |

### Siehe auch

* class [BlockSyntaxNode](../../com.aspose.html.toolkit.markdown.syntax/blocksyntaxnode/)
* package [com.aspose.html.toolkit.markdown.syntax.extensions](../../com.aspose.html.toolkit.markdown.syntax.extensions/)
* package [Aspose.HTML](../../)
