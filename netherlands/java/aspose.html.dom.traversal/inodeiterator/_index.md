---
title: "INodeIterator Interface"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.traversal.INodeIterator interface. Iterators worden gebruikt om door een verzameling knooppunten te stappen, bijvoorbeeld de verzameling knooppunten in een NodeList, de document‑subboom die wordt beheerd door een bepaald Node, de resultaten van een query of elke andere verzameling knooppunten. De te itereren verzameling knooppunten wordt bepaald door de implementatie van de NodeIterator. DOM Level 2 specificeert één NodeIterator‑implementatie voor documentvolgorde‑traversering van een document‑subboom. Exemplaren van deze iterators worden gecreëerd door DocumentTraversal .createNodeIterator aan te roepen."
type: docs

url: /nl/java/com.aspose.html.dom.traversal/inodeiterator/
---
## INodeIterator interface

Iterators worden gebruikt om door een verzameling knopen te stappen, bv. de verzameling knopen in een NodeList, de document‑subboom beheerd door een specifieke Node, de resultaten van een query, of elke andere verzameling knopen. De te itereren verzameling knopen wordt bepaald door de implementatie van de NodeIterator. DOM Level 2 specificeert één NodeIterator‑implementatie voor documentvolgorde‑traversie van een document‑subboom. Instanties van deze iterators worden gecreëerd door DocumentTraversal .createNodeIterator() aan te roepen.

Zie ook de [Document object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface INodeIterator : ITraversal
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getPointerBeforeReferenceNode](../../com.aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/) De waarde van deze vlag bepaalt of de kinderen van entiteitsreferentie‑knooppunten zichtbaar zijn voor de iterator. Als false, worden zij en hun afstammelingen afgewezen. Merk op dat deze afwijzing voorrang heeft boven whatToShow en het filter. Let ook op dat dit momenteel de enige situatie is waarin NodeIterators een volledige subboom kunnen afwijzen in plaats van individuele knooppunten over te slaan. Om een weergave van het document te produceren waarin entiteitsreferenties zijn uitgeklapt en het entiteitsreferentie‑knooppunt zelf niet wordt blootgesteld, gebruik je de whatToShow‑vlaggen om het entiteitsreferentie‑knooppunt te verbergen en stel je expandEntityReferences in op true bij het maken van de iterator. Om een weergave van het document te produceren met entiteitsreferentie‑knooppunten maar zonder entiteitsuitbreiding, gebruik je de whatToShow‑vlaggen om het entiteitsreferentie‑knooppunt te tonen en stel je expandEntityReferences in op false. |
| [getReferenceNode](../../com.aspose.html.dom.traversal/inodeiterator/referencenode/) Het huidige referentie‑knooppunt. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [detach](../../com.aspose.html.dom.traversal/inodeiterator/detach/)() | Ontkoppelt de NodeIterator van de verzameling die hij heeft doorlopen, waardoor eventuele computationele bronnen worden vrijgegeven en de iterator in de STATUS INVALID wordt geplaatst. Nadat detach is aangeroepen, zullen oproepen naar nextNode of previousNode de uitzondering INVALID_STATE_ERR veroorzaken. |
| [nextNode](../../com.aspose.html.dom.traversal/inodeiterator/nextnode/)() | Retourneert het volgende knooppunt in de verzameling en verschuift de positie van de iterator in de verzameling. Nadat een NodeIterator is aangemaakt, retourneert de eerste oproep van nextNode() het eerste knooppunt in de verzameling. |
| [previousNode](../../com.aspose.html.dom.traversal/inodeiterator/previousnode/)() | Retourneert het vorige knooppunt in de verzameling en verplaatst de positie van de NodeIterator achterwaarts in de verzameling. |

### Zie ook

* interface [ITraversal](../itraversal/)
* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
