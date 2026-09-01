---
title: "TimeEvent.InitTimeEvent"
second_title: "Référence de l'API Aspose.HTML pour Java"
description: "Méthode TimeEvent. La méthode initTimeEvent est utilisée pour initialiser la valeur d'un TimeEvent créé via l'interface DocumentEvent. Cette méthode ne peut être appelée qu'avant que le TimeEvent ne soit dispatché via la méthode dispatchEvent, bien qu'elle puisse être appelée plusieurs fois pendant cette phase si nécessaire. Si elle est appelée plusieurs fois, la dernière invocation l'emporte."
type: docs

url: /fr/java/com.aspose.html.dom.svg.events/timeevent/inittimeevent/
---
## TimeEvent.InitTimeEvent method

La méthode initTimeEvent est utilisée pour initialiser la valeur d'un TimeEvent créé via l'interface DocumentEvent. Cette méthode ne peut être appelée qu'avant que le TimeEvent ne soit dispatché via la méthode dispatchEvent, bien qu'elle puisse être appelée plusieurs fois pendant cette phase si nécessaire. Si elle est appelée plusieurs fois, la dernière invocation l'emporte.

```java
public void InitTimeEvent(String typeArg, IAbstractView viewArg, long detailArg)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| typeArg | String | Spécifie le type d'événement. |
| viewArg | IAbstractView | Spécifie l'AbstractView de l'événement. |
| detailArg | Int64 | Spécifie le détail de l'événement. |

### Voir aussi

* interface [IAbstractView](../../../com.aspose.html.dom.views/iabstractview/)
* class [TimeEvent](../)
* package [com.aspose.html.dom.svg.events](../../../com.aspose.html.dom.svg.events/)
* package [Aspose.HTML](../../../)
