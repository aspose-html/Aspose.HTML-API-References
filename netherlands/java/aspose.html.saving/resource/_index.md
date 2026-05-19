---
title: "Resource-klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.saving.Resource-klasse. Deze klasse beschrijft een resource en biedt methoden voor de verwerking ervan"
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
| [getMimeType](../../com.aspose.html.saving/resource/mimetype/) Retourneert de [`MimeType`](../../com.aspose.html/mimetype/) van deze resource. Kan `null` zijn als de resource niet is gevonden. |
| [getOriginalReference](../../com.aspose.html.saving/resource/originalreference/) Retourneert een String die de oorspronkelijke referentie naar deze resource bevat. |
| [getOriginalUrl](../../com.aspose.html.saving/resource/originalurl/) Retourneert een URL die aangeeft waar deze resource zich bevond. |
[getOutputUrl]
[setOutputUrl] Gets or sets the URL indicating where the resource will be located after processing. |
| [getStatus](../../com.aspose.html.saving/resource/status/) Retourneert de huidige status van de bron. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [embed](../../com.aspose.html.saving/resource/embed/)(ResourceHandlingContext) | Integreert deze bron in de bovenliggende door deze als Base64 te coderen. Het coderingsresultaat wordt weggeschreven naar [`OutputUrl`](./outputurl/). |
| [save](../../com.aspose.html.saving/resource/save/)(Stream, ResourceHandlingContext) | Slaat de bron op in de opgegeven stream. |
| [withOutputUrl](../../com.aspose.html.saving/resource/withoutputurl/)(Url) | Specificeert de nieuwe URL die aangeeft waar de bron zich zal bevinden na verwerking. |

### Zie ook

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
