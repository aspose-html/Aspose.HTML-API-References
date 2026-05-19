---
title: "INodeFilter-interface"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.traversal.INodeFilter-interface. Filters zijn objecten die weten hoe knooppunten gefilterd moeten worden. Als een NodeIterator of TreeWalker een NodeFilter krijgt, past hij het filter toe voordat hij het volgende knooppunt retourneert. Als het filter aangeeft het knooppunt te accepteren, retourneert de traversallogica het; anders zoekt de traversie naar het volgende knooppunt en doet alsof het afgewezen knooppunt niet bestaat."
type: docs

url: /nl/java/com.aspose.html.dom.traversal/inodefilter/
---
## INodeFilter interface

Filters zijn objecten die weten hoe ze knooppunten moeten \"filteren\". Als een NodeIterator of TreeWalker een NodeFilter krijgt, past hij het filter toe voordat hij het volgende knooppunt retourneert. Als het filter aangeeft het knooppunt te accepteren, retourneert de doorlooplogica het; anders zoekt de doorloop naar het volgende knooppunt en doet alsof het afgewezen knooppunt niet bestond.

De DOM biedt geen filters. NodeFilter is slechts een interface die gebruikers kunnen implementeren om hun eigen filters te leveren.

NodeFilters hoeven niet te weten hoe ze van knooppunt naar knooppunt moeten traverseren, noch hoeven ze iets te weten over de datastructuur die wordt doorlopen. Dit maakt het zeer eenvoudig om filters te schrijven, aangezien het enige wat ze moeten kunnen, is een enkel knooppunt evalueren. Eén filter kan worden gebruikt met een aantal verschillende soorten traversals, wat codehergebruik stimuleert.

Zie ook de [Document Object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface INodeFilter
```

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [acceptNode](../../com.aspose.html.dom.traversal/inodefilter/acceptnode/)(Node) | Test of een opgegeven knooppunt zichtbaar is in de logische weergave van een TreeWalker of NodeIterator. Deze functie wordt aangeroepen door de implementatie van TreeWalker en NodeIterator; hij wordt normaal niet direct vanuit gebruikerscode aangeroepen. (Hoewel je dit wel kunt doen als je hetzelfde filter wilt gebruiken om je eigen toepassingslogica te sturen.) |

### Zie ook

* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
