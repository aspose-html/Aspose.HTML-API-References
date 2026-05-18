---
title: "Resource.Save"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode Resource. Enregistre la ressource dans le flux fourni"
type: docs

url: /fr/java/com.aspose.html.saving/resource/save/
---
## Resource.Save method

Enregistre la ressource dans le flux fourni.

```java
public Resource Save(Stream stream, ResourceHandlingContext context)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| flux | Flux | Le flux dans lequel la ressource sera enregistrée. |
| contexte | ResourceHandlingContext | Contexte de gestion des ressources. |

### Valeur de retour

Cette ressource vous permet de chaîner les appels.

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Levée si [`OutputUrl`](../outputurl/) est `null`. [`OutputUrl`](../outputurl/) doit être spécifié avant d'enregistrer la ressource car sinon il est impossible de spécifier la référence correcte dans les ressources qui référencent celle-ci. |

### Voir aussi

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* package [com.aspose.html.saving](../../../com.aspose.html.saving/)
* package [Aspose.HTML](../../../)
