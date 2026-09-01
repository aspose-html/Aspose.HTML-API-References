---
title: "Clase SVGZoomEvent"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Clase com.aspose.html.dom.svg.events.SVGZoomEvent. El evento de zoom ocurre cuando el usuario inicia una acción que hace que la vista actual del fragmento del documento SVG sea reescalada. Los controladores de eventos solo se reconocen en elementos svg."
type: docs

url: /es/java/com.aspose.html.dom.svg.events/svgzoomevent/
---
## SVGZoomEvent class

El evento de zoom ocurre cuando el usuario inicia una acción que hace que la vista actual del fragmento del documento SVG se vuelva a escalar. Los manejadores de eventos solo se reconocen en elementos ‘svg’.

```java
public class SVGZoomEvent : Event
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Se usa para indicar si un evento es de tipo burbujeante o no. Si el evento puede burbujear, el valor es true; de lo contrario, el valor es false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Se usa para indicar si un evento puede tener su acción predeterminada prevenida. Si la acción predeterminada puede ser prevenida, el valor es true; de lo contrario, el valor es false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Se usa para indicar el [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/) cuyo(s) [`IEventListener`](../../com.aspose.html.dom.events/ieventlistener/) están siendo procesados actualmente. Esto es particularmente útil durante la captura y la propagación. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Devuelve true si se invocó preventDefault() mientras el valor del atributo cancelable es true, y false en caso contrario. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Se usa para indicar qué fase del flujo de eventos se está evaluando actualmente. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) El atributo isTrusted debe devolver el valor con el que se inicializó. Cuando se crea un evento, el atributo debe inicializarse a false. |
| [getNewScale](../../com.aspose.html.dom.svg.events/svgzoomevent/newscale/) El factor de escala que estará en vigor después de que la operación de zoom haya sido procesada. |
| [getNewTranslate](../../com.aspose.html.dom.svg.events/svgzoomevent/newtranslate/) Los valores de traslación que estarán en vigor después de que la operación de zoom haya sido procesada. El objeto SVGPoint es de solo lectura. |
| [getPreviousScale](../../com.aspose.html.dom.svg.events/svgzoomevent/previousscale/) El factor de escala de operaciones de zoom anteriores que estaba en vigor antes de que ocurriera la operación de zoom. |
| [getPreviousTranslate](../../com.aspose.html.dom.svg.events/svgzoomevent/previoustranslate/) Los valores de traslación de operaciones de zoom anteriores que estaban en vigor antes de que ocurriera la operación de zoom. El objeto SVGPoint es de solo lectura. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Se usa para indicar el [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/) al que el evento fue despachado originalmente. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Se usa para especificar el tiempo (en milisegundos relativos a la época) en que se creó el evento. Debido a que algunos sistemas pueden no proporcionar esta información, el valor de timeStamp puede no estar disponible para todos los eventos. Cuando no esté disponible, se devolverá un valor de 0. Ejemplos de tiempo de época son el momento del inicio del sistema o 0:0:0 UTC 1 de enero de 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) El nombre del evento (sin distinción de mayúsculas y minúsculas). El nombre debe ser un nombre XML. |
| [getZoomRectScreen](../../com.aspose.html.dom.svg.events/svgzoomevent/zoomrectscreen/) El rectángulo de zoom especificado en unidades de pantalla. El objeto SVGRect es de solo lectura. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Este método se utiliza para obtener el objeto ECMAScript. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | El método [`InitEvent`](../../com.aspose.html.dom.events/event/initevent/) se usa para inicializar el valor de un [`Event`](../../com.aspose.html.dom.events/event/) creado a través de la interfaz [`IDocumentEvent`](../../com.aspose.html.dom.events/idocumentevent/). |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Si un evento es cancelable, el método [`PreventDefault`](../../com.aspose.html.dom.events/event/preventdefault/) se usa para indicar que el evento debe cancelarse, lo que significa que cualquier acción predeterminada que normalmente ejecutaría la implementación como resultado del evento no ocurrirá. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Invocar este método impide que el evento llegue a cualquier escuchador de eventos registrado después del actual y, cuando se despacha en un árbol, también impide que el evento llegue a cualquier otro objeto. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | El método [`StopPropagation`](../../com.aspose.html.dom.events/event/stoppropagation/) se usa para evitar una mayor propagación de un evento durante el flujo de eventos. |

### Ver también

* class [Event](../../com.aspose.html.dom.events/event/)
* package [com.aspose.html.dom.svg.events](../../com.aspose.html.dom.svg.events/)
* package [Aspose.HTML](../../)
