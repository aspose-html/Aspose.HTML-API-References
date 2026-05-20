---
title: "ResourceHandler.HandleResourceReference"
second_title: "Aspose.HTML för Java API-referens"
description: "ResourceHandler‑metod. Denna metod ansvarar för att hantera resursreferensen. I den här metoden kan du ange hur referensen till den hanterade resursen ska se ut."
type: docs

url: /sv/java/com.aspose.html.saving.resourcehandlers/resourcehandler/handleresourcereference/
---
## ResourceHandler.HandleResourceReference method

Denna metod ansvarar för att hantera resursreferensen. I denna metod kan du ange hur referensen till den hanterade resursen ska se ut.

```java
public String HandleResourceReference(Resource resource, ResourceHandlingContext context)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| resource | Resource | Den [`Resource`](../../../com.aspose.html.saving/resource/) som kommer att hanteras. |
| kontext | ResourceHandlingContext | Resurshanteringskontext. |

### Returvärde

En sträng som kommer att skrivas till den överordnade resursen och som representerar en referens till den resurs som för närvarande hanteras.

### Undantag

| undantag | villkor |
| --- | --- |
| InvalidOperationException | Utlöst om [`OutputUrl`](../../../com.aspose.html.saving/resource/outputurl/) är `null` och [`Status`](../../../com.aspose.html.saving/resource/status/) är Saved. [`OutputUrl`](../../../com.aspose.html.saving/resource/outputurl/) bör specificeras för sparad resurs eftersom det annars är omöjligt att ange korrekt referens i de resurser som refererar till denna. |

### Se även

* class [Resource](../../../com.aspose.html.saving/resource/)
* class [ResourceHandlingContext](../../../com.aspose.html.saving/resourcehandlingcontext/)
* class [ResourceHandler](../)
* package [com.aspose.html.saving.ResourceHandlers](../../../com.aspose.html.saving.resourcehandlers/)
* package [Aspose.HTML](../../../)
