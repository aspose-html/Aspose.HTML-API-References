---
title: "Clase Event"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.dom.events.Event class. Se usa para proporcionar información contextual sobre un evento al manejador que procesa el evento."
type: docs

url: /es/java/com.aspose.html.dom.events/event/
---
## Event class

Se utiliza para proporcionar información contextual sobre un evento al manejador que procesa el evento.

```java
public class Event : DOMObject
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Event](event/#constructor)(String) | Inicializa una nueva instancia de la clase `Event`. |
| [Event](event/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Se usa para indicar si un evento es de tipo burbujeante o no. Si el evento puede burbujear, el valor es verdadero; de lo contrario, el valor es falso. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Se usa para indicar si un evento puede tener su acción predeterminada prevenida. Si la acción predeterminada puede ser prevenida, el valor es verdadero; de lo contrario, el valor es falso. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Se usa para indicar el [`IEventTarget`](../ieventtarget/) cuyos [`IEventListener`](../ieventlistener/) están siendo procesados actualmente. Esto es particularmente útil durante la captura y el burbujeo. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Devuelve verdadero si preventDefault() se invocó mientras el valor del atributo cancelable es verdadero, y falso en caso contrario. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Se usa para indicar qué fase del flujo de eventos se está evaluando actualmente. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) El atributo isTrusted debe devolver el valor con el que se inicializó. Cuando se crea un evento, el atributo debe inicializarse a false. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Se usa para indicar el [`IEventTarget`](../ieventtarget/) al que el evento fue despachado originalmente. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Se usa para especificar el tiempo (en milisegundos relativos a la época) en que se creó el evento. Debido a que algunos sistemas pueden no proporcionar esta información, el valor de timeStamp puede no estar disponible para todos los eventos. Cuando no esté disponible, se devolverá un valor de 0. Ejemplos de tiempo de época son el momento del inicio del sistema o 0:0:0 UTC 1 de enero de 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) El nombre del evento (sin distinción de mayúsculas). El nombre debe ser un nombre XML. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Este método se usa para recuperar el objeto ECMAScript. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | El método [`InitEvent`](./initevent/) se usa para inicializar el valor de un `Event` creado a través de la interfaz [`IDocumentEvent`](../idocumentevent/). |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Si un evento es cancelable, el método [`PreventDefault`](./preventdefault/) se usa para indicar que el evento debe cancelarse, lo que significa que cualquier acción predeterminada que normalmente tomaría la implementación como resultado del evento no ocurrirá. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Invocar este método impide que el evento alcance a los escuchadores de eventos registrados después del actual y, cuando se despacha en un árbol, también impide que el evento llegue a cualquier otro objeto. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | El método [`StopPropagation`](./stoppropagation/) se usa para evitar la propagación adicional de un evento durante el flujo de eventos. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [AtTargetPhase](../../com.aspose.html.dom.events/event/attargetphase/) | La fase actual del evento es la fase de captura. |
| const [BubblingPhase](../../com.aspose.html.dom.events/event/bubblingphase/) | La fase actual del evento es la fase de burbujeo. |
| const [CapturingPhase](../../com.aspose.html.dom.events/event/capturingphase/) | El evento se está evaluando actualmente en el objetivo [`IEventTarget`](../ieventtarget/). |
| const [NonePhase](../../com.aspose.html.dom.events/event/nonephase/) | Los eventos que no se están despachando actualmente están en esta fase. |

## Observaciones

Un objeto que implementa generalmente se pasa como el primer parámetro a un manejador de eventos. Información de contexto más específica se pasa a los manejadores de eventos derivando interfaces adicionales que contienen información directamente relacionada con el tipo de evento que acompañan. Estas interfaces derivadas también son implementadas por el objeto pasado al escuchador de eventos.

### Ver también

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
