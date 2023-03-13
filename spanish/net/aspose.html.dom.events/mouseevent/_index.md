---
title: Class MouseEvent
second_title: Referencia de API de Aspose.HTML para .NET
description: Aspose.Html.Dom.Events.MouseEvent clase. La interfaz MouseEvent proporciona información contextual específica asociada con los eventos del mouse.
type: docs
weight: 840
url: /es/net/aspose.html.dom.events/mouseevent/
---
## MouseEvent class

La interfaz MouseEvent proporciona información contextual específica asociada con los eventos del mouse.

```csharp
public class MouseEvent : UIEvent
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MouseEvent](mouseevent/#constructor)(string) | Inicializa una nueva instancia del`MouseEvent` clase. |
| [MouseEvent](mouseevent/#constructor_1)(string, IDictionary&lt;string, object&gt;) | Inicializa una nueva instancia del`MouseEvent` clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AltKey](../../aspose.html.dom.events/mouseevent/altkey/) { get; } | Consulte el atributo altKey. |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | Se utiliza para indicar si un evento es un evento burbujeante o no. Si el evento puede burbujear, el valor es verdadero; de lo contrario, el valor es falso. |
| [Button](../../aspose.html.dom.events/mouseevent/button/) { get; } | Durante los eventos del mouse causados por presionar o soltar un botón del mouse, el botón DEBE usarse para indicar qué botón del dispositivo de puntero cambió de estado. |
| [Buttons](../../aspose.html.dom.events/mouseevent/buttons/) { get; } | Durante cualquier evento del mouse, los botones DEBEN usarse para indicar qué combinación de botones del mouse se está presionando actualmente, expresada como una máscara de bits. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | Se utiliza para indicar si un evento puede o no tener su acción predeterminada prevenida. Si se puede evitar la acción predeterminada, el valor es verdadero; de lo contrario, el valor es falso. |
| [ClientX](../../aspose.html.dom.events/mouseevent/clientx/) { get; } | La coordenada horizontal en la que ocurrió el evento en relación con la ventana gráfica asociada con el evento. |
| [ClientY](../../aspose.html.dom.events/mouseevent/clienty/) { get; } | La coordenada vertical en la que ocurrió el evento en relación con la ventana gráfica asociada con el evento. |
| [CtrlKey](../../aspose.html.dom.events/mouseevent/ctrlkey/) { get; } | Consulte el atributo ctrlKey. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | Se utiliza para indicar el[`IEventTarget`](../ieventtarget/) cuyo[`IEventListener`](../ieventlistener/) los mensajes de correo electrónico se están procesando actualmente. Esto es especialmente útil durante la captura y el burbujeo. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | Devuelve verdadero si se invocó preventDefault() mientras el valor del atributo cancelable es verdadero y falso en caso contrario. |
| [Detail](../../aspose.html.dom.events/uievent/detail/) { get; } | Especifica información detallada sobre el evento, según el tipo de evento. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | Se utiliza para indicar qué fase del flujo de eventos se está evaluando actualmente. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | El atributo isTrusted debe devolver el valor con el que se inicializó. Cuando se crea un evento, el atributo debe inicializarse en false. |
| [MetaKey](../../aspose.html.dom.events/mouseevent/metakey/) { get; } | Consulte el atributo metaKey. |
| [RelatedTarget](../../aspose.html.dom.events/mouseevent/relatedtarget/) { get; } | Se utiliza para identificar un objetivo de evento secundario relacionado con un evento de interfaz de usuario, según el tipo de evento. |
| [ScreenX](../../aspose.html.dom.events/mouseevent/screenx/) { get; } | La coordenada horizontal en la que ocurrió el evento en relación con el origen del sistema de coordenadas de la pantalla. |
| [ScreenY](../../aspose.html.dom.events/mouseevent/screeny/) { get; } | La coordenada vertical en la que ocurrió el evento en relación con el origen del sistema de coordenadas de la pantalla. |
| [ShiftKey](../../aspose.html.dom.events/mouseevent/shiftkey/) { get; } | Consulte el atributo shiftKey. |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | Se utiliza para indicar el[`IEventTarget`](../ieventtarget/) al que se despachó originalmente el evento. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | Se utiliza para especificar la hora (en milisegundos con respecto a la época) en la que se creó el evento. Debido al hecho de que algunos sistemas pueden no proporcionar esta información, es posible que el valor de timeStamp no esté disponible para todos los eventos. Cuando no está disponible , se devolverá un valor de 0. Ejemplos de tiempo de época son el tiempo de inicio del sistema o 0:0:0 UTC del 1 de enero de 1970. |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | El nombre del evento (no distingue entre mayúsculas y minúsculas). El nombre debe ser un nombre XML. |
| [View](../../aspose.html.dom.events/uievent/view/) { get; } | El atributo de vista identifica la ventana desde la cual se generó el evento. El valor no inicializado de este atributo DEBE ser nulo. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Este método se utiliza para recuperar el objeto ECMAScriptType . |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | El[`InitEvent`](../event/initevent/) El método se utiliza para inicializar el valor de un[`Event`](../event/) creado a través de the [`IDocumentEvent`](../idocumentevent/) interfaz. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | Si un evento es cancelable, el[`PreventDefault`](../event/preventdefault/) El método se utiliza para indicar que el evento debe cancelarse, lo que significa que no se producirá ninguna acción predeterminada que normalmente toma la implementación como resultado del evento. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | La invocación de este método evita que el evento llegue a cualquier detector de eventos registrado después del actual y, cuando se distribuye en un árbol, también evita que el evento llegue a cualquier otro objeto. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | El[`StopPropagation`](../event/stoppropagation/) El método se utiliza para evitar la propagación adicional de un evento durante el flujo del evento. |

### Ver también

* class [UIEvent](../uievent/)
* espacio de nombres [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* asamblea [Aspose.HTML](../../)


