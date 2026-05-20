---
title: "IDocumentTraversal‑gränssnitt"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.traversal.IDocumentTraversal‑gränssnitt. DocumentTraversal innehåller metoder som skapar iteratorer och tree‑walkers för att gå igenom en nod och dess barn i dokumentordning, djup‑först för‑ordningstraversering som motsvarar den ordning i vilken starttaggarna förekommer i dokumentets textrepresentation. I DOM‑er som stöder Traversal‑funktionen kommer DocumentTraversal att implementeras av samma objekt som implementerar Document‑gränssnittet."
type: docs

url: /sv/java/com.aspose.html.dom.traversal/idocumenttraversal/
---
## IDocumentTraversal interface

DocumentTraversal innehåller metoder som skapar iteratorer och tree-walkers för att traversera en nod och dess barn i dokumentordning (djup först, förordnings‑traversering, vilket är ekvivalent med den ordning i vilken starttaggarna förekommer i dokumentets textrepresentation). I DOM‑er som stödjer Traversal‑funktionen kommer DocumentTraversal att implementeras av samma objekt som implementerar Document‑gränssnittet.

Se även [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface IDocumentTraversal
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator)(Node) | Skapa en ny NodeIterator över delträdet som har den angivna noden som rot. |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_1)(Node, long) | Skapa en ny NodeIterator över delträdet som har den angivna noden som rot. |
| [createNodeIterator](../../com.aspose.html.dom.traversal/idocumenttraversal/createnodeiterator/#createnodeiterator_2)(Node, long, INodeFilter) | Skapa en ny NodeIterator över delträdet som har den angivna noden som rot. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker)(Node) | Skapa en ny TreeWalker över delträdet som har den angivna noden som rot. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_1)(Node, long) | Skapa en ny TreeWalker över delträdet som har den angivna noden som rot. |
| [createTreeWalker](../../com.aspose.html.dom.traversal/idocumenttraversal/createtreewalker/#createtreewalker_2)(Node, long, INodeFilter) | Skapa en ny TreeWalker över delträdet som har den angivna noden som rot. |

### Se även

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
