---
title: "Event.StopPropagation"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode Event. La méthode StopPropagation est utilisée pour empêcher la propagation supplémentaire d'un événement pendant le flux d'événements"
type: docs

url: /fr/java/com.aspose.html.dom.events/event/stoppropagation/
---
## Event.StopPropagation method

La méthode `StopPropagation` est utilisée pour empêcher la propagation supplémentaire d'un événement pendant le flux d'événements.

```java
public void StopPropagation()
```

## Remarques

Si cette méthode est appelée par n'importe quel [`IEventListener`](../../ieventlistener/), l'événement cessera de se propager dans l'arbre. L'événement terminera le dispatch vers tous les écouteurs sur le [`IEventTarget`](../../ieventtarget/) actuel avant que le flux d'événements ne s'arrête. Cette méthode peut être utilisée à n'importe quelle étape du flux d'événements.

### Voir aussi

* class [Event](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
