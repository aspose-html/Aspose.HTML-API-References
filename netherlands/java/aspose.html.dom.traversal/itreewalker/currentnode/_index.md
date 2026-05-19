---
title: "ITreeWalker.CurrentNode"
second_title: "Aspose.HTML voor Java API-referentie"
description: "ITreeWalker property. Het knooppunt waarop de TreeWalker momenteel is gepositioneerd. Wijzigingen in de DOM-boom kunnen ertoe leiden dat het huidige knooppunt niet langer wordt geaccepteerd door het bijbehorende filter van de TreeWalker. currentNode kan ook expliciet worden ingesteld op elk knooppunt, ongeacht of het zich binnen de subboom bevindt die is gespecificeerd door het rootknooppunt of al dan niet wordt geaccepteerd door het filter en de whatToShow‑vlaggen. Verdere traversals vinden plaats relatief aan currentNode, zelfs als het niet deel uitmaakt van de huidige weergave, door de filters toe te passen in de gevraagde richting; als er geen traversals mogelijk zijn, wordt currentNode niet gewijzigd."
type: docs

url: /nl/java/com.aspose.html.dom.traversal/itreewalker/currentnode/
---
## ITreeWalker.CurrentNode property

Het knooppunt waarop de TreeWalker momenteel is gepositioneerd. Wijzigingen in de DOM-boom kunnen ertoe leiden dat het huidige knooppunt niet langer wordt geaccepteerd door het bijbehorende filter van de TreeWalker. currentNode kan ook expliciet worden ingesteld op elk knooppunt, ongeacht of het zich binnen de subboom bevindt die is gespecificeerd door het rootknooppunt of al dan niet wordt geaccepteerd door het filter en de whatToShow‑vlaggen. Verdere traversals vinden plaats relatief aan currentNode, zelfs als het niet deel uitmaakt van de huidige weergave, door de filters toe te passen in de gevraagde richting; als er geen traversals mogelijk zijn, wordt currentNode niet gewijzigd.

```java
public Node CurrentNode { get; set; }
```

### Property Value

Het huidige knooppunt.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Opgetreden als een poging wordt gedaan om currentNode op null in te stellen. |

### Zie ook

* class [Node](../../../com.aspose.html.dom/node/)
* interface [ITreeWalker](../)
* package [com.aspose.html.dom.traversal](../../../com.aspose.html.dom.traversal/)
* package [Aspose.HTML](../../../)
