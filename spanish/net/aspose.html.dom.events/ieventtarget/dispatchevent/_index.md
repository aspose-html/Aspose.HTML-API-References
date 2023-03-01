---
title: IEventTarget.DispatchEvent
second_title: Referencia de API de Aspose.HTML para .NET
description: IEventTarget método. Este método permite el envío de eventos al modelo de eventos de implementaciones.
type: docs
weight: 20
url: /es/net/aspose.html.dom.events/ieventtarget/dispatchevent/
---
## IEventTarget.DispatchEvent method

Este método permite el envío de eventos al modelo de eventos de implementaciones.

```csharp
public bool DispatchEvent(Event @event)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| event | Event | Especifica el tipo de evento, el comportamiento y la información contextual que se utilizará para procesar el evento. |

### Valor_devuelto

El valor de retorno de[`DispatchEvent`](../../../aspose.html.dom/eventtarget/dispatchevent/) indica si alguno de los oyentes que manejaron el evento llamado[`PreventDefault`](../../event/preventdefault/) . Si[`PreventDefault`](../../event/preventdefault/) fue llamado el valor es falso, de lo contrario el valor es verdadero.

### Excepciones

| excepción | condición |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) |  |

### Observaciones

Los eventos enviados de esta manera tendrán el mismo comportamiento de captura y burbujeo que los eventos enviados directamente por la implementación. El destino del evento es el[`EventTarget`](../../../aspose.html.dom/eventtarget/) en la que[`DispatchEvent`](../../../aspose.html.dom/eventtarget/dispatchevent/) se llama.

### Ver también

* class [Event](../../event/)
* interface [IEventTarget](../)
* espacio de nombres [Aspose.Html.Dom.Events](../../ieventtarget/)
* asamblea [Aspose.HTML](../../../)


