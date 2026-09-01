---
title: "Resource‑klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.saving.Resource class. Deze klasse beschrijft een resource en biedt methoden voor de verwerking ervan"
type: docs

url: /nl/java/com.aspose.html.saving/resource/
---
## Resource class

Deze klasse beschrijft een bron en biedt methoden voor de verwerking ervan.

```java
public class Resource
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getMimeType](../../com.aspose.html.saving/resource/mimetype/) Retourneert de [`MimeType`](../../com.aspose.html/mimetype/) van deze resource. Kan `null` zijn als de resource niet gevonden is. |
| [getOriginalReference](../../com.aspose.html.saving/resource/originalreference/) Retourneert een String die de oorspronkelijke referentie naar deze resource bevat. |
| [getOriginalUrl](../../com.aspose.html.saving/resource/originalurl/) Retourneert een URL die aangeeft waar deze resource zich bevond. |
[getOutputUrl]
[setOutputUrl] Gets or sets the URL indicating where the resource will be located after processing. |
| [getStatus](../../com.aspose.html.saving/resource/status/) Retourneert de huidige status van de resource. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [embed](../../com.aspose.html.saving/resource/embed/)(ResourceHandlingContext) | Voegt deze resource in zijn bovenliggende element in door deze te coderen als Base64. Het coderingsresultaat wordt geschreven naar [`OutputUrl`](./outputurl/). |
| [save](../../com.aspose.html.saving/resource/save/)(Stream, ResourceHandlingContext) | Slaat de resource op in de opgegeven stream. |
| [withOutputUrl](../../com.aspose.html.saving/resource/withoutputurl/)(Url) | Specificeert de nieuwe URL die aangeeft waar de resource zich zal bevinden na verwerking. |

### Zie ook

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
