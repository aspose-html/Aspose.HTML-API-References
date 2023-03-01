---
title: Interface IEventListener
second_title: Referencia de API de Aspose.HTML para .NET
description: Aspose.Html.Dom.Events.IEventListener interfaz. ElIEventListenerinterfaz es el método principal para manejar eventos. Los usuarios implementan elIEventListener interfaz y registrar a su oyente en unEventTarget utilizando elAddEventListener method. Los usuarios también deben eliminar suIEventListener de suEventTarget después de que hayan completado el uso de listener.
type: docs
weight: 800
url: /es/net/aspose.html.dom.events/ieventlistener/
---
## IEventListener interface

El`IEventListener`interfaz es el método principal para manejar eventos. Los usuarios implementan el`IEventListener` interfaz y registrar a su oyente en un[`EventTarget`](../../aspose.html.dom/eventtarget/) utilizando el[`AddEventListener`](../../aspose.html.dom/eventtarget/addeventlistener/) method. Los usuarios también deben eliminar su`IEventListener` de su[`EventTarget`](../../aspose.html.dom/eventtarget/) después de que hayan completado el uso de listener.

```csharp
public interface IEventListener
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| [HandleEvent](../../aspose.html.dom.events/ieventlistener/handleevent/)(Event) | Este método se llama cada vez que ocurre un evento del tipo para el cual el`IEventListener` la interfaz fue registrada. |

### Observaciones

Cuando se copia un nodo con el método cloneNode, los detectores de eventos adjuntos al nodo de origen no se adjuntan al nodo copiado. Si el usuario desea que se agreguen los mismos detectores de eventos a la copia recién creada, debe agregarlos manualmente.

### Ver también

* espacio de nombres [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* asamblea [Aspose.HTML](../../)


