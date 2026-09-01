---
title: "IDocumentTraversal Interface"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.traversal.IDocumentTraversal interface. DocumentTraversal bevat methoden die iterators en tree‑walkers maken om een knooppunt en zijn kinderen te doorlopen in documentvolgorde, diepte‑eerste pre‑order traversering, wat gelijk is aan de volgorde waarin de start‑tags voorkomen in de tekstrepresentatie van het document. In DOM’s die de Traversal‑functie ondersteunen, zal DocumentTraversal worden geïmplementeerd door dezelfde objecten die de Document‑interface implementeren."
type: docs

url: /nl/java/com.aspose.html.dom.traversal/idocumenttraversal/
---
## IDocumentTraversal interface

DocumentTraversal bevat methoden die iterators en tree-walkers maken om een knoop en zijn kinderen te doorlopen in documentvolgorde (diepte‑eerste, pre‑order traversie, wat gelijk is aan de volgorde waarin de start‑tags voorkomen in de tekstrepresentatie van het document). In DOM's die de Traversal‑functie ondersteunen, zal DocumentTraversal worden geïmplementeerd door dezelfde objecten die de Document‑interface implementeren.

Zie ook de [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface IDocumentTraversal
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator)(Node) | Maak een nieuwe NodeIterator over de subboom die is geworteld bij het opgegeven knooppunt. |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_1)(Node, long) | Maak een nieuwe NodeIterator over de subboom die is geworteld bij het opgegeven knooppunt. |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_2)(Node, long, INodeFilter) | Maak een nieuwe NodeIterator over de subboom die is geworteld bij het opgegeven knooppunt. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker)(Node) | Maak een nieuwe TreeWalker over de subboom die is geworteld bij het opgegeven knooppunt. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_1)(Node, long) | Maak een nieuwe TreeWalker over de subboom die is geworteld bij het opgegeven knooppunt. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_2)(Node, long, INodeFilter) | Maak een nieuwe TreeWalker over de subboom die is geworteld bij het opgegeven knooppunt. |

### Zie ook

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
