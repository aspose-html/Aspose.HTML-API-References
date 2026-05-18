---
title: "Resource.Embed"
second_title: "Aspose.HTML für Java API-Referenz"
description: "Resource-Methode. Bettet diese Ressource in ihr übergeordnetes Element ein, indem sie als Base64 kodiert wird. Das Kodierungsergebnis wird in OutputUrl geschrieben."
type: docs

url: /de/java/com.aspose.html.saving/resource/embed/
---
## Resource.Embed method

Bettet diese Ressource in ihr übergeordnetes Element ein, indem sie als Base64 kodiert wird. Das Kodierungsergebnis wird in [`OutputUrl`](../outputurl/) geschrieben.

```java
public Resource Embed(ResourceHandlingContext context)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Kontext | ResourceHandlingContext | Ressourcenverarbeitungskontext. |

### Rückgabewert

Diese Ressource, damit Sie Aufrufe verketten können.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| InvalidOperationException | Ausgelöst, wenn es kein [`ParentResource`](../../resourcehandlingcontext/parentresource/) gibt, weil es keinen Ort gibt, um das Ergebnis einzubetten. |

### Siehe auch

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* package [com.aspose.html.saving](../../../com.aspose.html.saving/)
* package [Aspose.HTML](../../../)
