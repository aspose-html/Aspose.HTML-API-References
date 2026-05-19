---
title: "ITreeWalker-interface"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.traversal.ITreeWalker-interface. TreeWalker-objecten worden gebruikt om door een documentboom of subboom te navigeren met behulp van de weergave van het document gedefinieerd door hun whatToShow‑vlaggen en eventueel filter. Elke functie die navigatie uitvoert met een TreeWalker ondersteunt automatisch elke weergave die door een TreeWalker is gedefinieerd."
type: docs

url: /nl/java/com.aspose.html.dom.traversal/itreewalker/
---
## ITreeWalker interface

TreeWalker‑objecten worden gebruikt om door een documentboom of subboom te navigeren met behulp van de weergave van het document die wordt gedefinieerd door hun whatToShow‑vlaggen en filter (indien aanwezig). Elke functie die navigatie uitvoert met een TreeWalker ondersteunt automatisch elke weergave die door een TreeWalker wordt gedefinieerd.

Het weglaten van knooppunten uit de logische weergave van een subboom kan resulteren in een structuur die aanzienlijk verschilt van dezelfde subboom in het volledige, ongefilterde document. Knooppunten die broers en zussen zijn in de TreeWalker-weergave kunnen kinderen zijn van verschillende, ver uit elkaar liggende knooppunten in de oorspronkelijke weergave. Bijvoorbeeld, overweeg een NodeFilter die alle knooppunten behalve Tekstknooppunten en het rootknooppunt van een document overslaat. In de logische weergave die hieruit voortvloeit, zullen alle tekstknooppunten broers en zussen zijn en verschijnen als directe kinderen van het rootknooppunt, ongeacht hoe diep genest de structuur van het oorspronkelijke document is.

Zie ook de [Document Object Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @since DOM Level 2

```java
public interface ITreeWalker : ITraversal
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
[getCurrentNode]
[setCurrentNode] The node at which the TreeWalker is currently positioned. Alterations to the DOM tree may cause the current node to no longer be accepted by the TreeWalker's associated filter. currentNode may also be explicitly set to any node, whether or not it is within the subtree specified by the root node or would be accepted by the filter and whatToShow flags. Further traversal occurs relative to currentNode even if it is not part of the current view, by applying the filters in the requested direction; if no traversal is possible, currentNode is not changed. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [firstChild](../../com.aspose.html.dom.traversal/itreewalker/firstchild/)() | Verplaatst de TreeWalker naar het eerste zichtbare kind van het huidige knooppunt en retourneert het nieuwe knooppunt. Als het huidige knooppunt geen zichtbare kinderen heeft, wordt null geretourneerd en blijft het huidige knooppunt behouden. |
| [lastChild](../../com.aspose.html.dom.traversal/itreewalker/lastchild/)() | Verplaatst de TreeWalker naar het laatste zichtbare kind van het huidige knooppunt en retourneert het nieuwe knooppunt. Als het huidige knooppunt geen zichtbare kinderen heeft, wordt null geretourneerd en blijft het huidige knooppunt behouden. |
| [nextNode](../../com.aspose.html.dom.traversal/itreewalker/nextnode/)() | Verplaatst de TreeWalker naar het volgende zichtbare knooppunt in documentvolgorde ten opzichte van het huidige knooppunt en retourneert het nieuwe knooppunt. Als het huidige knooppunt geen volgend knooppunt heeft, of als de zoektocht naar nextNode omhoog probeert te gaan vanaf de root van de TreeWalker, wordt null geretourneerd en blijft het huidige knooppunt behouden. |
| [nextSibling](../../com.aspose.html.dom.traversal/itreewalker/nextsibling/)() | Verplaatst de TreeWalker naar de volgende zichtbare broer/zus van het huidige knooppunt en retourneert het nieuwe knooppunt. Als het huidige knooppunt geen zichtbaar volgend broertje/zusje heeft, wordt null geretourneerd en blijft het huidige knooppunt behouden. |
| [parentNode](../../com.aspose.html.dom.traversal/itreewalker/parentnode/)() | Verplaatst naar en retourneert het dichtstbijzijnde zichtbare bovenliggende knooppunt van het huidige knooppunt. Als de zoektocht naar parentNode omhoog probeert te gaan vanaf de root van de TreeWalker, of als er geen zichtbaar bovenliggend knooppunt wordt gevonden, behoudt deze methode de huidige positie en retourneert null. |
| [previousNode](../../com.aspose.html.dom.traversal/itreewalker/previousnode/)() | Verplaatst de TreeWalker naar het vorige zichtbare knooppunt in documentvolgorde ten opzichte van het huidige knooppunt, en retourneert het nieuwe knooppunt. Als het huidige knooppunt geen vorig knooppunt heeft, of als de zoekopdracht voor previousNode probeert omhoog te gaan vanaf de root‑knoop van de TreeWalker, wordt null geretourneerd en blijft het huidige knooppunt behouden. |
| [previousSibling](../../com.aspose.html.dom.traversal/itreewalker/previoussibling/)() | Verplaatst de TreeWalker naar de vorige sibling van het huidige knooppunt, en retourneert het nieuwe knooppunt. Als het huidige knooppunt geen zichtbaar vorige sibling heeft, wordt null geretourneerd en blijft het huidige knooppunt behouden. |

### Zie ook

* interface [ITraversal](../itraversal/)
* package [com.aspose.html.dom.traversal](../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../)
