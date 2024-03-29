---
title: Interface IEventTarget
second_title: Referencia de API de Aspose.HTML para .NET
description: Aspose.Html.Dom.Events.IEventTarget interfaz. ElEventTarget Todos los nodos implementan la interfaz en una implementación que admite el modelo de eventos DOM. Por lo tanto esta interfaz se puede obtener utilizando métodos de conversión específicos de vinculación en una instancia de la interfaz de nodo. La interfaz permite el registro y la eliminación de escuchas de eventos en unEventTarget y envío de eventos a eseIEventTarget .
type: docs
weight: 810
url: /es/net/aspose.html.dom.events/ieventtarget/
---
## IEventTarget interface

El[`EventTarget`](../../aspose.html.dom/eventtarget/) Todos los nodos implementan la interfaz en una implementación que admite el modelo de eventos DOM. Por lo tanto, esta interfaz se puede obtener utilizando métodos de conversión específicos de vinculación en una instancia de la interfaz de nodo. La interfaz permite el registro y la eliminación de escuchas de eventos en un[`EventTarget`](../../aspose.html.dom/eventtarget/) y envío de eventos a ese`IEventTarget` .

```csharp
public interface IEventTarget
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddEventListener](../../aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener)(string, IEventListener) | Este método permite el registro de detectores de eventos en el destino del evento. |
| [AddEventListener](../../aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(string, IEventListener, bool) | Este método permite el registro de detectores de eventos en el destino del evento. |
| [DispatchEvent](../../aspose.html.dom.events/ieventtarget/dispatchevent/)(Event) | Este método permite el envío de eventos al modelo de eventos de implementaciones. |
| [RemoveEventListener](../../aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(string, IEventListener) | Este método permite eliminar detectores de eventos del destino del evento. Si[`IEventListener`](../ieventlistener/) se elimina de un[`EventTarget`](../../aspose.html.dom/eventtarget/) mientras está procesando un evento, no será activado por las acciones actuales. Los detectores de eventos nunca se pueden invocar después de eliminarlos. |
| [RemoveEventListener](../../aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(string, IEventListener, bool) | Este método permite eliminar detectores de eventos del destino del evento. Si[`IEventListener`](../ieventlistener/) se elimina de un[`EventTarget`](../../aspose.html.dom/eventtarget/) mientras está procesando un evento, no será activado por las acciones actuales. Los detectores de eventos nunca se pueden invocar después de eliminarlos. |

### Ver también

* espacio de nombres [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* asamblea [Aspose.HTML](../../)


