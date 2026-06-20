---
title: "IDocumentEvent.CreateEvent"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode IDocumentEvent. La méthode createEvent est utilisée pour créer des Events lorsque il est soit incommode soit inutile que l'utilisateur crée lui‑même un Event."
type: docs

url: /fr/java/com.aspose.html.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

La méthode createEvent est utilisée pour créer des Events lorsqu'il est soit peu pratique, soit inutile que l'utilisateur crée lui-même un Event.

```java
public Event CreateEvent(String eventType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| eventType | String | Le paramètre eventType spécifie le type d'interface à créer. Si l'interface spécifiée est prise en charge par l'implémentation, cette méthode renverra une nouvelle instance du type d'interface demandé. Si le est destiné à être dispatché via la méthode, la méthode appropriée doit être appelée après la création afin d'initialiser les valeurs. La méthode est utilisée pour créer des s lorsque cela est soit incommode soit inutile que l'utilisateur crée un lui‑même. Dans les cas où l'implémentation fournie est insuffisante, les utilisateurs peuvent fournir leurs propres implémentations à utiliser avec la méthode. |

### Valeur de retour

Renvoie l'événement nouvellement créé du type d'événement spécifié.

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR : Levé si l'implementation ne prend pas en charge le type d'interface demandé |

### Voir aussi

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
