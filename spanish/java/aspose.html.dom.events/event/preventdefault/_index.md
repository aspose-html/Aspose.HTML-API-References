---
title: "Event.PreventDefault"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método del evento. Si un evento es cancelable, el método PreventDefault se utiliza para indicar que el evento debe cancelarse, lo que significa que cualquier acción predeterminada que normalmente realiza la implementación como resultado del evento no ocurrirá."
type: docs

url: /es/java/com.aspose.html.dom.events/event/preventdefault/
---
## Event.PreventDefault method

Si un evento es cancelable, el método `PreventDefault` se utiliza para indicar que el evento debe cancelarse, lo que significa que cualquier acción predeterminada que normalmente realiza la implementación como resultado del evento no ocurrirá.

```java
public void PreventDefault()
```

## Observaciones

Si, durante cualquier etapa del flujo de eventos, se llama al método `PreventDefault`, el evento se cancela. Cualquier acción predeterminada asociada al evento no ocurrirá. Llamar a este método para un evento no cancelable no tiene efecto. Una vez que se ha llamado a `PreventDefault`, permanecerá en vigor durante el resto de la propagación del evento. Este método puede usarse en cualquier etapa del flujo de eventos.

### Ver también

* class [Event](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
