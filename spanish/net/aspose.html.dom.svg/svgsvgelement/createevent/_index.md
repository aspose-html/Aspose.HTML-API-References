---
title: SVGSVGElement.CreateEvent
second_title: Referencia de API de Aspose.HTML para .NET
description: SVGSVGElement método. Crea unEvent de un tipo soportado por la implementación.
type: docs
weight: 110
url: /es/net/aspose.html.dom.svg/svgsvgelement/createevent/
---
## SVGSVGElement.CreateEvent method

Crea un[`Event`](../../../aspose.html.dom.events/event/) de un tipo soportado por la implementación.

```csharp
public Event CreateEvent(string eventType)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| eventType | String | El parámetro eventType especifica el tipo de[`Event`](../../../aspose.html.dom.events/event/) interfaz a crear.  Si el[`Event`](../../../aspose.html.dom.events/event/)la interfaz especificada es compatible con la implementación, este método devolverá un new [`Event`](../../../aspose.html.dom.events/event/) del tipo de interfaz solicitado. Si el[`Event`](../../../aspose.html.dom.events/event/)debe ser enviado a través del[`DispatchEvent`](../../../aspose.html.dom/eventtarget/dispatchevent/) método el apropiado [`InitEvent`](../../../aspose.html.dom.events/event/initevent/) El método debe llamarse después de la creación para inicializar el[`Event`](../../../aspose.html.dom.events/event/) valores s. |

### Valor_devuelto

El recién creado[`Event`](../../../aspose.html.dom.events/event/)

### Excepciones

| excepción | condición |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: se genera si la implementación no admite el tipo de[`Event`](../../../aspose.html.dom.events/event/) interfaz solicitada |

### Ver también

* class [Event](../../../aspose.html.dom.events/event/)
* class [SVGSVGElement](../)
* espacio de nombres [Aspose.Html.Dom.Svg](../../svgsvgelement/)
* asamblea [Aspose.HTML](../../../)


