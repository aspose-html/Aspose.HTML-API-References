---
title: "Classe Resource"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Classe com.aspose.html.saving.Resource. Cette classe décrit une ressource et fournit des méthodes pour la traiter"
type: docs

url: /fr/java/com.aspose.html.saving/resource/
---
## Resource class

Cette classe décrit une ressource et fournit des méthodes pour la traiter.

```java
public class Resource
```

## Propriétés

| Nom | Description |
| --- | --- |
| [getMimeType](../../com.aspose.html.saving/resource/mimetype/) Retourne le [`MimeType`](../../com.aspose.html/mimetype/) de cette ressource. Peut être `null` si la ressource n'a pas été trouvée. |
| [getOriginalReference](../../com.aspose.html.saving/resource/originalreference/) Retourne une chaîne contenant la référence originale à cette ressource. |
| [getOriginalUrl](../../com.aspose.html.saving/resource/originalurl/) Retourne une URL indiquant où cette ressource était située. |
[getOutputUrl]
[setOutputUrl] Gets or sets the URL indicating where the resource will be located after processing. |
| [getStatus](../../com.aspose.html.saving/resource/status/) Retourne l'état actuel de la ressource. |

## Méthodes

| Nom | Description |
| --- | --- |
| [embed](../../com.aspose.html.saving/resource/embed/)(ResourceHandlingContext) | Intègre cette ressource dans son parent en l'encodant en Base64. Le résultat de l'encodage sera écrit dans [`OutputUrl`](./outputurl/). |
| [save](../../com.aspose.html.saving/resource/save/)(Stream, ResourceHandlingContext) | Enregistre la ressource dans le flux fourni. |
| [withOutputUrl](../../com.aspose.html.saving/resource/withoutputurl/)(Url) | Spécifie la nouvelle URL indiquant où la ressource sera située après le traitement. |

### Voir aussi

* package [com.aspose.html.saving](../../com.aspose.html.saving/)
* package [Aspose.HTML](../../)
