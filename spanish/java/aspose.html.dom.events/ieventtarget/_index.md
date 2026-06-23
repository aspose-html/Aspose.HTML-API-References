---
title: "Interfaz IEventTarget"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "interfaz com.aspose.html.dom.events.IEventTarget. La interfaz EventTarget es implementada por todos los Nodos en una implementación que soporta el Modelo de Eventos DOM. Por lo tanto, esta interfaz puede obtenerse usando métodos de casting específicos del enlace en una instancia de la interfaz Node. La interfaz permite el registro y la eliminación de Event Listeners y el despacho de eventos a ese."
type: docs

url: /es/java/com.aspose.html.dom.events/ieventtarget/
---
## IEventTarget interface

La interfaz EventTarget es implementada por todos los Nodes en una implementación que soporta el Modelo de Eventos DOM. Por lo tanto, esta interfaz puede obtenerse usando métodos de casting específicos de enlace en una instancia de la interfaz Node. La interfaz permite el registro y la eliminación de Event Listeners en un objeto y el despacho de eventos a ese.

```java
public interface IEventTarget
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener)(String, IEventListener) | El método addEventListener() de EventTarget configura una función que será llamada siempre que el evento especificado sea entregado al objetivo. |
| [addEventListener](../../com.aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(String, IEventListener, bool) | El método addEventListener() de EventTarget configura una función que será llamada siempre que el evento especificado sea entregado al objetivo. |
| [dispatchEvent](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/)(Event) | Despacha un Event en el EventTarget especificado, (síncronamente) invocando los EventListeners afectados en el orden apropiado. Las reglas normales de procesamiento de eventos (incluyendo la fase de captura y la fase de burbujeo opcional) también se aplican a los eventos despachados manualmente con dispatchEvent(). |
| [removeEventListener](../../com.aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(String, IEventListener) | Este método permite la eliminación de Event Listeners del objetivo del evento. Si un Event Listener se elimina de un elemento mientras se está procesando un evento, no se activará por las acciones actuales. Los Event Listeners nunca pueden ser invocados después de ser eliminados. |
| [removeEventListener](../../com.aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(String, IEventListener, bool) | Este método permite la eliminación de Event Listeners del objetivo del evento. Si un Event Listener se elimina de un elemento mientras se está procesando un evento, no se activará por las acciones actuales. Los Event Listeners nunca pueden ser invocados después de ser eliminados. |

### Ver también

* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
