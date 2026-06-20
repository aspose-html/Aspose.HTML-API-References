---
title: "Event.InitEvent"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode Event. La méthode InitEvent est utilisée pour initialiser la valeur d'un Event créé via l'interface IDocumentEvent."
type: docs

url: /fr/java/com.aspose.html.dom.events/event/initevent/
---
## Event.InitEvent method

La méthode `InitEvent` est utilisée pour initialiser la valeur d'un [`Event`](../) créé via l'[`IDocumentEvent`](../../idocumentevent/) interface.

```java
public void InitEvent(String type, bool bubbles, bool cancelable)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| type | String | Le type d'événement. |
| bubbles | Boolean | si défini sur `true` [bubbles]. |
| cancelable | Boolean | si défini sur `true` [cancelable]. |

## Remarques

Cette méthode ne peut être appelée qu'avant que l'Event ne soit dispatché via la méthode [`DispatchEvent`](../../ieventtarget/dispatchevent/), bien qu'elle puisse être appelée plusieurs fois pendant cette phase si nécessaire. Si elle est appelée plusieurs fois, la dernière invocation l'emporte. Si elle est appelée depuis une sous‑classe de l'interface Event, seules les valeurs spécifiées dans la méthode initEvent sont modifiées, tous les autres attributs restent inchangés.

### Voir aussi

* class [Event](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
