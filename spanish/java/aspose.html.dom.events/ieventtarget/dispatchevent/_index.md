---
title: "IEventTarget.DispatchEvent"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método IEventTarget. Despacha un Event en el EventTarget especificado invocando de forma sincrónica los EventListeners afectados en el orden apropiado. Las reglas normales de procesamiento de eventos, incluyendo la fase de captura y la fase opcional de burbujeo, también se aplican a los eventos despachados manualmente con dispatchEvent."
type: docs

url: /es/java/com.aspose.html.dom.events/ieventtarget/dispatchevent/
---
## IEventTarget.DispatchEvent method

Envía un Event al EventTarget especificado, (síncronamente) invocando los EventListeners afectados en el orden apropiado. Las reglas normales de procesamiento de eventos (incluyendo la fase de captura y la fase opcional de burbujeo) también se aplican a los eventos enviados manualmente con dispatchEvent().

```java
public bool DispatchEvent(Event @event)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| evento | Evento | Especifica el tipo de evento, el comportamiento y la información contextual que se utilizarán al procesar el evento. |

### Valor de retorno

El valor de retorno de indica si alguno de los listeners que manejaron el evento fue llamado. Si fue llamado, el valor es false, de lo contrario el valor es true.

### Excepciones

| excepción | condición |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | Las excepciones lanzadas por los controladores de eventos se informan como excepciones no capturadas. Los controladores de eventos se ejecutan en una pila de llamadas anidada; bloquean al llamador hasta que terminan, pero las excepciones no se propagan al llamador. |

## Observaciones

Los eventos despachados de esta manera tendrán el mismo comportamiento de captura y burbujeo que los eventos despachados directamente por la implementación. El objetivo del evento es el on que se llama.

### Ver también

* class [Event](../../event/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
