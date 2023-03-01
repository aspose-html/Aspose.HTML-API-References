---
title: Interface INodeIterator
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Dom.Traversal.INodeIterator koppel. Iterators worden gebruikt om door een set knooppunten te stappen bijv. de set knooppunten in een NodeList de substructuur van het document die wordt beheerd door een bepaald knooppunt de resultaten van een query of een andere set knooppunten. De set te herhalen knooppunten wordt bepaald door de implementatie van de NodeIterator. DOM Level 2 specificeert een enkele NodeIteratorimplementatie voor documentvolgorde traversal van een documentsubstructuur. Instanties van deze iterators worden gemaakt door DocumentTraversal .createNodeIterator. aan te roepen
type: docs
weight: 2500
url: /nl/net/aspose.html.dom.traversal/inodeiterator/
---
## INodeIterator interface

Iterators worden gebruikt om door een set knooppunten te stappen, bijv. de set knooppunten in een NodeList, de substructuur van het document die wordt beheerd door een bepaald knooppunt, de resultaten van een query of een andere set knooppunten. De set te herhalen knooppunten wordt bepaald door de -implementatie van de NodeIterator. DOM Level 2 specificeert een enkele NodeIterator-implementatie voor documentvolgorde traversal van een documentsubstructuur. Instanties van deze iterators worden gemaakt door DocumentTraversal .createNodeIterator(). aan te roepen

Zie ook de[Documentobject Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @sinds DOM-niveau 2

```csharp
public interface INodeIterator : ITraversal
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [PointerBeforeReferenceNode](../../aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/) { get; } | De waarde van deze vlag bepaalt of de kinderen van entiteit referentieknooppunten zichtbaar zijn voor de iterator. Indien onwaar, zullen zij en hun afstammelingen worden afgewezen. Merk op dat deze weigering voorrang heeft op whatToShow en het filter. Merk ook op dat dit momenteel de enige situatie is waarin NodeIterators een volledige subboom kunnen verwerpen in plaats van afzonderlijke knooppunten overslaan. Om een weergave te maken van het document met entiteitsreferenties uitgebreid en het entiteitsreferentieknooppunt zelf niet bloot te leggen, use de whatToShow-vlaggen naar verberg de entiteitsreferentie node en stel expandEntityReferences in op true bij het maken van de iterator. Om een weergave te maken van het document met entiteitsreferentie -knooppunten maar zonder entiteitsuitbreiding, gebruikt u de whatToShow-vlaggen om het entiteitsreferentieknooppunt weer te geven en set expandEntityReferences naar false. |
| [ReferenceNode](../../aspose.html.dom.traversal/inodeiterator/referencenode/) { get; } | Het huidige referentieknooppunt. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Detach](../../aspose.html.dom.traversal/inodeiterator/detach/)() | Koppelt de NodeIterator los van de set waarover het itereerde , waarbij alle rekenbronnen worden vrijgegeven en de iterator in de INVALID-status wordt geplaatst. Nadat de ontkoppeling is aangeroepen, aanroepen naar nextNode of previousNode will de uitzondering INVALID_STATE_ERR. veroorzaken |
| [NextNode](../../aspose.html.dom.traversal/inodeiterator/nextnode/)() | Retourneert het volgende knooppunt in de set en verhoogt de positie van de iterator in de set. Nadat een NodeIterator is gemaakt, retourneert de eerste aanroep van nextNode() het eerste knooppunt in de set. |
| [PreviousNode](../../aspose.html.dom.traversal/inodeiterator/previousnode/)() | Retourneert het vorige knooppunt in de set en verplaatst de positie van de NodeIterator naar achteren in de set. |

### Zie ook

* interface [ITraversal](../itraversal/)
* naamruimte [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* montage [Aspose.HTML](../../)


