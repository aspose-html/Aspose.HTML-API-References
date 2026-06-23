---
title: "Clase UIEvent"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Clase com.aspose.html.dom.events.UIEvent. La interfaz UIEvent proporciona información contextual específica asociada con eventos de la Interfaz de Usuario."
type: docs

url: /es/java/com.aspose.html.dom.events/uievent/
---
## UIEvent class

La interfaz UIEvent proporciona información contextual específica asociada a los eventos de interfaz de usuario.

```java
public class UIEvent : Event
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [UIEvent](uievent/#constructor)(String) | Inicializa una nueva instancia de la clase `UIEvent`. |
| [UIEvent](uievent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Se usa para indicar si un evento es de tipo burbujeante o no. Si el evento puede burbujear, el valor es true; de lo contrario, el valor es false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Se usa para indicar si un evento puede tener su acción predeterminada prevenida. Si la acción predeterminada puede ser prevenida, el valor es true; de lo contrario, el valor es false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Se usa para indicar el [`IEventTarget`](../ieventtarget/) cuyos [`IEventListener`](../ieventlistener/) están siendo procesados actualmente. Esto es particularmente útil durante la captura y el burbujeo. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Devuelve true si se invocó preventDefault() mientras el valor del atributo cancelable es true, y false en caso contrario. |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) Especifica alguna información detallada sobre el Event, dependiendo del tipo de evento. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Se usa para indicar qué fase del flujo de eventos se está evaluando actualmente. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) El atributo isTrusted debe devolver el valor con el que se inicializó. Cuando se crea un evento, el atributo debe inicializarse a false. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Se usa para indicar el [`IEventTarget`](../ieventtarget/) al que el evento se envió originalmente. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Se usa para especificar el tiempo (en milisegundos relativos a la época) en que se creó el evento. Debido a que algunos sistemas pueden no proporcionar esta información, el valor de timeStamp puede no estar disponible para todos los eventos. Cuando no esté disponible, se devolverá un valor de 0. Ejemplos de tiempo de época son el momento del inicio del sistema o 0:0:0 UTC 1 de enero de 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) El nombre del evento (sin distinción de mayúsculas y minúsculas). El nombre debe ser un nombre XML. |
| [getView](../../com.aspose.html.dom.events/uievent/view/) El atributo view identifica la Window desde la cual se generó el evento. El valor no inicializado de este atributo DEBE ser null. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Este método se utiliza para obtener el objeto ECMAScript. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | El método [`InitEvent`](../event/initevent/) se usa para inicializar el valor de un [`Event`](../event/) creado a través de la interfaz [`IDocumentEvent`](../idocumentevent/). |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Si un evento es cancelable, el método [`PreventDefault`](../event/preventdefault/) se usa para indicar que el evento debe cancelarse, lo que significa que cualquier acción predeterminada que normalmente ejecutaría la implementación como resultado del evento no ocurrirá. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Invocar este método impide que el evento llegue a cualquier escuchador de eventos registrado después del actual y, cuando se despacha en un árbol, también impide que el evento llegue a cualquier otro objeto. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | El método [`StopPropagation`](../event/stoppropagation/) se usa para evitar una mayor propagación de un evento durante el flujo de eventos. |

### Ver también

* class [Event](../event/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
