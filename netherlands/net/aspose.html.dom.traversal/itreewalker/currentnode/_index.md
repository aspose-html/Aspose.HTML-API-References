---
title: ITreeWalker.CurrentNode
second_title: Aspose.HTML voor .NET API-referentie
description: ITreeWalker eigendom. Het knooppunt waarop de TreeWalker momenteel is gepositioneerd. Wijzigingen aan de DOMstructuur kunnen ertoe leiden dat het huidige knooppunt niet langer wordt geaccepteerd door het bijbehorende filter van de TreeWalker. currentNode kan ook expliciet worden ingesteld op elk knooppunt of het nu is of niet binnen de substructuur gespecificeerd door het rootknooppunt of zou worden geaccepteerd door het filter en whatToShowvlaggen. Verdere verplaatsing vindt plaats ten opzichte van currentNode zelfs als het geen deel uitmaakt van de huidige weergave door de filters toe te passen in de gevraagde richting als geen traversal mogelijk is wordt currentNode niet gewijzigd.
type: docs
weight: 10
url: /nl/net/aspose.html.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

Het knooppunt waarop de TreeWalker momenteel is gepositioneerd. Wijzigingen aan de DOM-structuur kunnen ertoe leiden dat het huidige knooppunt niet langer wordt geaccepteerd door het bijbehorende filter van de TreeWalker. currentNode kan ook expliciet worden ingesteld op elk knooppunt, of het nu is of niet binnen de substructuur gespecificeerd door het root-knooppunt of zou worden geaccepteerd door het filter en whatToShow-vlaggen. Verdere verplaatsing vindt plaats ten opzichte van currentNode, zelfs als het geen deel uitmaakt van de huidige weergave, door de filters toe te passen in de gevraagde richting; als geen traversal mogelijk is, wordt currentNode niet gewijzigd.

```csharp
public Node CurrentNode { get; set; }
```

### Eigendoms-waarde

Het huidige knooppunt.

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Verhoogd als er een poging wordt gedaan om currentNode in te stellen op null. |

### Zie ook

* class [Node](../../../aspose.html.dom/node/)
* interface [ITreeWalker](../)
* naamruimte [Aspose.Html.Dom.Traversal](../../itreewalker/)
* montage [Aspose.HTML](../../../)


