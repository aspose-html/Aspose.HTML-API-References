---
title: "Resource‑Klasse"
second_title: "Aspose.HTML für Java API-Referenz"
description: "com.aspose.html.saving.Resource‑Klasse. Diese Klasse beschreibt eine Ressource und stellt Methoden zur Verarbeitung bereit."
type: docs

url: /de/java/com.aspose.html.saving/resource/
---
## Resource class

Diese Klasse beschreibt eine Ressource und stellt Methoden zur Verarbeitung bereit.

```java
public class Resource
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [getMimeType](../../com.aspose.html.saving/resource/mimetype/) Gibt den [`MimeType`](../../com.aspose.html/mimetype/) dieser Ressource zurück. Kann `null` sein, wenn die Ressource nicht gefunden wurde. |
| [getOriginalReference](../../com.aspose.html.saving/resource/originalreference/) Gibt einen String zurück, der die ursprüngliche Referenz zu dieser Ressource enthält. |
| [getOriginalUrl](../../com.aspose.html.saving/resource/originalurl/) Gibt eine URL zurück, die angibt, wo sich diese Ressource befand. |
[getOutputUrl]
[setOutputUrl] Gets or sets the URL indicating where the resource will be located after processing. |
| [getStatus](../../com.aspose.html.saving/resource/status/) Gibt den aktuellen Status der Ressource zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [embed](../../com.aspose.html.saving/resource/embed/)(ResourceHandlingContext) | Betettet diese Ressource in ihr übergeordnetes Element ein, indem sie als Base64 kodiert wird. Das Kodierungsergebnis wird in [`OutputUrl`](./outputurl/) geschrieben. |
| [save](../../com.aspose.html.saving/resource/save/)(Stream, ResourceHandlingContext) | Speichert die Ressource in den bereitgestellten Stream. |
| [withOutputUrl](../../com.aspose.html.saving/resource/withoutputurl/)(Url) | Gibt die neue URL an, die angibt, wo die Ressource nach der Verarbeitung zu finden sein wird. |

### Siehe auch

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
