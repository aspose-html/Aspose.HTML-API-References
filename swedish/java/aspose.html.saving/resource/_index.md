---
title: "Resource‑klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.saving.Resource‑klass. Denna klass beskriver en resurs och tillhandahåller metoder för att bearbeta den"
type: docs

url: /sv/java/com.aspose.html.saving/resource/
---
## Resource class

Denna klass beskriver en resurs och tillhandahåller metoder för att bearbeta den.

```java
public class Resource
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getMimeType](../../com.aspose.html.saving/resource/mimetype/) Returnerar [`MimeType`](../../com.aspose.html/mimetype/) för denna resurs. Kan vara `null` om resursen inte hittades. |
| [getOriginalReference](../../com.aspose.html.saving/resource/originalreference/) Returnerar en sträng som innehåller den ursprungliga referensen till denna resurs. |
| [getOriginalUrl](../../com.aspose.html.saving/resource/originalurl/) Returnerar en URL som visar var denna resurs var placerad. |
[getOutputUrl]
[setOutputUrl] Gets or sets the URL indicating where the resource will be located after processing. |
| [getStatus](../../com.aspose.html.saving/resource/status/) Returnerar den aktuella statusen för resursen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [embed](../../com.aspose.html.saving/resource/embed/)(ResourceHandlingContext) | Bäddar in denna resurs i dess förälder genom att koda den som Base64. Kodningsresultatet kommer att skrivas till [`OutputUrl`](./outputurl/). |
| [save](../../com.aspose.html.saving/resource/save/)(Stream, ResourceHandlingContext) | Sparar resursen till den angivna strömmen. |
| [withOutputUrl](../../com.aspose.html.saving/resource/withoutputurl/)(Url) | Anger den nya URL:en som visar var resursen kommer att finnas efter bearbetning. |

### Se även

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
