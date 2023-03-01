---
title: Event.InitEvent
second_title: Referencia de API de Aspose.HTML para .NET
description: Event método. ElInitEvent El método se utiliza para inicializar el valor de unEvent creado a través de the IDocumentEvent interfaz.
type: docs
weight: 110
url: /es/net/aspose.html.dom.events/event/initevent/
---
## Event.InitEvent method

El`InitEvent` El método se utiliza para inicializar el valor de un[`Event`](../) creado a través de the [`IDocumentEvent`](../../idocumentevent/) interfaz.

```csharp
public void InitEvent(string type, bool bubbles, bool cancelable)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| type | String | El tipo de evento. |
| bubbles | Boolean | si se establece en`verdadero` [burbujas]. |
| cancelable | Boolean | si se establece en`verdadero` [cancelable]. |

### Observaciones

Este método solo puede llamarse antes de que el Evento haya sido enviado a través del[`DispatchEvent`](../../ieventtarget/dispatchevent/) método, aunque se puede llamar varias veces durante esa fase si es necesario. Si se llama varias veces, la invocación final tiene prioridad. Si se llama desde una subclase de la interfaz de eventos, solo se modifican los valores especificados en el método initEvent, todos los demás atributos se dejan sin cambios.

### Ver también

* class [Event](../)
* espacio de nombres [Aspose.Html.Dom.Events](../../event/)
* asamblea [Aspose.HTML](../../../)


