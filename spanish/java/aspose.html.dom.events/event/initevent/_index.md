---
title: "Event.InitEvent"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método del evento. El método InitEvent se usa para inicializar el valor de un Evento creado a través de la interfaz IDocumentEvent"
type: docs

url: /es/java/com.aspose.html.dom.events/event/initevent/
---
## Event.InitEvent method

El método `InitEvent` se usa para inicializar el valor de un [`Event`](../) creado a través de la [`IDocumentEvent`](../../idocumentevent/) interfaz.

```java
public void InitEvent(String type, bool bubbles, bool cancelable)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tipo | String | El tipo de evento. |
| bubbles | Boolean | si se establece en `true` [bubbles]. |
| cancelable | Boolean | si se establece en `true` [cancelable]. |

## Observaciones

Este método solo puede llamarse antes de que el Event haya sido despachado mediante el método [`DispatchEvent`](../../ieventtarget/dispatchevent/), aunque puede llamarse varias veces durante esa fase si es necesario. Si se llama varias veces, la invocación final tiene prioridad. Si se llama desde una subclase de la interfaz Event, solo se modifican los valores especificados en el método initEvent, todos los demás atributos permanecen sin cambios.

### Ver también

* class [Event](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
