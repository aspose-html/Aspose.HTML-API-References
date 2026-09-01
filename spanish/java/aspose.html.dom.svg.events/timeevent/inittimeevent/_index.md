---
title: "TimeEvent.InitTimeEvent"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método TimeEvent. El método initTimeEvent se usa para inicializar el valor de un TimeEvent creado a través de la interfaz DocumentEvent. Este método solo puede llamarse antes de que el TimeEvent haya sido despachado mediante el método dispatchEvent, aunque puede llamarse varias veces durante esa fase si es necesario. Si se llama varias veces, la invocación final tiene precedencia"
type: docs

url: /es/java/com.aspose.html.dom.svg.events/timeevent/inittimeevent/
---
## TimeEvent.InitTimeEvent method

El método initTimeEvent se usa para inicializar el valor de un TimeEvent creado a través de la interfaz DocumentEvent. Este método solo puede llamarse antes de que el TimeEvent haya sido despachado mediante el método dispatchEvent, aunque puede llamarse varias veces durante esa fase si es necesario. Si se llama varias veces, la invocación final tiene precedencia.

```java
public void InitTimeEvent(String typeArg, IAbstractView viewArg, long detailArg)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| typeArg | Cadena | Especifica el tipo de evento. |
| viewArg | IAbstractView | Especifica la AbstractView del Evento. |
| detailArg | Int64 | Especifica el detalle del Evento. |

### Ver también

* interface [IAbstractView](../../../com.aspose.html.dom.views/iabstractview/)
* class [TimeEvent](../)
* package [com.aspose.html.dom.svg.events](../../../com.aspose.html.dom.svg.events/)
* package [Aspose.HTML](../../../)
