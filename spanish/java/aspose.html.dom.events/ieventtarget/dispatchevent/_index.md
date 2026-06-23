---
title: "IEventTarget.DispatchEvent"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método IEventTarget. Despacha un Event en el EventTarget especificado invocando sincrónicamente los EventListeners afectados en el orden apropiado. Las reglas normales de procesamiento de eventos, incluida la fase de captura y la fase opcional de burbujeo, también se aplican a los eventos despachados manualmente con dispatchEvent."
type: docs

url: /es/java/com.aspose.html.dom.events/ieventtarget/dispatchevent/
---
## IEventTarget.DispatchEvent method

Despacha un Event en el EventTarget especificado, (síncronamente) invocando los EventListeners afectados en el orden apropiado. Las reglas normales de procesamiento de eventos (incluyendo la fase de captura y la fase de burbujeo opcional) también se aplican a los eventos despachados manualmente con dispatchEvent().

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
| [dOMException](../../../com.aspose.html.dom/domexception/) | Las excepciones lanzadas por los manejadores de eventos se informan como excepciones no capturadas. Los manejadores de eventos se ejecutan en una pila de llamadas anidada; bloquean al llamador hasta que completan, pero las excepciones no se propagan al llamador. |

## Observaciones

Los eventos despachados de esta manera tendrán el mismo comportamiento de captura y burbujeo que los eventos despachados directamente por la implementación. El objetivo del evento es el on que se llama.

### Ver también

* class [Event](../../event/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
