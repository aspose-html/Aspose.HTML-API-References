---
title: "INodeIterator Interface"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.traversal.INodeIterator interface. Iteratoren worden gebruikt om door een set knooppunten te stappen, bv. de set knooppunten in een NodeList, de document‑subboom beheerd door een bepaald Node, de resultaten van een query of een andere set knooppunten. De set knooppunten die moet worden geïtereerd, wordt bepaald door de implementatie van de NodeIterator. DOM Level 2 specificeert een enkele NodeIterator‑implementatie voor document‑order traversie van een document‑subboom. Instanties van deze iteratoren worden gecreëerd door het aanroepen van DocumentTraversal.createNodeIterator."
type: docs

url: /nl/java/com.aspose.html.dom.traversal/inodeiterator/
---
## INodeIterator interface

Iterators worden gebruikt om door een verzameling knooppunten te stappen, bijv. de verzameling knooppunten in een NodeList, de document‑subboom die wordt beheerd door een specifieke Node, de resultaten van een query, of elke andere verzameling knooppunten. De te itereren verzameling wordt bepaald door de implementatie van de NodeIterator. DOM Level 2 specificeert een enkele NodeIterator‑implementatie voor document‑volgorde doorloop van een document‑subboom. Instanties van deze iterators worden gecreëerd door DocumentTraversal.createNodeIterator() aan te roepen.

Zie ook de [Document Object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface INodeIterator : ITraversal
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getPointerBeforeReferenceNode](../../com.aspose.html.dom.traversal/inodeiterator/pointerbeforereferencenode/) De waarde van deze vlag bepaalt of de kinderen van entiteitsreferatieknooppunten zichtbaar zijn voor de iterator. Als false, worden zij en hun afstammelingen afgewezen. Merk op dat deze afwijzing voorrang heeft boven whatToShow en de filter. Ook merk op dat dit momenteel de enige situatie is waarin NodeIterators een volledige subboom kunnen afwijzen in plaats van individuele knooppunten over te slaan. Om een weergave van het document te produceren waarbij entiteitsreferenties zijn uitgeklapt en de entiteitsreferatieknoop zelf niet wordt getoond, gebruik de whatToShow‑vlaggen om de entiteitsreferatieknoop te verbergen en stel expandEntityReferences in op true bij het maken van de iterator. Om een weergave te produceren waarbij entiteitsreferatieknooppunten aanwezig zijn maar zonder entiteitsexpansie, gebruik de whatToShow‑vlaggen om de entiteitsreferatieknoop te tonen en stel expandEntityReferences in op false. |
| [getReferenceNode](../../com.aspose.html.dom.traversal/inodeiterator/referencenode/) De huidige referentieknoop. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [detach](../../com.aspose.html.dom.traversal/inodeiterator/detach/)() | Ontkoppelt de NodeIterator van de set waarover deze itereerde, maakt eventuele computationele bronnen vrij en plaatst de iterator in de STATUS INVALID. Nadat detach is aangeroepen, zullen oproepen naar nextNode of previousNode de uitzondering INVALID_STATE_ERR veroorzaken. |
| [nextNode](../../com.aspose.html.dom.traversal/inodeiterator/nextnode/)() | Retourneert het volgende knooppunt in de set en verschuift de positie van de iterator in de set. Na het aanmaken van een NodeIterator, retourneert de eerste aanroep van nextNode() het eerste knooppunt in de set. |
| [previousNode](../../com.aspose.html.dom.traversal/inodeiterator/previousnode/)() | Retourneert het vorige knooppunt in de set en verplaatst de positie van de NodeIterator terug in de set. |

### Zie ook

* interface [ITraversal](../itraversal/)
* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
