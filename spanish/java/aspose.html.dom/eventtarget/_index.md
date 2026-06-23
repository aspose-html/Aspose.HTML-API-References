---
title: "Clase EventTarget"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Clase com.aspose.html.dom.EventTarget. La interfaz EventTarget es implementada por objetos que pueden recibir eventos y pueden tener escuchadores para ellos. En otras palabras, cualquier objetivo de eventos implementa los tres métodos asociados con esta interfaz."
type: docs

url: /es/java/com.aspose.html.dom/eventtarget/
---
## EventTarget class

La interfaz EventTarget es implementada por objetos que pueden recibir eventos y pueden tener escuchadores para ellos. En otras palabras, cualquier objetivo de eventos implementa los tres métodos asociados con esta interfaz.

[`Element`](../element/), and its children, as well as [`Document`](../document/) and Window, are the most common event targets, but other objects can be event targets, too.

```java
public class EventTarget : DOMObject, IDisposable, IEventTarget
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [EventTarget](eventtarget/)() | Inicializa una nueva instancia del objeto EventTarget. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_1)(String, IEventListener) | El método addEventListener() de la interfaz `EventTarget `configura una función que será llamada cada vez que el evento especificado se entregue al objetivo. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/#addeventlistener)(String, DOMEventHandler, bool) | El método addEventListener() de la interfaz [EventTarget ](T:com.aspose.html.dom.EventTarget) configura una función que será llamada cada vez que el evento especificado se entregue al objetivo. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_2)(String, IEventListener, bool) | El método addEventListener() de la interfaz [EventTarget ](T:com.aspose.html.dom.EventTarget) configura una función que será llamada cada vez que el evento especificado se entregue al objetivo. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Envía un Event al [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) especificado, (de forma sincrónica) invocando los EventListeners afectados en el orden apropiado. Las reglas normales de procesamiento de eventos (incluyendo la fase de captura y la fase opcional de burbujeo) también se aplican a los eventos enviados manualmente con [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Realiza tareas definidas por la aplicación asociadas con la liberación, el desbloqueo o el restablecimiento de recursos no administrados. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Este método se utiliza para obtener el objeto ECMAScript. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_1)(String, IEventListener) | Este método permite la eliminación de Event Listeners del objetivo del evento. Si un Event Listener se elimina de un elemento mientras se está procesando un evento, no se activará por las acciones actuales. Los Event Listeners nunca pueden ser invocados después de ser eliminados. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener)(String, DOMEventHandler, bool) | Este método permite la eliminación de Event Listeners del objetivo del evento. Si un Event Listener se elimina de un elemento mientras se está procesando un evento, no se activará por las acciones actuales. Los Event Listeners nunca pueden ser invocados después de ser eliminados. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_2)(String, IEventListener, bool) | Este método permite la eliminación de Event Listeners del objetivo del evento. Si un Event Listener se elimina de un elemento mientras se está procesando un evento, no se activará por las acciones actuales. Los Event Listeners nunca pueden ser invocados después de ser eliminados. |

### Ver también

* class [DOMObject](../domobject/)
* interface [IEventTarget](../../com.aspose.html.dom.events/ieventtarget/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
