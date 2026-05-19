---
title: "Clase KeyboardEvent"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Clase com.aspose.html.dom.events.KeyboardEvent. La interfaz KeyboardEvent proporciona información contextual específica asociada a dispositivos de teclado. Cada evento de teclado hace referencia a una tecla mediante un valor. Los eventos de teclado se dirigen comúnmente al elemento que tiene el foco."
type: docs

url: /es/java/com.aspose.html.dom.events/keyboardevent/
---
## KeyboardEvent class

La interfaz KeyboardEvent proporciona información contextual específica asociada a dispositivos de teclado. Cada evento de teclado hace referencia a una tecla mediante un valor. Los eventos de teclado se dirigen normalmente al elemento que tiene el foco.

```java
public class KeyboardEvent : UIEvent
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [KeyboardEvent](keyboardevent/#constructor)(String) | Inicializa una nueva instancia de la clase `KeyboardEvent`. |
| [KeyboardEvent](keyboardevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [getAltKey](../../com.aspose.html.dom.events/keyboardevent/altkey/) true si el modificador de tecla Alt (alternativa) (o \"Option\") estaba activo. El valor no inicializado de este atributo DEBE ser false. |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Se usa para indicar si un evento es de tipo burbujeante o no. Si el evento puede burbujear, el valor es verdadero; de lo contrario, el valor es falso. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Se usa para indicar si un evento puede tener su acción predeterminada prevenida. Si la acción predeterminada puede ser prevenida, el valor es verdadero; de lo contrario, el valor es falso. |
| [getCode](../../com.aspose.html.dom.events/keyboardevent/code/) El código contiene una cadena que identifica la tecla física que se está presionando. El valor no se ve afectado por la distribución de teclado actual ni por el estado de los modificadores, por lo que una tecla en particular siempre devolverá el mismo valor. |
| [getCtrlKey](../../com.aspose.html.dom.events/keyboardevent/ctrlkey/) true si el modificador de tecla Control (control) estaba activo. El valor no inicializado de este atributo DEBE ser false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Se usa para indicar el [`IEventTarget`](../ieventtarget/) cuyos [`IEventListener`](../ieventlistener/) están siendo procesados actualmente. Esto es particularmente útil durante la captura y el burbujeo. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Devuelve verdadero si preventDefault() se invocó mientras el valor del atributo cancelable es verdadero, y falso en caso contrario. |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) Especifica alguna información detallada sobre el Event, dependiendo del tipo de evento. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Se usa para indicar qué fase del flujo de eventos se está evaluando actualmente. |
| [getIsComposing](../../com.aspose.html.dom.events/keyboardevent/iscomposing/) true si el evento de tecla ocurre como parte de una sesión de composición, es decir, después de un evento compositionstart y antes del evento compositionend correspondiente. El valor no inicializado de este atributo DEBE ser false. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) El atributo isTrusted debe devolver el valor con el que se inicializó. Cuando se crea un evento, el atributo debe inicializarse a false. |
| [getKey](../../com.aspose.html.dom.events/keyboardevent/key/) La tecla contiene el valor de la tecla presionada. Si el valor tiene una representación impresa, DEBE ser una cadena de caracteres Unicode no vacía, conforme al algoritmo para determinar el valor de la tecla definido en esta especificación. Si el valor es una tecla de control que no tiene representación impresa, DEBE ser uno de los valores de tecla definidos en el conjunto de valores de tecla, según lo determine el algoritmo para determinar el valor de la tecla. Las implementaciones que no puedan identificar una tecla DEBEN usar el valor de tecla Unidentified. |
| [getLocation](../../com.aspose.html.dom.events/keyboardevent/location/) El atributo location contiene una indicación de la ubicación lógica de la tecla en el dispositivo. |
| [getMetaKey](../../com.aspose.html.dom.events/keyboardevent/metakey/) true si el modificador de tecla meta (Meta) estaba activo. |
| [getRepeat](../../com.aspose.html.dom.events/keyboardevent/repeat/) true si la tecla ha sido presionada de forma sostenida. Mantener presionada una tecla DEBE resultar en la repetición de los eventos keydown, beforeinput, input en este orden, a una velocidad determinada por la configuración del sistema. Para dispositivos móviles que tienen comportamiento de pulsación larga, el primer evento de tecla con el atributo repeat con valor true DEBE servir como indicación de una pulsación larga. El tiempo que la tecla DEBE estar presionada para comenzar a repetirse depende de la configuración. |
| [getShiftKey](../../com.aspose.html.dom.events/keyboardevent/shiftkey/) true si el modificador de tecla shift (Shift) estaba activo. |
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
| const [DOM_KEY_LOCATION_LEFT](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_left/) | La tecla activada se originó en la ubicación izquierda de la tecla (cuando hay más de una ubicación posible para esta tecla). |
| const [DOM_KEY_LOCATION_NUMPAD](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_numpad/) | La activación de la tecla se originó en el teclado numérico o con una tecla virtual correspondiente al teclado numérico (cuando hay más de una ubicación posible para esta tecla). Tenga en cuenta que la tecla NumLock siempre debe codificarse con una ubicación de DOM_KEY_LOCATION_STANDARD. |
| const [DOM_KEY_LOCATION_RIGHT](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_right/) | La activación de la tecla se originó en la ubicación derecha de la tecla (cuando hay más de una ubicación posible para esta tecla). |
| const [DOM_KEY_LOCATION_STANDARD](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_standard/) | La activación de la tecla NO DEBE distinguirse como la versión izquierda o derecha de la tecla, y (excepto la tecla NumLock) no se originó en el teclado numérico (o no se originó con una tecla virtual correspondiente al teclado numérico). |

### Ver también

* class [UIEvent](../uievent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
