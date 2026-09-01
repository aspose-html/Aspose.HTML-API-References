---
title: "Resource.Embed"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Resource methode. Integreert deze resource in zijn ouder door deze te coderen als Base64. Het coderingsresultaat wordt geschreven naar OutputUrl"
type: docs

url: /nl/java/com.aspose.html.saving/resource/embed/
---
## Resource.Embed method

Integreert deze resource in zijn ouder door deze te coderen als Base64. Het coderingsresultaat wordt geschreven naar [`OutputUrl`](../outputurl/).

```java
public Resource Embed(ResourceHandlingContext context)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| context | ResourceHandlingContext | Resource-afhandelingscontext. |

### Retourwaarde

Deze resource zodat je oproepen kunt ketenen.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| InvalidOperationException | Wordt opgegooid als er geen [`ParentResource`](../../resourcehandlingcontext/parentresource/) is omdat er geen plaats is om het resultaat in te sluiten. |

### Zie ook

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* package [com.aspose.html.saving](../../../com.aspose.html.saving/)
* package [Aspose.HTML](../../../)
