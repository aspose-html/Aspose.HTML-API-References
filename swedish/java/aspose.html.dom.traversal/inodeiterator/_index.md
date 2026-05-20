---
title: "INodeIterator‑gränssnitt"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.traversal.INodeIterator‑gränssnitt. Iteratorer används för att gå igenom en uppsättning noder, t.ex. uppsättningen noder i en NodeList, dokumentdelträdet som styrs av en viss Node, resultatet av en fråga eller någon annan noduppsättning. Vilka noder som ska itereras bestäms av implementationen av NodeIterator. DOM nivå 2 specificerar en enda NodeIterator‑implementation för dokumentordningens traversering av ett dokumentdelträd. Instanser av dessa iteratorer skapas genom att anropa DocumentTraversal .createNodeIterator."
type: docs

url: /sv/java/com.aspose.html.dom.traversal/inodeiterator/
---
## INodeIterator interface

Iteratorer används för att gå igenom en mängd noder, t.ex. mängden noder i en NodeList, dokumentets underträd som styrs av en viss Node, resultatet av en fråga eller någon annan mängd noder. Mängden noder som ska itereras bestäms av implementationen av NodeIterator. DOM Level 2 specificerar en enda NodeIterator‑implementation för dokumentordningstraversering av ett dokumentunderträd. Instanser av dessa iteratorer skapas genom att anropa DocumentTraversal .createNodeIterator().

Se även [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface INodeIterator : ITraversal
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getPointerBeforeReferenceNode](../../com.aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/) Värdet på denna flagga bestämmer om barnen till entitetsreferensnoder är synliga för iteratorn. Om falskt kommer de och deras undernoder att avvisas. Observera att detta avslag har företräde framför whatToShow och filtret. Notera också att detta för närvarande är det enda fallet där NodeIterators kan avvisa ett helt delträd istället för att hoppa över enskilda noder. För att skapa en vy av dokumentet där entitetsreferenser är expanderade och inte avslöjar själva entitetsreferensnoden, använd whatToShow‑flaggorna för att dölja entitetsreferensnoden och sätt expandEntityReferences till true när iteratorn skapas. För att skapa en vy av dokumentet som har entitetsreferensnoder men ingen entitetsutvidgning, använd whatToShow‑flaggorna för att visa entitetsreferensnoden och sätt expandEntityReferences till false. |
| [getReferenceNode](../../com.aspose.html.dom.traversal/inodeiterator/referencenode/) Den aktuella referensnoden. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [detach](../../com.aspose.html.dom.traversal/inodeiterator/detach/)() | Kopplar bort NodeIterator från den mängd den itererade över, frigör eventuella beräkningsresurser och placerar iteratorn i det OGILTIGA tillståndet. Efter att detach har anropats kommer anrop till nextNode eller previousNode att kasta undantaget INVALID_STATE_ERR. |
| [nextNode](../../com.aspose.html.dom.traversal/inodeiterator/nextnode/)() | Returnerar nästa nod i mängden och avancerar iteratorns position i mängden. Efter att en NodeIterator har skapats returnerar det första anropet till nextNode() den första noden i mängden. |
| [previousNode](../../com.aspose.html.dom.traversal/inodeiterator/previousnode/)() | Returnerar föregående nod i mängden och flyttar NodeIteratorns position bakåt i mängden. |

### Se även

* interface [ITraversal](../itraversal/)
* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
