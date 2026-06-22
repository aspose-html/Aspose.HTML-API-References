---
title: "Resource.Save"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Resource-methode. Slaat de resource op in de opgegeven stream"
type: docs

url: /nl/java/com.aspose.html.saving/resource/save/
---
## Resource.Save method

Slaat de resource op in de opgegeven stream.

```java
public Resource Save(Stream stream, ResourceHandlingContext context)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stroom | Stroom | De stream waarin de resource zal worden opgeslagen. |
| context | ResourceHandlingContext | Resource-afhandelingscontext. |

### Retourwaarde

Deze resource zodat je oproepen kunt ketenen.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| InvalidOperationException | Wordt opgegooid als [`OutputUrl`](../outputurl/) `null` is. [`OutputUrl`](../outputurl/) moet worden opgegeven voordat de resource wordt opgeslagen, omdat het anders onmogelijk is de juiste referentie op te geven in de resources die naar deze verwijzen. |

### Zie ook

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* package [com.aspose.html.saving](../../../com.aspose.html.saving/)
* package [Aspose.HTML](../../../)
