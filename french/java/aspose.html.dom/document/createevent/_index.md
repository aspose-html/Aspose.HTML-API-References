---
title: "Document.CreateEvent"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode Document. Crée un Event d'un type pris en charge par l'implémentation"
type: docs

url: /fr/java/com.aspose.html.dom/document/createevent/
---
## Document.CreateEvent method

Crée un [`Event`](../../../com.aspose.html.dom.events/event/) d'un type pris en charge par l'implémentation.

```java
public Event CreateEvent(String eventType)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| eventType | String | Le paramètre eventType spécifie le type d'interface [`Event`](../../../com.aspose.html.dom.events/event/) à créer. Si l'interface [`Event`](../../../com.aspose.html.dom.events/event/) spécifiée est prise en charge par l'implémentation, cette méthode renverra un nouveau [`Event`](../../../com.aspose.html.dom.events/event/) du type d'interface demandé. Si le [`Event`](../../../com.aspose.html.dom.events/event/) doit être déclenché via la méthode [`DispatchEvent`](../../../com.aspose.html.dom.events/ieventtarget/dispatchevent/), la méthode [`InitEvent`](../../../com.aspose.html.dom.events/event/initevent/) appropriée doit être appelée après la création afin d'initialiser les valeurs du [`Event`](../../../com.aspose.html.dom.events/event/). |

### Valeur de retour

Le [`Event`](../../../com.aspose.html.dom.events/event/) nouvellement créé

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR : Levé si l'implémentation ne prend pas en charge le type d'interface [`Event`](../../../com.aspose.html.dom.events/event/) demandé |

### Voir aussi

* class [Event](../../../com.aspose.html.dom.events/event/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
