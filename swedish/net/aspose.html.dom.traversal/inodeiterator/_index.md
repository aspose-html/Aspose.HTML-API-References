---
title: Interface INodeIterator
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Dom.Traversal.INodeIterator gränssnitt. Iteratorer används för att stega igenom en uppsättning noder t.ex. uppsättningen av noder i en NodeList dokumentunderträdet som styrs av en viss Nod resultaten av en fråga eller någon annan uppsättning av noder. Uppsättningen av noder som ska itereras bestäms av implementeringen av NodeIterator. DOM Level 2 specificerar en enda NodeIteratorimplementering för dokumentorder genomgång av ett dokumentunderträd. Förekomster av dessa iteratorer skapas genom att anropa DocumentTraversal .createNodeIterator.
type: docs
weight: 2500
url: /sv/net/aspose.html.dom.traversal/inodeiterator/
---
## INodeIterator interface

Iteratorer används för att stega igenom en uppsättning noder, t.ex. uppsättningen av noder i en NodeList, dokumentunderträdet som styrs av en viss Nod, resultaten av en fråga eller någon annan uppsättning av noder. Uppsättningen av noder som ska itereras bestäms av -implementeringen av NodeIterator. DOM Level 2 specificerar en enda NodeIterator-implementering för dokument-order genomgång av ett dokumentunderträd. Förekomster av dessa iteratorer skapas genom att anropa DocumentTraversal .createNodeIterator().

Se även[Dokumentobjekt Modell (DOM) Nivå 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @sedan DOM nivå 2

```csharp
public interface INodeIterator : ITraversal
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [PointerBeforeReferenceNode](../../aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/) { get; } | Värdet på denna flagga avgör om underordnade av referensnoder för entity är synliga för iteratorn. Om falskt kommer de och deras ättlingar att avvisas. Observera att detta avslag har företräde framför whatToShow och filtret. Notera också att detta för närvarande är den enda situationen där NodeIterators kan avvisa ett fullständigt underträd snarare än hoppa över enskilda noder. För att skapa en vy av dokumentet som har entity references expanderat och inte exponerar entitetsreferensen för själva entitetsreferensnoden what00S, använd flagg_hows_x dölj entitetsreferensen node och ställ expandEntityReferences till true när du skapar iteratorn . För att skapa en vy av dokumentet som har entitetsreferens -noder men ingen entitetsexpansion, använd whatToShow flags för att visa entitetsreferensnoden och set expandEntityReferences to false. |
| [ReferenceNode](../../aspose.html.dom.traversal/inodeiterator/referencenode/) { get; } | Den aktuella referensnoden. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Detach](../../aspose.html.dom.traversal/inodeiterator/detach/)() | Kopplar bort NodeIterator från uppsättningen som den itererade över, frigör alla beräkningsresurser och placerar iterator i INVALID-tillståndet. Efter att detach har anropats kommer anrop till nextNode eller previousNode att höja undantaget INVALID_STATE_ERR. |
| [NextNode](../../aspose.html.dom.traversal/inodeiterator/nextnode/)() | Returnerar nästa nod i uppsättningen och flyttar fram positionen för iteratorn i uppsättningen. Efter att en NodeIterator har skapats returnerar det första anropet till nextNode() den första noden i setet. |
| [PreviousNode](../../aspose.html.dom.traversal/inodeiterator/previousnode/)() | Returnerar föregående nod i uppsättningen och flyttar positionen för NodeIterator bakåt i uppsättningen. |

### Se även

* interface [ITraversal](../itraversal/)
* namnutrymme [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* hopsättning [Aspose.HTML](../../)


