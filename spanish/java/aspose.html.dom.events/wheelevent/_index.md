---
title: "Clase WheelEvent"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "com.aspose.html.dom.events.WheelEvent class. La interfaz WheelEvent proporciona información contextual específica asociada a eventos de rueda. Para crear una instancia de la interfaz WheelEvent, use el constructor WheelEvent pasando un diccionario opcional WheelEventInit."
type: docs

url: /es/java/com.aspose.html.dom.events/wheelevent/
---
## WheelEvent class

La interfaz WheelEvent proporciona información contextual específica asociada a eventos de rueda. Para crear una instancia de la interfaz WheelEvent, use el constructor WheelEvent, pasando un diccionario opcional WheelEventInit.

```java
public class WheelEvent : MouseEvent
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [WheelEvent](wheelevent/#constructor)(String) | Inicializa una nueva instancia de la clase `WheelEvent`. |
| [WheelEvent](wheelevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getAltKey](../../com.aspose.html.dom.events/mouseevent/altkey/) Consulte el atributo altKey. |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Se usa para indicar si un evento es de tipo burbujeante o no. Si el evento puede burbujear, el valor es verdadero; de lo contrario, el valor es falso. |
| [getButton](../../com.aspose.html.dom.events/mouseevent/button/) Durante los eventos de ratón causados por la pulsación o liberación de un botón del ratón, button DEBE usarse para indicar qué botón del dispositivo apuntador cambió de estado. |
| [getButtons](../../com.aspose.html.dom.events/mouseevent/buttons/) Durante cualquier evento de ratón, buttons DEBE usarse para indicar qué combinación de botones del ratón está actualmente presionada, expresada como una máscara de bits. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Se usa para indicar si un evento puede tener su acción predeterminada prevenida. Si la acción predeterminada puede ser prevenida, el valor es verdadero; de lo contrario, el valor es falso. |
| [getClientX](../../com.aspose.html.dom.events/mouseevent/clientx/) La coordenada horizontal en la que ocurrió el evento respecto al viewport asociado con el evento. |
| [getClientY](../../com.aspose.html.dom.events/mouseevent/clienty/) La coordenada vertical en la que ocurrió el evento respecto al viewport asociado con el evento. |
| [getCtrlKey](../../com.aspose.html.dom.events/mouseevent/ctrlkey/) Consulte el atributo ctrlKey. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Se usa para indicar el [`IEventTarget`](../ieventtarget/) cuyos [`IEventListener`](../ieventlistener/) están siendo procesados actualmente. Esto es particularmente útil durante la captura y el burbujeo. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Devuelve verdadero si preventDefault() se invocó mientras el valor del atributo cancelable es verdadero, y falso en caso contrario. |
| [getDeltaMode](../../com.aspose.html.dom.events/wheelevent/deltamode/) El atributo deltaMode contiene una indicación de las unidades de medida para los valores delta. El valor predeterminado es DOM_DELTA_PIXEL (píxeles). |
| [getDeltaX](../../com.aspose.html.dom.events/wheelevent/deltax/) En los agentes de usuario donde la acción predeterminada del evento de rueda es desplazarse, el valor DEBE ser la medida a lo largo del eje x (en píxeles, líneas o páginas) que se desplazará en caso de que el evento no sea cancelado. De lo contrario, esta es una medida específica de la implementación (en píxeles, líneas o páginas) del movimiento de un dispositivo de rueda alrededor del eje x. |
| [getDeltaY](../../com.aspose.html.dom.events/wheelevent/deltay/) En los agentes de usuario donde la acción predeterminada del evento de rueda es desplazarse, el valor DEBE ser la medida a lo largo del eje y (en píxeles, líneas o páginas) que se desplazará en caso de que el evento no sea cancelado. De lo contrario, esta es una medida específica de la implementación (en píxeles, líneas o páginas) del movimiento de un dispositivo de rueda alrededor del eje y. |
| [getDeltaZ](../../com.aspose.html.dom.events/wheelevent/deltaz/) En los agentes de usuario donde la acción predeterminada del evento de rueda es desplazarse, el valor DEBE ser la medida a lo largo del eje z (en píxeles, líneas o páginas) que se desplazará en caso de que el evento no sea cancelado. De lo contrario, esta es una medida específica de la implementación (en píxeles, líneas o páginas) del movimiento de un dispositivo de rueda alrededor del eje z. |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) Especifica alguna información detallada sobre el Event, dependiendo del tipo de evento. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Se usa para indicar qué fase del flujo de eventos se está evaluando actualmente. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) El atributo isTrusted debe devolver el valor con el que se inicializó. Cuando se crea un evento, el atributo debe inicializarse a false. |
| [getMetaKey](../../com.aspose.html.dom.events/mouseevent/metakey/) Consulte el atributo metaKey. |
| [getRelatedTarget](../../com.aspose.html.dom.events/mouseevent/relatedtarget/) Utilizado para identificar un EventTarget secundario relacionado con un evento de UI, dependiendo del tipo de evento. |
| [getScreenX](../../com.aspose.html.dom.events/mouseevent/screenx/) La coordenada horizontal en la que ocurrió el evento respecto al origen del sistema de coordenadas de la pantalla. |
| [getScreenY](../../com.aspose.html.dom.events/mouseevent/screeny/) La coordenada vertical en la que ocurrió el evento respecto al origen del sistema de coordenadas de la pantalla. |
| [getShiftKey](../../com.aspose.html.dom.events/mouseevent/shiftkey/) Consulte el atributo shiftKey. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Se usa para indicar el [`IEventTarget`](../ieventtarget/) al que el evento fue despachado originalmente. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Se usa para especificar el tiempo (en milisegundos relativos a la época) en que se creó el evento. Debido a que algunos sistemas pueden no proporcionar esta información, el valor de timeStamp puede no estar disponible para todos los eventos. Cuando no esté disponible, se devolverá un valor de 0. Ejemplos de tiempo de época son el momento del inicio del sistema o 0:0:0 UTC 1 de enero de 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) El nombre del evento (sin distinción de mayúsculas). El nombre debe ser un nombre XML. |
| [getView](../../com.aspose.html.dom.events/uievent/view/) El atributo view identifica la Window desde la cual se generó el evento. El valor no inicializado de este atributo DEBE ser null. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Este método se usa para recuperar el objeto ECMAScript. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | El método [`InitEvent`](../event/initevent/) se usa para inicializar el valor de un [`Event`](../event/) creado a través de la interfaz[`IDocumentEvent`](../idocumentevent/). |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Si un evento es cancelable, el método [`PreventDefault`](../event/preventdefault/) se usa para indicar que el evento debe cancelarse, lo que significa que cualquier acción predeterminada que normalmente ejecutaría la implementación como resultado del evento no ocurrirá. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Invocar este método impide que el evento alcance a los escuchadores de eventos registrados después del actual y, cuando se despacha en un árbol, también impide que el evento llegue a cualquier otro objeto. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | El método [`StopPropagation`](../event/stoppropagation/) se usa para evitar una mayor propagación de un evento durante el flujo de eventos. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [DOM_DELTA_LINE](../../com.aspose.html.dom.events/wheelevent/dom_delta_line/) | Las unidades de medida para el delta DEBEN ser líneas individuales de texto. Este es el caso para muchos controles de formulario. |
| const [DOM_DELTA_PAGE](../../com.aspose.html.dom.events/wheelevent/dom_delta_page/) | Las unidades de medida para el delta DEBEN ser páginas, ya sea definidas como una sola pantalla o como una página demarcada. |
| const [DOM_DELTA_PIXEL](../../com.aspose.html.dom.events/wheelevent/dom_delta_pixel/) | Las unidades de medida para el delta DEBEN ser píxeles. Este es el caso más típico en la mayoría de los sistemas operativos y configuraciones de implementación. |

### Ver también

* class [MouseEvent](../mouseevent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
