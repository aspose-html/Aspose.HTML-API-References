---
title: Class SVGZoomEvent
second_title: Referencia de API de Aspose.HTML para .NET
description: Aspose.Html.Dom.Svg.Events.SVGZoomEvent clase. El evento de zoom ocurre cuando el usuario inicia una acción que hace que la vista actual del fragmento del documento SVG se reescale. Los controladores de eventos solo se reconocen en elementos svg.
type: docs
weight: 1330
url: /es/net/aspose.html.dom.svg.events/svgzoomevent/
---
## SVGZoomEvent class

El evento de zoom ocurre cuando el usuario inicia una acción que hace que la vista actual del fragmento del documento SVG se reescale. Los controladores de eventos solo se reconocen en elementos 'svg'.

```csharp
public class SVGZoomEvent : Event
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | Se utiliza para indicar si un evento es un evento burbujeante o no. Si el evento puede burbujear, el valor es verdadero; de lo contrario, el valor es falso. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | Se utiliza para indicar si un evento puede o no tener su acción predeterminada prevenida. Si se puede evitar la acción predeterminada, el valor es verdadero; de lo contrario, el valor es falso. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | Se utiliza para indicar el[`IEventTarget`](../../aspose.html.dom.events/ieventtarget/) cuyo[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) los mensajes de correo electrónico se están procesando actualmente. Esto es especialmente útil durante la captura y el burbujeo. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | Devuelve verdadero si se invocó preventDefault() mientras el valor del atributo cancelable es verdadero y falso en caso contrario. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | Se utiliza para indicar qué fase del flujo de eventos se está evaluando actualmente. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | El atributo isTrusted debe devolver el valor con el que se inicializó. Cuando se crea un evento, el atributo debe inicializarse en false. |
| [NewScale](../../aspose.html.dom.svg.events/svgzoomevent/newscale/) { get; } | El factor de escala que estará en su lugar después de que se haya procesado la operación de zoom. |
| [NewTranslate](../../aspose.html.dom.svg.events/svgzoomevent/newtranslate/) { get; } | Los valores de traducción que estarán en su lugar después de que se haya procesado la operación de zoom. El objeto SVGPoint es de solo lectura. |
| [PreviousScale](../../aspose.html.dom.svg.events/svgzoomevent/previousscale/) { get; } | El factor de escala de las operaciones de zoom anteriores que estaba en su lugar antes de que ocurriera la operación de zoom. |
| [PreviousTranslate](../../aspose.html.dom.svg.events/svgzoomevent/previoustranslate/) { get; } | Los valores de traducción de las operaciones de zoom anteriores que estaban en su lugar antes de que ocurriera la operación de zoom. El objeto SVGPoint es de solo lectura. |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | Se utiliza para indicar el[`IEventTarget`](../../aspose.html.dom.events/ieventtarget/) al que se despachó originalmente el evento. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | Se utiliza para especificar la hora (en milisegundos con respecto a la época) en la que se creó el evento. Debido al hecho de que algunos sistemas pueden no proporcionar esta información, es posible que el valor de timeStamp no esté disponible para todos los eventos. Cuando no está disponible , se devolverá un valor de 0. Ejemplos de tiempo de época son el tiempo de inicio del sistema o 0:0:0 UTC del 1 de enero de 1970. |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | El nombre del evento (no distingue entre mayúsculas y minúsculas). El nombre debe ser un nombre XML. |
| [ZoomRectScreen](../../aspose.html.dom.svg.events/svgzoomevent/zoomrectscreen/) { get; } | El rectángulo de zoom especificado en unidades de pantalla. El objeto SVGRect es de solo lectura. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Este método se utiliza para recuperar el objeto ECMAScriptType . |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | El[`InitEvent`](../../aspose.html.dom.events/event/initevent/) El método se utiliza para inicializar el valor de un[`Event`](../../aspose.html.dom.events/event/) creado a través de the [`IDocumentEvent`](../../aspose.html.dom.events/idocumentevent/) interfaz. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | Si un evento es cancelable, el[`PreventDefault`](../../aspose.html.dom.events/event/preventdefault/) El método se utiliza para indicar que el evento debe cancelarse, lo que significa que no se producirá ninguna acción predeterminada que normalmente toma la implementación como resultado del evento. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | La invocación de este método evita que el evento llegue a cualquier detector de eventos registrado después del actual y, cuando se distribuye en un árbol, también evita que el evento llegue a cualquier otro objeto. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | El[`StopPropagation`](../../aspose.html.dom.events/event/stoppropagation/) El método se utiliza para evitar la propagación adicional de un evento durante el flujo del evento. |

### Ver también

* class [Event](../../aspose.html.dom.events/event/)
* espacio de nombres [Aspose.Html.Dom.Svg.Events](../../aspose.html.dom.svg.events/)
* asamblea [Aspose.HTML](../../)


