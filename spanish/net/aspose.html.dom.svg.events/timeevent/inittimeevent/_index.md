---
title: TimeEvent.InitTimeEvent
second_title: Referencia de API de Aspose.HTML para .NET
description: TimeEvent método. El método initTimeEvent se utiliza para inicializar el valor de un TimeEvent creado a través de la interfaz DocumentEvent. Solo se puede llamar a este método antes de que TimeEvent se haya enviado a través del método dispatchEvent aunque se puede llamar varias veces durante esa fase si es necesario. Si se llama varias veces la invocación final tiene prioridad.
type: docs
weight: 30
url: /es/net/aspose.html.dom.svg.events/timeevent/inittimeevent/
---
## TimeEvent.InitTimeEvent method

El método initTimeEvent se utiliza para inicializar el valor de un TimeEvent creado a través de la interfaz DocumentEvent. Solo se puede llamar a este método antes de que TimeEvent se haya enviado a través del método dispatchEvent, aunque se puede llamar varias veces durante esa fase si es necesario. Si se llama varias veces, la invocación final tiene prioridad.

```csharp
public void InitTimeEvent(string typeArg, IAbstractView viewArg, long detailArg)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| typeArg | String | Especifica el tipo de evento. |
| viewArg | IAbstractView | Especifica el AbstractView del evento. |
| detailArg | Int64 | Especifica el detalle del evento. |

### Ver también

* interface [IAbstractView](../../../aspose.html.dom.views/iabstractview/)
* class [TimeEvent](../)
* espacio de nombres [Aspose.Html.Dom.Svg.Events](../../timeevent/)
* asamblea [Aspose.HTML](../../../)


