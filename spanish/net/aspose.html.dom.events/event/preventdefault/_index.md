---
title: Event.PreventDefault
second_title: Referencia de API de Aspose.HTML para .NET
description: Event método. Si un evento es cancelable elPreventDefault El método se utiliza para indicar que el evento debe cancelarse lo que significa que no se producirá ninguna acción predeterminada que normalmente toma la implementación como resultado del evento.
type: docs
weight: 120
url: /es/net/aspose.html.dom.events/event/preventdefault/
---
## Event.PreventDefault method

Si un evento es cancelable, el`PreventDefault` El método se utiliza para indicar que el evento debe cancelarse, lo que significa que no se producirá ninguna acción predeterminada que normalmente toma la implementación como resultado del evento.

```csharp
public void PreventDefault()
```

### Observaciones

Si, durante cualquier etapa del flujo de eventos, el`PreventDefault`se llama al método, el evento se cancela. No se producirá ninguna acción predeterminada asociada con el evento. Llamar a este método para un evento no cancelable no tiene ningún efecto. Una vez`PreventDefault` ha sido llamado, permanecerá en efecto durante el resto de la propagación del evento. Este método puede usarse durante cualquier etapa del flujo del evento.

### Ver también

* class [Event](../)
* espacio de nombres [Aspose.Html.Dom.Events](../../event/)
* asamblea [Aspose.HTML](../../../)


