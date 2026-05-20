---
title: "ITreeWalker‑gränssnitt"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.traversal.ITreeWalker‑gränssnitt. TreeWalker‑objekt används för att navigera i ett dokumentträd eller underträd med den vy av dokumentet som definieras av deras whatToShow‑flaggor och eventuellt filter. Alla funktioner som utför navigation med en TreeWalker kommer automatiskt att stödja vilken vy som helst som definieras av en TreeWalker."
type: docs

url: /sv/java/com.aspose.html.dom.traversal/itreewalker/
---
## ITreeWalker interface

TreeWalker‑objekt används för att navigera i ett dokumentträd eller underträd med hjälp av den vy av dokumentet som definieras av deras whatToShow‑flaggor och filter (om sådant finns). Alla funktioner som utför navigation med en TreeWalker kommer automatiskt att stödja vilken vy som helst som definieras av en TreeWalker.

Att utelämna noder från den logiska vyn av ett underträd kan resultera i en struktur som är avsevärt annorlunda än samma underträd i det kompletta, ofiltrerade dokumentet. Noder som är syskon i TreeWalker‑vyn kan vara barn till olika, vida åtskilda noder i den ursprungliga vyn. Till exempel, tänk på ett NodeFilter som hoppar över alla noder förutom Text‑noder och rotnoden i ett dokument. I den logiska vyn som resultat blir alla textnoder syskon och visas som direkta barn till rotnoden, oavsett hur djupt den ursprungliga dokumentstrukturen är inbäddad.

Se även [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface ITreeWalker : ITraversal
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
[getCurrentNode]
[setCurrentNode] The node at which the TreeWalker is currently positioned. Alterations to the DOM tree may cause the current node to no longer be accepted by the TreeWalker's associated filter. currentNode may also be explicitly set to any node, whether or not it is within the subtree specified by the root node or would be accepted by the filter and whatToShow flags. Further traversal occurs relative to currentNode even if it is not part of the current view, by applying the filters in the requested direction; if no traversal is possible, currentNode is not changed. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [firstChild](../../com.aspose.html.dom.traversal/itreewalker/firstchild/)() | Flyttar TreeWalker till det första synliga barnet till den aktuella noden och returnerar den nya noden. Om den aktuella noden saknar synliga barn returneras null och den aktuella noden behålls. |
| [lastChild](../../com.aspose.html.dom.traversal/itreewalker/lastchild/)() | Flyttar TreeWalker till det sista synliga barnet till den aktuella noden och returnerar den nya noden. Om den aktuella noden saknar synliga barn returneras null och den aktuella noden behålls. |
| [nextNode](../../com.aspose.html.dom.traversal/itreewalker/nextnode/)() | Flyttar TreeWalker till nästa synliga nod i dokumentordning relativt den aktuella noden och returnerar den nya noden. Om den aktuella noden saknar nästa nod, eller om sökningen efter nextNode försöker gå uppåt från TreeWalkers rotnod, returneras null och den aktuella noden behålls. |
| [nextSibling](../../com.aspose.html.dom.traversal/itreewalker/nextsibling/)() | Flyttar TreeWalker till nästa syskon till den aktuella noden och returnerar den nya noden. Om den aktuella noden saknar synligt nästa syskon returneras null och den aktuella noden behålls. |
| [parentNode](../../com.aspose.html.dom.traversal/itreewalker/parentnode/)() | Flyttar till och returnerar den närmaste synliga föräldranoden till den aktuella noden. Om sökningen efter parentNode försöker gå uppåt från TreeWalkers rotnod, eller om den misslyckas med att hitta en synlig föräldranod, behåller metoden den aktuella positionen och returnerar null. |
| [previousNode](../../com.aspose.html.dom.traversal/itreewalker/previousnode/)() | Flyttar TreeWalker till den föregående synliga noden i dokumentordning relativt den aktuella noden och returnerar den nya noden. Om den aktuella noden inte har någon föregående nod, eller om sökningen efter previousNode försöker gå uppåt från TreeWalkerns rotnod, returneras null och den aktuella noden behålls. |
| [previousSibling](../../com.aspose.html.dom.traversal/itreewalker/previoussibling/)() | Flyttar TreeWalker till den föregående syskonnoden till den aktuella noden och returnerar den nya noden. Om den aktuella noden inte har någon synlig föregående syskonnod, returneras null och den aktuella noden behålls. |

### Se även

* interface [ITraversal](../itraversal/)
* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
