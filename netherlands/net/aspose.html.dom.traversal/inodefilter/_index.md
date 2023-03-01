---
title: Interface INodeFilter
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Dom.Traversal.INodeFilter koppel. Filters zijn objecten die nodes kunnen uitfilteren. Als een NodeIterator of TreeWalker een NodeFilter krijgt wordt het filter toegepast voordat het volgende knooppunt wordt geretourneerd. Als het filter zegt om het knooppunt te accepteren retourneert de traversallogica it anders zoekt traversal naar het volgende knooppunt en doet alsof het knooppunt dat werd afgewezen er niet was.
type: docs
weight: 2490
url: /nl/net/aspose.html.dom.traversal/inodefilter/
---
## INodeFilter interface

Filters zijn objecten die nodes kunnen "uitfilteren". Als een NodeIterator of TreeWalker een NodeFilter krijgt, wordt het filter toegepast voordat het volgende knooppunt wordt geretourneerd. Als het filter zegt om het knooppunt te accepteren, retourneert de traversal-logica it; anders zoekt traversal naar het volgende knooppunt en doet alsof het -knooppunt dat werd afgewezen er niet was.

De DOM biedt geen filters. NodeFilter is slechts een -interface die gebruikers kunnen implementeren om hun eigen filters te bieden.

NodeFilters hoeven niet te weten hoe ze van knooppunt naar knooppunt moeten gaan, noch hoeven ze iets te weten over de datastructuur die wordt doorlopen. Dit maakt het heel gemakkelijk om filters te schrijven, aangezien het enige dat ze hoeven te weten, is het evalueren van een enkel knooppunt. Eén -filter kan worden gebruikt met een aantal verschillende soorten traversals, stimuleert hergebruik van code.

Zie ook de[Documentobject Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @sinds DOM-niveau 2

```csharp
public interface INodeFilter
```

## methoden

| Naam | Beschrijving |
| --- | --- |
| [AcceptNode](../../aspose.html.dom.traversal/inodefilter/acceptnode/)(Node) | Test of een gespecificeerd knooppunt zichtbaar is in de logische weergave van een TreeWalker of NodeIterator. Deze functie wordt aangeroepen door de implementatie van TreeWalker en NodeIterator; het wordt normaal gesproken niet rechtstreeks aangeroepen vanuit de gebruikerscode . (Hoewel u dit zou kunnen doen als u hetzelfde -filter wilt gebruiken om uw eigen toepassingslogica te sturen.) |

### Zie ook

* naamruimte [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* montage [Aspose.HTML](../../)


