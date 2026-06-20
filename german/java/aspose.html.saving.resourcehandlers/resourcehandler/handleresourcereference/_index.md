---
title: "ResourceHandler.HandleResourceReference"
second_title: "Aspose.HTML für Java API-Referenz"
description: "ResourceHandler-Methode. Diese Methode ist für die Verarbeitung der Ressourcenreferenz verantwortlich. In dieser Methode können Sie festlegen, wie die Referenz auf die zu verarbeitende Ressource aussehen soll."
type: docs

url: /de/java/com.aspose.html.saving.resourcehandlers/resourcehandler/handleresourcereference/
---
## ResourceHandler.HandleResourceReference method

Diese Methode ist für die Verarbeitung der Ressourcenreferenz verantwortlich. In dieser Methode können Sie festlegen, wie die Referenz auf die zu verarbeitende Ressource aussehen soll.

```java
public String HandleResourceReference(Resource resource, ResourceHandlingContext context)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| resource | Resource | Die [`Resource`](../../../com.aspose.html.saving/resource/), die verarbeitet wird. |
| Kontext | ResourceHandlingContext | Ressourcenverarbeitungskontext. |

### Rückgabewert

Ein String, der in die übergeordnete Ressource geschrieben wird und eine Referenz auf die aktuell verarbeitete Ressource darstellt.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| InvalidOperationException | Wird ausgelöst, wenn [`OutputUrl`](../../../com.aspose.html.saving/resource/outputurl/) `null` ist und [`Status`](../../../com.aspose.html.saving/resource/status/) auf Saved gesetzt ist. [`OutputUrl`](../../../com.aspose.html.saving/resource/outputurl/) muss für die gespeicherte Ressource angegeben werden, da sonst die korrekte Referenz in den Ressourcen, die auf diese verweisen, nicht angegeben werden kann. |

### Siehe auch

* class [Resource](../../../com.aspose.html.saving/resource/)
* class [ResourceHandlingContext](../../../com.aspose.html.saving/resourcehandlingcontext/)
* class [ResourceHandler](../)
* package [com.aspose.html.saving.ResourceHandlers](../../../com.aspose.html.saving.resourcehandlers/)
* package [Aspose.HTML](../../../)
