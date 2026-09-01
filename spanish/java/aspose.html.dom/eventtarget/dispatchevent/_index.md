---
title: "EventTarget.DispatchEvent"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método de EventTarget. Despacha un Evento en el EventTarget especificado de forma síncrona, invocando los EventListeners afectados en el orden apropiado. Las reglas normales de procesamiento de eventos, incluida la fase de captura y la fase de burbujeo opcional, también se aplican a los eventos despachados manualmente con dispatchEvent"
type: docs

url: /es/java/com.aspose.html.dom/eventtarget/dispatchevent/
---
## EventTarget.DispatchEvent method

Despacha un Evento en el [`EventTarget`](../../../com.aspose.html.dom.events/ieventtarget/), (síncronamente) invocando los EventListeners afectados en el orden apropiado. Las reglas normales de procesamiento de eventos (incluida la fase de captura y la fase de burbujeo opcional) también se aplican a los eventos despachados manualmente con [`dispatchEvent()`](../../../com.aspose.html.dom.events/ieventtarget/dispatchevent/).

```java
public bool DispatchEvent(Event @event)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| evento | Evento | Especifica el tipo de evento, el comportamiento y la información contextual que se utilizará al procesar el evento. |

### Valor devuelto

El valor de retorno de indica si alguno de los listeners que manejaron el evento llamó. Si se llamó, el valor es false; de lo contrario, el valor es true.

### Excepciones

| excepción | condición |
| --- | --- |
| [dOMException](../../domexception/) |  |

## Observaciones

Los eventos despachados de esta manera tendrán el mismo comportamiento de captura y burbujeo que los eventos despachados directamente por la implementación. El objetivo del evento es el on que se llama.

### Ver también

* class [Event](../../../com.aspose.html.dom.events/event/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
