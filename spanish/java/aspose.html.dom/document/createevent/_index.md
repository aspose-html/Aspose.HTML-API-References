---
title: "Document.CreateEvent"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método Document. Crea un Event de un tipo compatible con la implementación."
type: docs

url: /es/java/com.aspose.html.dom/document/createevent/
---
## Document.CreateEvent method

Crea un [`Event`](../../../com.aspose.html.dom.events/event/) de un tipo compatible con la implementación.

```java
public Event CreateEvent(String eventType)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| eventType | String | El parámetro eventType especifica el tipo de interfaz [`Event`](../../../com.aspose.html.dom.events/event/) que se debe crear. Si la interfaz [`Event`](../../../com.aspose.html.dom.events/event/) especificada es compatible con la implementación, este método devolverá un nuevo [`Event`](../../../com.aspose.html.dom.events/event/) del tipo de interfaz solicitado. Si el [`Event`](../../../com.aspose.html.dom.events/event/) se va a despachar mediante el método [`DispatchEvent`](../../../com.aspose.html.dom.events/ieventtarget/dispatchevent/), debe llamarse después de la creación el método [`InitEvent`](../../../com.aspose.html.dom.events/event/initevent/) correspondiente para inicializar los valores del [`Event`](../../../com.aspose.html.dom.events/event/). |

### Valor de retorno

El [`Event`](../../../com.aspose.html.dom.events/event/) recién creado

### Excepciones

| excepción | condición |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Se genera si la implementación no admite el tipo de interfaz [`Event`](../../../com.aspose.html.dom.events/event/) solicitado |

### Ver también

* class [Event](../../../com.aspose.html.dom.events/event/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
