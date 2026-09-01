---
title: "SVGSVGElement.CreateEvent"
second_title: "Referencia de la API de Aspose.HTML para Java"
description: "Método SVGSVGElement. Crea un Event de un tipo compatible con la implementación."
type: docs

url: /es/java/com.aspose.html.dom.svg/svgsvgelement/createevent/
---
## SVGSVGElement.CreateEvent method

Crea un [`Event`](../../../com.aspose.html.dom.events/event/) de un tipo compatible con la implementación.

```java
public Event CreateEvent(String eventType)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| eventType | String | El parámetro eventType especifica el tipo de interfaz [`Event`](../../../com.aspose.html.dom.events/event/) que se debe crear. Si la interfaz [`Event`](../../../com.aspose.html.dom.events/event/) especificada es compatible con la implementación, este método devolverá un nuevo[`Event`](../../../com.aspose.html.dom.events/event/) del tipo de interfaz solicitado. Si el [`Event`](../../../com.aspose.html.dom.events/event/) debe enviarse mediante el método [`DispatchEvent`](../../../com.aspose.html.dom/eventtarget/dispatchevent/) se debe llamar al método[`InitEvent`](../../../com.aspose.html.dom.events/event/initevent/) apropiado después de la creación para inicializar los valores del [`Event`](../../../com.aspose.html.dom.events/event/). |

### Valor devuelto

El [`Event`](../../../com.aspose.html.dom.events/event/) recién creado

### Excepciones

| excepción | condición |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Se genera si la implementación no admite el tipo de interfaz [`Event`](../../../com.aspose.html.dom.events/event/) solicitado |

### Ver también

* class [Event](../../../com.aspose.html.dom.events/event/)
* class [SVGSVGElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
