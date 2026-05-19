---
title: "Classe Resource"
second_title: "Riferimento API Aspose.HTML per Java"
description: "classe com.aspose.html.saving.Resource. Questa classe descrive una risorsa e fornisce metodi per elaborarla"
type: docs

url: /it/java/com.aspose.html.saving/resource/
---
## Resource class

Questa classe descrive una risorsa e fornisce metodi per elaborarla.

```java
public class Resource
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [getMimeType](../../com.aspose.html.saving/resource/mimetype/) Restituisce il [`MimeType`](../../com.aspose.html/mimetype/) di questa risorsa. Può essere `null` se la risorsa non è stata trovata. |
| [getOriginalReference](../../com.aspose.html.saving/resource/originalreference/) Restituisce una stringa contenente il riferimento originale a questa risorsa. |
| [getOriginalUrl](../../com.aspose.html.saving/resource/originalurl/) Restituisce un URL che indica dove si trovava questa risorsa. |
[getOutputUrl]
[setOutputUrl] Gets or sets the URL indicating where the resource will be located after processing. |
| [getStatus](../../com.aspose.html.saving/resource/status/) Restituisce lo stato corrente della risorsa. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [embed](../../com.aspose.html.saving/resource/embed/)(ResourceHandlingContext) | Incorpora questa risorsa all'interno del suo genitore codificandola come Base64. Il risultato della codifica verrà scritto in [`OutputUrl`](./outputurl/). |
| [save](../../com.aspose.html.saving/resource/save/)(Stream, ResourceHandlingContext) | Salva la risorsa nello stream fornito. |
| [withOutputUrl](../../com.aspose.html.saving/resource/withoutputurl/)(Url) | Specifica il nuovo URL che indica dove la risorsa sarà posizionata dopo l'elaborazione. |

### Vedi anche

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
