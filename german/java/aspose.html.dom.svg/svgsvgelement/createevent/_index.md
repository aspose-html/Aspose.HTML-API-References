---
title: "SVGSVGElement.CreateEvent"
second_title: "Aspose.HTML für Java API-Referenz"
description: "SVGSVGElement‑Methode. Erstellt ein Event eines von der Implementierung unterstützten Typs."
type: docs

url: /de/java/com.aspose.html.dom.svg/svgsvgelement/createevent/
---
## SVGSVGElement.CreateEvent method

Erstellt ein [`Event`](../../../com.aspose.html.dom.events/event/) eines von der Implementierung unterstützten Typs.

```java
public Event CreateEvent(String eventType)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| eventType | String | Der eventType-Parameter gibt den Typ der [`Event`](../../../com.aspose.html.dom.events/event/) Schnittstelle an, die erstellt werden soll. Wenn die angegebene [`Event`](../../../com.aspose.html.dom.events/event/) Schnittstelle von der Implementierung unterstützt wird, gibt diese Methode ein neues [`Event`](../../../com.aspose.html.dom.events/event/) des angeforderten Schnittstellentyps zurück. Wenn das [`Event`](../../../com.aspose.html.dom.events/event/) über die [`DispatchEvent`](../../../com.aspose.html.dom/eventtarget/dispatchevent/) Methode ausgelöst werden soll, muss nach der Erstellung die entsprechende [`InitEvent`](../../../com.aspose.html.dom.events/event/initevent/) Methode aufgerufen werden, um die Werte des [`Event`](../../../com.aspose.html.dom.events/event/) zu initialisieren. |

### Rückgabewert

Das neu erstellte [`Event`](../../../com.aspose.html.dom.events/event/)

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Wird ausgelöst, wenn die Implementierung den angeforderten Typ der [`Event`](../../../com.aspose.html.dom.events/event/) Schnittstelle nicht unterstützt |

### Siehe auch

* class [Event](../../../com.aspose.html.dom.events/event/)
* class [SVGSVGElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
