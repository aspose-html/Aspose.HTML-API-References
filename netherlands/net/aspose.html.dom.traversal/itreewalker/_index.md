---
title: Interface ITreeWalker
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Dom.Traversal.ITreeWalker koppel. TreeWalkerobjecten worden gebruikt om door een documentstructuur of substructuur te navigeren met behulp van de weergave van het document dat is gedefinieerd door hun whatToShowvlaggen en filter indien aanwezig. Elke functie die navigatie uitvoert met behulp van een TreeWalker ondersteunt automatisch elke weergave gedefinieerd door een TreeWalker.
type: docs
weight: 2520
url: /nl/net/aspose.html.dom.traversal/itreewalker/
---
## ITreeWalker interface

TreeWalker-objecten worden gebruikt om door een documentstructuur of -substructuur te navigeren met behulp van de weergave van het document dat is gedefinieerd door hun whatToShow-vlaggen en filter (indien aanwezig). Elke functie die navigatie uitvoert met behulp van een TreeWalker, ondersteunt automatisch elke weergave gedefinieerd door een TreeWalker.

Het weglaten van knooppunten uit de logische weergave van een substructuur kan resulteren in een -structuur die substantieel verschilt van dezelfde substructuur in het complete, ongefilterde document. Knooppunten die broers en zussen zijn in de TreeWalker-weergave kunnen kinderen zijn van verschillende, ver uit elkaar knooppunten in de oorspronkelijke weergave. Neem bijvoorbeeld een NodeFilter dat alle knooppunten overslaat behalve Tekstknooppunten en het hoofdknooppunt van een document. In de logische weergave die resulteert, zullen alle tekst -knooppunten broers en zussen zijn en verschijnen als directe kinderen van het hoofdknooppunt, ongeacht hoe diep de structuur van het originele document is genest.

Zie ook de[Documentobject Model (DOM) Level 2 Traversal and Range Specification](http://www.w3.org/TR/2000/REC-DOM-Level-2-Traversal-Range-20001113). @sinds DOM-niveau 2

```csharp
public interface ITreeWalker : ITraversal
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [CurrentNode](../../aspose.html.dom.traversal/itreewalker/currentnode/) { get; set; } | Het knooppunt waarop de TreeWalker momenteel is gepositioneerd. Wijzigingen aan de DOM-structuur kunnen ertoe leiden dat het huidige knooppunt niet langer wordt geaccepteerd door het bijbehorende filter van de TreeWalker. currentNode kan ook expliciet worden ingesteld op elk knooppunt, of het nu is of niet binnen de substructuur gespecificeerd door het root-knooppunt of zou worden geaccepteerd door het filter en whatToShow-vlaggen. Verdere verplaatsing vindt plaats ten opzichte van currentNode, zelfs als het geen deel uitmaakt van de huidige weergave, door de filters toe te passen in de gevraagde richting; als geen traversal mogelijk is, wordt currentNode niet gewijzigd. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [FirstChild](../../aspose.html.dom.traversal/itreewalker/firstchild/)() | Verplaatst de TreeWalker naar het eerste zichtbare kind van het huidige knooppunt en retourneert het nieuwe knooppunt. Als het huidige knooppunt geen zichtbare kinderen heeft, retourneert null en behoudt het huidige knooppunt. |
| [LastChild](../../aspose.html.dom.traversal/itreewalker/lastchild/)() | Verplaatst de TreeWalker naar het laatst zichtbare kind van het huidige knooppunt en retourneert het nieuwe knooppunt. Als het huidige knooppunt geen zichtbare kinderen heeft, retourneert null en behoudt het huidige knooppunt. |
| [NextNode](../../aspose.html.dom.traversal/itreewalker/nextnode/)() | Verplaatst de TreeWalker naar het volgende zichtbare knooppunt in document volgorde ten opzichte van het huidige knooppunt en retourneert het nieuwe knooppunt. Als de huidige node geen volgende node heeft, of als het zoeken naar nextNode probeert omhoog te stappen vanaf de TreeWalker's root node, null retourneert en de huidige node behoudt. |
| [NextSibling](../../aspose.html.dom.traversal/itreewalker/nextsibling/)() | Verplaatst de TreeWalker naar het volgende broertje van het huidige knooppunt en retourneert het nieuwe knooppunt. Als het huidige knooppunt geen zichtbaar volgende broer of zus heeft, retourneert null en behoudt het huidige knooppunt. |
| [ParentNode](../../aspose.html.dom.traversal/itreewalker/parentnode/)() | Gaat naar en retourneert het dichtstbijzijnde zichtbare voorouderknooppunt van het huidige knooppunt. Als het zoeken naar parentNode probeert om stap omhoog te gaan vanaf het hoofdknooppunt van de TreeWalker, of als er geen zichtbaar voorouderknooppunt kan worden gevonden, behoudt deze methode de huidige positie en retourneert null. |
| [PreviousNode](../../aspose.html.dom.traversal/itreewalker/previousnode/)() | Verplaatst de TreeWalker naar het vorige zichtbare knooppunt in documentvolgorde ten opzichte van het huidige knooppunt, en retourneert het nieuwe knooppunt. Als het huidige knooppunt geen vorig knooppunt heeft, of als de zoekopdracht naar previousNode probeert omhoog te stappen vanaf het hoofdknooppunt van de TreeWalker, retourneert null en behoudt het huidige knooppunt. |
| [PreviousSibling](../../aspose.html.dom.traversal/itreewalker/previoussibling/)() | Verplaatst de TreeWalker naar het vorige broertje van het huidige knooppunt en retourneert het nieuwe knooppunt. Als het huidige knooppunt geen zichtbaar vorig broertje heeft, retourneert null en behoudt het huidige knooppunt. |

### Zie ook

* interface [ITraversal](../itraversal/)
* naamruimte [Aspose.Html.Dom.Traversal](../../aspose.html.dom.traversal/)
* montage [Aspose.HTML](../../)


