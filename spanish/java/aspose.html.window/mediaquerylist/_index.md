---
title: "Clase MediaQueryList"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Clase com.aspose.html.window.MediaQueryList. Un objeto MediaQueryList almacena información sobre una consulta de medios aplicada a un documento, con soporte tanto para coincidencia inmediata como basada en eventos contra el estado del documento. Consulte la especificación del módulo de vista CSSOM https//www.w3.org/TR/cssom-view/the-mediaquerylist-interface"
type: docs

url: /es/java/com.aspose.html.window/mediaquerylist/
---
## MediaQueryList class

Un objeto MediaQueryList almacena información sobre una consulta de medios aplicada a un documento, con soporte tanto para coincidencias inmediatas como basadas en eventos contra el estado del documento. Consulte la especificación del módulo de vista CSSOM: [https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface](https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface)

```java
public class MediaQueryList : EventTarget
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getDocument](../../com.aspose.html.window/mediaquerylist/document/) Documento asociado al objeto de contexto. |
| [getMatches](../../com.aspose.html.window/mediaquerylist/matches/) Un valor booleano que devuelve true si el documento coincide actualmente con la lista de consultas de medios, o false en caso contrario. |
| [getMedia](../../com.aspose.html.window/mediaquerylist/media/) Una cadena que representa una consulta de medios serializada. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | The addEventListener() method of the [`EventTarget `](../../com.aspose.html.dom/eventtarget/)interface sets up a function that will be called whenever the specified event is delivered to the target. El método addEventListener() de la interfaz [`EventTarget `](../../com.aspose.html.dom/eventtarget/) configura una función que será llamada siempre que el evento especificado se entregue al objetivo. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | El método addEventListener() de la interfaz [EventTarget ](T:com.aspose.html.dom.EventTarget) configura una función que será llamada cada vez que el evento especificado se entregue al objetivo. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | El método addEventListener() de la interfaz [EventTarget ](T:com.aspose.html.dom.EventTarget) configura una función que será llamada cada vez que el evento especificado se entregue al objetivo. |
| [addListener](../../com.aspose.html.window/mediaquerylist/addlistener/)(IEventListener) | Agregar un escuchador de eventos de cambio de estado de coincidencias de MediaQueryList. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Envía un Event al [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/) especificado, (de forma sincrónica) invocando los EventListeners afectados en el orden apropiado. Las reglas normales de procesamiento de eventos (incluyendo la fase de captura y la fase opcional de burbujeo) también se aplican a los eventos enviados manualmente con [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Realiza tareas definidas por la aplicación asociadas con la liberación, el desbloqueo o el restablecimiento de recursos no administrados. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Este método se utiliza para obtener el objeto ECMAScript. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Este método permite la eliminación de Event Listeners del objetivo del evento. Si un Event Listener se elimina de un elemento mientras se está procesando un evento, no se activará por las acciones actuales. Los Event Listeners nunca pueden ser invocados después de ser eliminados. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Este método permite la eliminación de Event Listeners del objetivo del evento. Si un Event Listener se elimina de un elemento mientras se está procesando un evento, no se activará por las acciones actuales. Los Event Listeners nunca pueden ser invocados después de ser eliminados. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Este método permite la eliminación de Event Listeners del objetivo del evento. Si un Event Listener se elimina de un elemento mientras se está procesando un evento, no se activará por las acciones actuales. Los Event Listeners nunca pueden ser invocados después de ser eliminados. |
| [removeListener](../../com.aspose.html.window/mediaquerylist/removelistener/)(IEventListener) | Eliminar el escuchador de eventos de cambio de estado de coincidencias de MediaQueryList. |

## Eventos

| Nombre | Descripción |
| --- | --- |
| event [OnChange](../../com.aspose.html.window/mediaquerylist/onchange/) | Evento que se dispara en el MediaQueryList cuando cambia el estado de coincidencias. |

### Ver también

* class [EventTarget](../../com.aspose.html.dom/eventtarget/)
* package [com.aspose.html.window](../../com.aspose.html.window/)
* package [Aspose.HTML](../../)
