---
title: "ResourceHandler.HandleResourceReference"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode ResourceHandler. Cette méthode est responsable de la gestion de la référence de la ressource. Dans cette méthode, vous pouvez définir à quoi ressemblera la référence à la ressource en cours de traitement."
type: docs

url: /fr/java/com.aspose.html.saving.resourcehandlers/resourcehandler/handleresourcereference/
---
## ResourceHandler.HandleResourceReference method

Cette méthode est responsable du traitement de la référence de la ressource. Dans cette méthode, vous pouvez définir à quoi ressemblera la référence à la ressource traitée.

```java
public String HandleResourceReference(Resource resource, ResourceHandlingContext context)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| resource | Resource | Le [`Resource`](../../../com.aspose.html.saving/resource/) qui sera géré. |
| contexte | ResourceHandlingContext | Contexte de gestion des ressources. |

### Valeur de retour

Une chaîne qui sera écrite dans la ressource parent et qui représente une référence à la ressource actuellement traitée.

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Levée si [`OutputUrl`](../../../com.aspose.html.saving/resource/outputurl/) est `null` et que [`Status`](../../../com.aspose.html.saving/resource/status/) est Saved. [`OutputUrl`](../../../com.aspose.html.saving/resource/outputurl/) doit être spécifié pour la ressource enregistrée car sinon il est impossible de spécifier la référence correcte dans les ressources qui référencent celle-ci. |

### Voir aussi

* class [Resource](../../../com.aspose.html.saving/resource/)
* class [ResourceHandlingContext](../../../com.aspose.html.saving/resourcehandlingcontext/)
* class [ResourceHandler](../)
* package [com.aspose.html.saving.ResourceHandlers](../../../com.aspose.html.saving.resourcehandlers/)
* package [Aspose.HTML](../../../)
