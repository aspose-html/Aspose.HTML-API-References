---
title: "Event.StopPropagation"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método Event. El método StopPropagation se usa para evitar la propagación adicional de un evento durante el flujo de eventos."
type: docs

url: /es/java/com.aspose.html.dom.events/event/stoppropagation/
---
## Event.StopPropagation method

El método `StopPropagation` se usa para evitar la propagación adicional de un evento durante el flujo de eventos.

```java
public void StopPropagation()
```

## Observaciones

Si este método es llamado por cualquier [`IEventListener`](../../ieventlistener/), el evento dejará de propagarse a través del árbol. El evento completará el despacho a todos los listeners en el [`IEventTarget`](../../ieventtarget/) actual antes de que el flujo de eventos se detenga. Este método puede usarse en cualquier etapa del flujo de eventos.

### Ver también

* class [Event](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
