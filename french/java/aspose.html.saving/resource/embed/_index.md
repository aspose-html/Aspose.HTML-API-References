---
title: "Resource.Embed"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode Resource. Intègre cette ressource dans son parent en l'encodant en Base64. Le résultat de l'encodage sera écrit dans OutputUrl"
type: docs

url: /fr/java/com.aspose.html.saving/resource/embed/
---
## Resource.Embed method

Intègre cette ressource dans son parent en l'encodant en Base64. Le résultat de l'encodage sera écrit dans [`OutputUrl`](../outputurl/).

```java
public Resource Embed(ResourceHandlingContext context)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| contexte | ResourceHandlingContext | Contexte de gestion des ressources. |

### Valeur de retour

Cette ressource vous permet de chaîner les appels.

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Levée s'il n'existe pas de [`ParentResource`](../../resourcehandlingcontext/parentresource/) car il n'y a nulle part où intégrer le résultat. |

### Voir aussi

* class [ResourceHandlingContext](../../resourcehandlingcontext/)
* class [Resource](../)
* package [com.aspose.html.saving](../../../com.aspose.html.saving/)
* package [Aspose.HTML](../../../)
