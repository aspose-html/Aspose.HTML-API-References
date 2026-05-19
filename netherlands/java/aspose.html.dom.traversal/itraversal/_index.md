---
title: "ITraversal-interface"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.traversal.ITraversal-interface. Iterators worden gebruikt om door een set knooppunten te stappen, bijvoorbeeld de set knooppunten in een NodeList, de document-subboom beheerd door een bepaald knooppunt, de resultaten van een query of elke andere set knooppunten. De set knooppunten die moet worden geïtereerd, wordt bepaald door de implementatie van de NodeIterator. DOM Level 2 specificeert een enkele NodeIterator-implementatie voor documentvolgorde-traversie van een document-subboom. Instanties van deze iterators worden gecreëerd door DocumentTraversal.createNodeIterator aan te roepen."
type: docs

url: /nl/java/com.aspose.html.dom.traversal/itraversal/
---
## ITraversal interface

Iterators worden gebruikt om door een verzameling knooppunten te stappen, bijv. de verzameling knooppunten in een NodeList, de document‑subboom die wordt beheerd door een specifieke Node, de resultaten van een query, of elke andere verzameling knooppunten. De te itereren verzameling wordt bepaald door de implementatie van de NodeIterator. DOM Level 2 specificeert een enkele NodeIterator‑implementatie voor document‑volgorde doorloop van een document‑subboom. Instanties van deze iterators worden gecreëerd door DocumentTraversal.createNodeIterator() aan te roepen.

Zie ook de [Document Object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface ITraversal : IDisposable
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getFilter](../../com.aspose.html.dom.traversal/itraversal/filter/) De NodeFilter die wordt gebruikt om knooppunten te filteren. |
| [getRoot](../../com.aspose.html.dom.traversal/itraversal/root/) Het rootknooppunt van de NodeIterator, zoals gespecificeerd bij het aanmaken. |
| [getWhatToShow](../../com.aspose.html.dom.traversal/itraversal/whattoshow/) Dit attribuut bepaalt welke knooppunttypes via de iterator worden gepresenteerd. De beschikbare set constanten is gedefinieerd in de NodeFilter-interface. Knooppunten die niet door whatToShow worden geaccepteerd, worden overgeslagen, maar hun kinderen kunnen nog steeds worden beschouwd. Merk op dat deze overslaan voorrang heeft op het filter, indien aanwezig. |

### Zie ook

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
