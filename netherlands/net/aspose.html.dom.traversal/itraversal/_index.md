---
title: Interface ITraversal
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Dom.Traversal.ITraversal koppel. Iterators worden gebruikt om door een set knooppunten te stappen bijv. de set knooppunten in een NodeList de substructuur van het document die wordt beheerd door een bepaald knooppunt de resultaten van een query of een andere set knooppunten. De set te herhalen knooppunten wordt bepaald door de implementatie van de NodeIterator. DOM Level 2 specificeert een enkele NodeIteratorimplementatie voor documentvolgorde traversal van een documentsubstructuur. Instanties van deze iterators worden gemaakt door DocumentTraversal .createNodeIterator. aan te roepen
type: docs
weight: 2510
url: /nl/net/aspose.html.dom.traversal/itraversal/
---
## ITraversal interface

Iterators worden gebruikt om door een set knooppunten te stappen, bijv. de set knooppunten in een NodeList, de substructuur van het document die wordt beheerd door een bepaald knooppunt, de resultaten van een query of een andere set knooppunten. De set te herhalen knooppunten wordt bepaald door de -implementatie van de NodeIterator. DOM Level 2 specificeert een enkele NodeIterator-implementatie voor documentvolgorde traversal van een documentsubstructuur. Instanties van deze iterators worden gemaakt door DocumentTraversal .createNodeIterator(). aan te roepen

Zie ook de[Documentobject Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @sinds DOM-niveau 2

```csharp
public interface ITraversal : IDisposable
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Filter](../../aspose.html.dom.traversal/itraversal/filter/) { get; } | Het NodeFilter dat wordt gebruikt om knooppunten te screenen. |
| [Root](../../aspose.html.dom.traversal/itraversal/root/) { get; } | Het hoofdknooppunt van de NodeIterator, zoals opgegeven toen it werd gemaakt. |
| [WhatToShow](../../aspose.html.dom.traversal/itraversal/whattoshow/) { get; } | Dit attribuut bepaalt welke nodetypes gepresenteerd worden via de iterator. De beschikbare set constanten wordt gedefinieerd in de NodeFilter-interface. Knooppunten die niet zijn geaccepteerd door whatToShow, worden overgeslagen, maar hun kinderen kunnen nog steeds worden overwogen. Merk op dat dit overslaan voorrang heeft op het filter, indien aanwezig. |

### Zie ook

* naamruimte [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* montage [Aspose.HTML](../../)


