---
title: InputEvent
second_title: Referencia de API de Aspose.HTML para .NET
description: Los eventos de entrada se envían como notificaciones cada vez que se actualiza el DOM.
type: docs
weight: 830
url: /es/net/aspose.html.dom.events/inputevent/
---
## InputEvent class

Los eventos de entrada se envían como notificaciones cada vez que se actualiza el DOM.

```csharp
public class InputEvent : UIEvent
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [InputEvent](inputevent#constructor)(string) | Inicializa una nueva instancia del[`InputEvent`](../inputevent) clase. |
| [InputEvent](inputevent#constructor_1)(string, IDictionary&lt;string, object&gt;) | Inicializa una nueva instancia del[`InputEvent`](../inputevent) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles) { get; } | Se utiliza para indicar si un evento es un evento burbujeante o no. Si el evento puede burbujear, el valor es verdadero; de lo contrario, el valor es falso. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable) { get; } | Se utiliza para indicar si un evento puede o no tener su acción predeterminada prevenida. Si se puede evitar la acción predeterminada, el valor es verdadero; de lo contrario, el valor es falso. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget) { get; } | Se utiliza para indicar el[`IEventTarget`](../ieventtarget) cuyo[`IEventListener`](../ieventlistener) los mensajes de correo electrónico se están procesando actualmente. Esto es especialmente útil durante la captura y el burbujeo. |
| [Data](../../aspose.html.dom.events/inputevent/data) { get; } | Los datos contienen el valor de los caracteres generados por un método de entrada. Este PUEDE ser un solo carácter Unicode o una secuencia no vacía de caracteres Unicode [Unicode]. Los caracteres DEBERÍAN normalizarse según lo definido por el formulario de normalización Unicode NFC, definido en [UAX15]. Este atributo PUEDE contener la cadena vacía. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented) { get; } | Devuelve verdadero si se invocó preventDefault() mientras el valor del atributo cancelable es verdadero y falso en caso contrario. |
| [Detail](../../aspose.html.dom.events/uievent/detail) { get; } | Especifica información detallada sobre el evento, según el tipo de evento. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase) { get; } | Se utiliza para indicar qué fase del flujo de eventos se está evaluando actualmente. |
| [IsComposing](../../aspose.html.dom.events/inputevent/iscomposing) { get; } | verdadero si el evento de entrada ocurre como parte de una sesión de composición, es decir, después de un evento de inicio de composición y antes del evento de fin de composición correspondiente. El valor no inicializado de este atributo DEBE ser falso. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted) { get; } | El atributo isTrusted debe devolver el valor con el que se inicializó. Cuando se crea un evento, el atributo debe inicializarse en false. |
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

### Ver también

* class [UIEvent](../uievent)
* espacio de nombres [Aspose.Html.Dom.Events](../../aspose.html.dom.events)
* asamblea [Aspose.HTML](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
