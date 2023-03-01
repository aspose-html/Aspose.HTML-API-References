---
title: Class EventTarget
second_title: Referencia de API de Aspose.HTML para .NET
description: Aspose.Html.Dom.EventTarget clase. ElEventTarget Todos los nodos implementan la interfaz en una implementación que admite el modelo de eventos DOM. Por lo tanto esta interfaz se puede obtener utilizando métodos de conversión específicos de vinculación en una instancia de la interfaz de nodo. La interfaz permite el registro y la eliminación de escuchas de eventos en unEventTarget y envío de eventos a eseIEventTarget .
type: docs
weight: 720
url: /es/net/aspose.html.dom/eventtarget/
---
## EventTarget class

El`EventTarget` Todos los nodos implementan la interfaz en una implementación que admite el modelo de eventos DOM. Por lo tanto, esta interfaz se puede obtener utilizando métodos de conversión específicos de vinculación en una instancia de la interfaz de nodo. La interfaz permite el registro y la eliminación de escuchas de eventos en un`EventTarget` y envío de eventos a ese[`IEventTarget`](../../aspose.html.dom.events/ieventtarget/) .

```csharp
public class EventTarget : DOMObject, IDisposable, IEventTarget
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_1)(string, IEventListener) | Este método permite el registro de detectores de eventos en el destino del evento. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/#addeventlistener)(string, DOMEventHandler, bool) | Este método permite el registro de detectores de eventos en el destino del evento. |
| [AddEventListener](../../aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_2)(string, IEventListener, bool) | Este método permite el registro de detectores de eventos en el destino del evento. |
| [DispatchEvent](../../aspose.html.dom/eventtarget/dispatchevent/)(Event) | Este método permite el envío de eventos al modelo de eventos de implementaciones. |
| [Dispose](../../aspose.html.dom/eventtarget/dispose/)() | Realiza tareas definidas por la aplicación asociadas con liberar, liberar o restablecer recursos no administrados. |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Este método se utiliza para recuperar el objeto ECMAScriptType . |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_1)(string, IEventListener) | Este método permite eliminar detectores de eventos del destino del evento. Si[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) se elimina de un`EventTarget` mientras está procesando un evento, no será activado por las acciones actuales. Los detectores de eventos nunca se pueden invocar después de eliminarlos. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener)(string, DOMEventHandler, bool) | Este método permite eliminar detectores de eventos del destino del evento. Si[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) se elimina de un`EventTarget` mientras está procesando un evento, no será activado por las acciones actuales. Los detectores de eventos nunca se pueden invocar después de eliminarlos. |
| [RemoveEventListener](../../aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_2)(string, IEventListener, bool) | Este método permite eliminar detectores de eventos del destino del evento. Si[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) se elimina de un`EventTarget` mientras está procesando un evento, no será activado por las acciones actuales. Los detectores de eventos nunca se pueden invocar después de eliminarlos. |

### Ver también

* class [DOMObject](../domobject/)
* interface [IEventTarget](../../aspose.html.dom.events/ieventtarget/)
* espacio de nombres [Aspose.Html.Dom](../../aspose.html.dom/)
* asamblea [Aspose.HTML](../../)


