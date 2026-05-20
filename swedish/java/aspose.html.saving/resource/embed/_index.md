---
title: "Resource.Embed"
second_title: "Aspose.HTML för Java API-referens"
description: "Resource-metod. Bäddar in denna resurs i dess förälder genom att koda den som Base64. Kodningsresultatet kommer att skrivas till OutputUrl"
type: docs

url: /sv/java/com.aspose.html.saving/resource/embed/
---
## Resource.Embed method

Bäddar in denna resurs i dess förälder genom att koda den som Base64. Kodningsresultatet kommer att skrivas till [`OutputUrl`](../outputurl/).

```java
public Resource Embed(ResourceHandlingContext context)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| kontext | ResourceHandlingContext | Resurshanteringskontext. |

### Returvärde

Denna resurs så att du kan kedja anrop.

### Undantag

| undantag | villkor |
| --- | --- |
| InvalidOperationException | Uppstår om det inte finns någon [`ParentResource`](../../resourcehandlingcontext/parentresource/) eftersom det inte finns någon plats att bädda in resultatet. |

### Se även

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* package [com.aspose.html.saving](../../../com.aspose.html.saving/)
* package [Aspose.HTML](../../../)
