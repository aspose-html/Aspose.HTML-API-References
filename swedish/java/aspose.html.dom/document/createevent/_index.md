---
title: "Document.CreateEvent"
second_title: "Aspose.HTML för Java API-referens"
description: "Document‑metod. Skapar ett Event av en typ som stöds av implementationen."
type: docs

url: /sv/java/com.aspose.html.dom/document/createevent/
---
## Document.CreateEvent method

Skapar en [`Event`](../../../com.aspose.html.dom.events/event/) av en typ som stöds av implementationen.

```java
public Event CreateEvent(String eventType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| eventType | String | Parametern eventType specificerar vilken typ av [`Event`](../../../com.aspose.html.dom.events/event/)‑gränssnitt som ska skapas. Om det angivna [`Event`](../../../com.aspose.html.dom.events/event/)‑gränssnittet stöds av implementationen kommer denna metod att returnera ett nytt [`Event`](../../../com.aspose.html.dom.events/event/) av den begärda gränssnittstypen. Om [`Event`](../../../com.aspose.html.dom.events/event/) ska distribueras via [`DispatchEvent`](../../../com.aspose.html.dom.events/ieventtarget/dispatchevent/)‑metoden måste den lämpliga [`InitEvent`](../../../com.aspose.html.dom.events/event/initevent/)‑metoden anropas efter skapandet för att initiera värdena för [`Event`](../../../com.aspose.html.dom.events/event/). |

### Returvärde

Det nyss skapade [`Event`](../../../com.aspose.html.dom.events/event/)

### Undantag

| undantag | villkor |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Uppstår om implementationen inte stöder den begärda typen av [`Event`](../../../com.aspose.html.dom.events/event/)‑gränssnitt |

### Se även

* class [Event](../../../com.aspose.html.dom.events/event/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
