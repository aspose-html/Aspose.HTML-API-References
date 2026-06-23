---
title: "SVGSVGElement.CreateEvent"
second_title: "Aspose.HTML för Java API-referens"
description: "SVGSVGElement‑metod. Skapar en Event av en typ som stöds av implementationen."
type: docs

url: /sv/java/com.aspose.html.dom.svg/svgsvgelement/createevent/
---
## SVGSVGElement.CreateEvent method

Skapar en [`Event`](../../../com.aspose.html.dom.events/event/) av en typ som stöds av implementationen.

```java
public Event CreateEvent(String eventType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| eventType | String | The eventType‑parametern anger vilken typ av [`Event`](../../../com.aspose.html.dom.events/event/)‑gränssnitt som ska skapas. Om det angivna [`Event`](../../../com.aspose.html.dom.events/event/)‑gränssnittet stöds av implementationen kommer den här metoden att returnera ett nytt[`Event`](../../../com.aspose.html.dom.events/event/) av den begärda gränssnittstypen. Om [`Event`](../../../com.aspose.html.dom.events/event/) ska skickas via metoden [`DispatchEvent`](../../../com.aspose.html.dom/eventtarget/dispatchevent/) måste den lämpliga[`InitEvent`](../../../com.aspose.html.dom.events/event/initevent/)‑metoden anropas efter skapandet för att initiera [`Event`](../../../com.aspose.html.dom.events/event/)'s värden. |

### Returvärde

Det nyss skapade [`Event`](../../../com.aspose.html.dom.events/event/)

### Undantag

| undantag | villkor |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Uppstår om implementationen inte stöder den begärda typen av [`Event`](../../../com.aspose.html.dom.events/event/)‑gränssnitt |

### Se även

* class [Event](../../../com.aspose.html.dom.events/event/)
* class [SVGSVGElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
