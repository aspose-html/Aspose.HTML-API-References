---
title: Interface IDocumentTraversal
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Dom.Traversal.IDocumentTraversal gränssnitt. DocumentTraversal innehåller metoder som skapar iteratorer och trädvandrare för att korsa en nod och dess underordnade i dokumentordning djup first preorder traversal vilket motsvarar den ordning i vilken starttaggarna förekommer i textrepresentationen av dokumentet. I DOMer som stöder genomgångsfunktionen kommer DocumentTraversal att implementeras av samma objekt som implementerar dokumentgränssnittet.
type: docs
weight: 2470
url: /sv/net/aspose.html.dom.traversal/idocumenttraversal/
---
## IDocumentTraversal interface

DocumentTraversal innehåller metoder som skapar iteratorer och trädvandrare för att korsa en nod och dess underordnade i dokumentordning (djup first, pre-order traversal, vilket motsvarar den ordning i vilken starttaggarna förekommer i textrepresentationen av dokumentet). I DOM:er som stöder genomgångsfunktionen, kommer DocumentTraversal att implementeras av samma objekt som implementerar dokumentgränssnittet.

Se även[Dokumentobjekt Modell (DOM) Nivå 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @sedan DOM nivå 2

```csharp
public interface IDocumentTraversal
```

## Metoder

| namn | Beskrivning |
| --- | --- |
| [CreateNodeIterator](../../aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator)(Node) | Skapa en ny NodeIterator över underträdet som är rotat på den specificerade noden. |
| [CreateNodeIterator](../../aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_1)(Node, long) | Skapa en ny NodeIterator över underträdet som är rotat på den specificerade noden. |
| [CreateNodeIterator](../../aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_2)(Node, long, INodeFilter) | Skapa en ny NodeIterator över underträdet som är rotat på den specificerade noden. |
| [CreateTreeWalker](../../aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker)(Node) | Skapa en ny TreeWalker över underträdet som är rotat vid den specificerade noden. |
| [CreateTreeWalker](../../aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_1)(Node, long) | Skapa en ny TreeWalker över underträdet som är rotat vid den specificerade noden. |
| [CreateTreeWalker](../../aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_2)(Node, long, INodeFilter) | Skapa en ny TreeWalker över underträdet som är rotat vid den specificerade noden. |

### Se även

* namnutrymme [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* hopsättning [Aspose.HTML](../../)


