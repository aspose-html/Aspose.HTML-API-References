---
title: "Interfaz IEventTarget"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.dom.events.IEventTarget interface. La interfaz EventTarget es implementada por todos los Node en una implementación que soporta el Modelo de Eventos DOM. Por lo tanto, esta interfaz puede obtenerse usando métodos de casting específicos del enlace sobre una instancia de la interfaz Node. La interfaz permite el registro y la eliminación de Event Listeners en un y la distribución de eventos a ese"
type: docs

url: /es/java/com.aspose.html.dom.events/ieventtarget/
---
## IEventTarget interface

La interfaz EventTarget es implementada por todos los Nodes en una implementación que soporta el Modelo de Eventos DOM. Por lo tanto, esta interfaz puede obtenerse usando métodos de casting específicos de enlace en una instancia de la interfaz Node. La interfaz permite el registro y la eliminación de Event Listeners en un nodo y el despacho de eventos a ese.

```java
public interface IEventTarget
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener)(String, IEventListener) | El método addEventListener() de EventTarget configura una función que será llamada siempre que el evento especificado se entregue al objetivo. |
| [addEventListener](../../com.aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(String, IEventListener, bool) | El método addEventListener() de EventTarget configura una función que será llamada siempre que el evento especificado se entregue al objetivo. |
| [dispatchEvent](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/)(Event) | Envía un Event al EventTarget especificado, (síncronamente) invocando los EventListeners afectados en el orden apropiado. Las reglas normales de procesamiento de eventos (incluyendo la fase de captura y la fase opcional de burbujeo) también se aplican a los eventos enviados manualmente con dispatchEvent(). |
| [removeEventListener](../../com.aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(String, IEventListener) | Este método permite la eliminación de event listeners del event target. Si un event listener se elimina mientras se está procesando un evento, no será activado por las acciones actuales. Los Event Listeners nunca pueden ser invocados después de ser eliminados. |
| [removeEventListener](../../com.aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(String, IEventListener, bool) | Este método permite la eliminación de event listeners del event target. Si un event listener se elimina mientras se está procesando un evento, no será activado por las acciones actuales. Los Event Listeners nunca pueden ser invocados después de ser eliminados. |

### Ver también

* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
