---
title: "Clase CustomEvent"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Clase com.aspose.html.dom.events.CustomEvent. Los eventos que usan la interfaz CustomEvent pueden usarse para transportar datos personalizados."
type: docs

url: /es/java/com.aspose.html.dom.events/customevent/
---
## CustomEvent class

Los eventos que utilizan la interfaz CustomEvent pueden usarse para transportar datos personalizados.

```java
public class CustomEvent : Event
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [CustomEvent](customevent/#constructor)(String) | Inicializa una nueva instancia de la clase `CustomEvent`. |
| [CustomEvent](customevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Se usa para indicar si un evento es de tipo burbujeante o no. Si el evento puede burbujear, el valor es true; de lo contrario, el valor es false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Se usa para indicar si un evento puede tener su acción predeterminada prevenida. Si la acción predeterminada puede ser prevenida, el valor es true; de lo contrario, el valor es false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Se usa para indicar el [`IEventTarget`](../ieventtarget/) cuyos [`IEventListener`](../ieventlistener/) están siendo procesados actualmente. Esto es particularmente útil durante la captura y el burbujeo. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Devuelve true si se invocó preventDefault() mientras el valor del atributo cancelable es true, y false en caso contrario. |
| [getDetail](../../com.aspose.html.dom.events/customevent/detail/) Obtiene los datos personalizados. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Se usa para indicar qué fase del flujo de eventos se está evaluando actualmente. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) El atributo isTrusted debe devolver el valor con el que se inicializó. Cuando se crea un evento, el atributo debe inicializarse a false. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Se usa para indicar el [`IEventTarget`](../ieventtarget/) al que el evento se envió originalmente. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Se usa para especificar el tiempo (en milisegundos relativos a la época) en que se creó el evento. Debido a que algunos sistemas pueden no proporcionar esta información, el valor de timeStamp puede no estar disponible para todos los eventos. Cuando no esté disponible, se devolverá un valor de 0. Ejemplos de tiempo de época son el momento del inicio del sistema o 0:0:0 UTC 1 de enero de 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) El nombre del evento (sin distinción de mayúsculas y minúsculas). El nombre debe ser un nombre XML. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Este método se utiliza para obtener el objeto ECMAScript. |
| [initCustomEvent](../../com.aspose.html.dom.events/customevent/initcustomevent/)(String, bool, bool, object) | /// El método [`InitEvent`](../event/initevent/) se usa para inicializar el valor de un [`Event`](../event/) creado a través de la interfaz [`IDocumentEvent`](../idocumentevent/). |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | El método [`InitEvent`](../event/initevent/) se usa para inicializar el valor de un [`Event`](../event/) creado a través de la interfaz [`IDocumentEvent`](../idocumentevent/). |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Si un evento es cancelable, el método [`PreventDefault`](../event/preventdefault/) se usa para indicar que el evento debe cancelarse, lo que significa que cualquier acción predeterminada que normalmente ejecutaría la implementación como resultado del evento no ocurrirá. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Invocar este método impide que el evento llegue a cualquier escuchador de eventos registrado después del actual y, cuando se despacha en un árbol, también impide que el evento llegue a cualquier otro objeto. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | El método [`StopPropagation`](../event/stoppropagation/) se usa para evitar una mayor propagación de un evento durante el flujo de eventos. |

### Ver también

* class [Event](../event/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
