---
title: "ResourceHandler.HandleResourceReference"
second_title: "Aspose.HTML voor Java API-referentie"
description: "ResourceHandler-methode. Deze methode is verantwoordelijk voor het verwerken van de bronreferentie. In deze methode kunt u bepalen hoe de referentie naar de verwerkte bron eruitziet."
type: docs

url: /nl/java/com.aspose.html.saving.resourcehandlers/resourcehandler/handleresourcereference/
---
## ResourceHandler.HandleResourceReference method

Deze methode is verantwoordelijk voor het verwerken van de resource-referentie. In deze methode kun je instellen hoe de referentie naar de verwerkte resource eruitziet.

```java
public String HandleResourceReference(Resource resource, ResourceHandlingContext context)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| resource | Resource | De [`Resource`](../../../com.aspose.html.saving/resource/) die zal worden verwerkt. |
| context | ResourceHandlingContext | Resource-afhandelingscontext. |

### Retourwaarde

Een String die naar de bovenliggende bron wordt geschreven en die een referentie vertegenwoordigt naar de bron die momenteel wordt verwerkt.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| InvalidOperationException | Opgetreden als [`OutputUrl`](../../../com.aspose.html.saving/resource/outputurl/) `null` is en [`Status`](../../../com.aspose.html.saving/resource/status/) Opgeslagen is. [`OutputUrl`](../../../com.aspose.html.saving/resource/outputurl/) moet worden opgegeven voor een opgeslagen bron, omdat anders het onmogelijk is de juiste referentie op te geven in de bronnen die naar deze verwijzen. |

### Zie ook

* class [Resource](../../../com.aspose.html.saving/resource/)
* class [ResourceHandlingContext](../../../com.aspose.html.saving/resourcehandlingcontext/)
* class [ResourceHandler](../)
* package [com.aspose.html.saving.ResourceHandlers](../../../com.aspose.html.saving.resourcehandlers/)
* package [Aspose.HTML](../../../)
