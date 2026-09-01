---
title: "Resource.Save"
second_title: "Aspose.HTML för Java API-referens"
description: "Resursmetod. Sparar resursen till den angivna strömmen."
type: docs

url: /sv/java/com.aspose.html.saving/resource/save/
---
## Resource.Save method

Sparar resursen till den angivna strömmen.

```java
public Resource Save(Stream stream, ResourceHandlingContext context)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | Strömmen där resursen kommer att sparas. |
| kontext | ResourceHandlingContext | Resurshanteringskontext. |

### Returvärde

Denna resurs så att du kan kedja anrop.

### Undantag

| undantag | villkor |
| --- | --- |
| InvalidOperationException | Uppstår om [`OutputUrl`](../outputurl/) är `null`. [`OutputUrl`](../outputurl/) bör specificeras innan resursen sparas eftersom det annars är omöjligt att ange den korrekta referensen i de resurser som refererar till denna. |

### Se även

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* package [com.aspose.html.saving](../../../com.aspose.html.saving/)
* package [Aspose.HTML](../../../)
