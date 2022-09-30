---
title: KeyboardEvent
second_title: Referencia de API de Aspose.HTML para .NET
description: La interfaz KeyboardEvent proporciona información contextual específica asociada con dispositivos de teclado. Cada evento de teclado hace referencia a una tecla usando un valor. Los eventos de teclado normalmente se dirigen al elemento que tiene el foco.
type: docs
weight: 840
url: /es/net/aspose.html.dom.events/keyboardevent/
---
## KeyboardEvent class

La interfaz KeyboardEvent proporciona información contextual específica asociada con dispositivos de teclado. Cada evento de teclado hace referencia a una tecla usando un valor. Los eventos de teclado normalmente se dirigen al elemento que tiene el foco.

```csharp
public class KeyboardEvent : UIEvent
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [KeyboardEvent](keyboardevent#constructor)(string) | Inicializa una nueva instancia del[`KeyboardEvent`](../keyboardevent) clase. |
| [KeyboardEvent](keyboardevent#constructor_1)(string, IDictionary&lt;string, object&gt;) | Inicializa una nueva instancia del[`KeyboardEvent`](../keyboardevent) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AltKey](../../aspose.html.dom.events/keyboardevent/altkey) { get; } | verdadero si la tecla modificadora Alt (alternativa) (u "Opción") estaba activa. El valor no inicializado de este atributo DEBE ser falso. |
| [Bubbles](../../aspose.html.dom.events/event/bubbles) { get; } | Se utiliza para indicar si un evento es un evento burbujeante o no. Si el evento puede burbujear, el valor es verdadero; de lo contrario, el valor es falso. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable) { get; } | Se utiliza para indicar si un evento puede o no tener su acción predeterminada prevenida. Si se puede evitar la acción predeterminada, el valor es verdadero; de lo contrario, el valor es falso. |
| [Code](../../aspose.html.dom.events/keyboardevent/code) { get; } | El código contiene una cadena que identifica la tecla física que se presiona. El valor no se ve afectado por la disposición actual del teclado o el estado del modificador, por lo que una tecla en particular siempre devolverá el mismo valor. |
| [CtrlKey](../../aspose.html.dom.events/keyboardevent/ctrlkey) { get; } | verdadero si el modificador de tecla Control (control) estaba activo. El valor no inicializado de este atributo DEBE ser falso. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget) { get; } | Se utiliza para indicar el[`IEventTarget`](../ieventtarget) cuyo[`IEventListener`](../ieventlistener) los mensajes de correo electrónico se están procesando actualmente. Esto es especialmente útil durante la captura y el burbujeo. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented) { get; } | Devuelve verdadero si se invocó preventDefault() mientras el valor del atributo cancelable es verdadero y falso en caso contrario. |
| [Detail](../../aspose.html.dom.events/uievent/detail) { get; } | Especifica información detallada sobre el evento, según el tipo de evento. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase) { get; } | Se utiliza para indicar qué fase del flujo de eventos se está evaluando actualmente. |
| [IsComposing](../../aspose.html.dom.events/keyboardevent/iscomposing) { get; } | verdadero si el evento clave ocurre como parte de una sesión de composición, es decir, después de un evento de inicio de composición y antes del evento de finalización de composición correspondiente. El valor no inicializado de este atributo DEBE ser falso. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted) { get; } | El atributo isTrusted debe devolver el valor con el que se inicializó. Cuando se crea un evento, el atributo debe inicializarse en false. |
| [Key](../../aspose.html.dom.events/keyboardevent/key) { get; } | La tecla contiene el valor de la tecla presionada. Si el valor tiene una representación impresa, DEBE ser una cadena de caracteres Unicode no vacía, conforme al algoritmo para determinar el valor clave definido en esta especificación. Si el valor es una clave de control que no tiene representación impresa, DEBE ser uno de los valores clave definidos en el conjunto de valores clave, según lo determine el algoritmo para determinar el valor clave. Las implementaciones que no pueden identificar una clave DEBEN utilizar el valor de clave Unidentified. |
| [Location](../../aspose.html.dom.events/keyboardevent/location) { get; } | El atributo de ubicación contiene una indicación de la ubicación lógica de la clave en el dispositivo. |
| [MetaKey](../../aspose.html.dom.events/keyboardevent/metakey) { get; } | verdadero si el modificador de clave meta (Meta) estaba activo. |
| [Repeat](../../aspose.html.dom.events/keyboardevent/repeat) { get; } | verdadero si la tecla se ha presionado de manera sostenida. Mantener presionada una tecla DEBE resultar en la repetición de los eventos de pulsación de tecla, antes de la entrada, entrada en este orden, a una velocidad determinada por la configuración del sistema. Para los dispositivos móviles que tienen un comportamiento de pulsación larga de teclas, el primer evento de tecla con un valor de atributo repetido de verdadero DEBE servir como indicación de una pulsación larga de teclas. El tiempo que DEBE presionarse la tecla para comenzar a repetir depende de la configuración. |
| [ShiftKey](../../aspose.html.dom.events/keyboardevent/shiftkey) { get; } | verdadero si el modificador de tecla shift (Shift) estaba activo. |
| [Target](../../aspose.html.dom.events/event/target) { get; } | Se utiliza para indicar el[`IEventTarget`](../ieventtarget) al que se despachó originalmente el evento. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp) { get; } | Se utiliza para especificar la hora (en milisegundos con respecto a la época) en la que se creó el evento. Debido al hecho de que algunos sistemas pueden no proporcionar esta información, es posible que el valor de timeStamp no esté disponible para todos los eventos. Cuando no está disponible , se devolverá un valor de 0. Ejemplos de tiempo de época son el tiempo de inicio del sistema o 0:0:0 UTC del 1 de enero de 1970. |
| [Type](../../aspose.html.dom.events/event/type) { get; } | El nombre del evento (no distingue entre mayúsculas y minúsculas). El nombre debe ser un nombre XML. |
| [View](../../aspose.html.dom.events/uievent/view) { get; } | El atributo de vista identifica la ventana desde la cual se generó el evento. El valor no inicializado de este atributo DEBE ser nulo. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype)() | Este método se utiliza para recuperar el objeto ECMAScriptType . |
| [InitEvent](../../aspose.html.dom.events/event/initevent)(string, bool, bool) | El[`InitEvent`](../event/initevent) El método se utiliza para inicializar el valor de un[`Event`](../event) creado a través de the [`IDocumentEvent`](../idocumentevent) interfaz. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault)() | Si un evento es cancelable, el[`PreventDefault`](../event/preventdefault) El método se utiliza para indicar que el evento debe cancelarse, lo que significa que no se producirá ninguna acción predeterminada que normalmente toma la implementación como resultado del evento. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation)() | La invocación de este método evita que el evento llegue a cualquier detector de eventos registrado después del actual y, cuando se distribuye en un árbol, también evita que el evento llegue a cualquier otro objeto. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation)() | El[`StopPropagation`](../event/stoppropagation) El método se utiliza para evitar la propagación adicional de un evento durante el flujo del evento. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [DOM_KEY_LOCATION_LEFT](../../aspose.html.dom.events/keyboardevent/dom_key_location_left) | La clave activada se originó en la ubicación de la tecla izquierda (cuando hay más de una ubicación posible para esta clave). |
| const [DOM_KEY_LOCATION_NUMPAD](../../aspose.html.dom.events/keyboardevent/dom_key_location_numpad) | La activación de la tecla se originó en el teclado numérico o con una tecla virtual correspondiente al teclado numérico (cuando hay más de una ubicación posible para esta tecla). Tenga en cuenta que la tecla Bloq Num siempre debe estar codificada con una ubicación de DOM_KEY_LOCATION_STANDARD. |
| const [DOM_KEY_LOCATION_RIGHT](../../aspose.html.dom.events/keyboardevent/dom_key_location_right) | La activación de la clave se originó en la ubicación correcta de la clave (cuando hay más de una ubicación posible para esta clave). |
| const [DOM_KEY_LOCATION_STANDARD](../../aspose.html.dom.events/keyboardevent/dom_key_location_standard) | La activación de la tecla NO DEBE distinguirse como la versión izquierda o derecha de la tecla y (aparte de la tecla NumLock) no se originó en el teclado numérico (o no se originó con una tecla virtual correspondiente al teclado numérico). |

### Ver también

* class [UIEvent](../uievent)
* espacio de nombres [Aspose.Html.Dom.Events](../../aspose.html.dom.events)
* asamblea [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
