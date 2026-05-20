---
title: "IDocumentEvent.CreateEvent"
second_title: "Aspose.HTML för Java API-referens"
description: "IDocumentEvent‑metod. Metoden createEvent används för att skapa Events när det är antingen opraktiskt eller onödigt för användaren att skapa ett Event själv."
type: docs

url: /sv/java/com.aspose.html.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

Metoden createEvent används för att skapa händelser när det är opraktiskt eller onödigt för användaren att skapa en händelse själv.

```java
public Event CreateEvent(String eventType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| eventType | String | eventType‑parametern specificerar vilken typ av gränssnitt som ska skapas. Om det angivna gränssnittet stöds av implementationen kommer denna metod att returnera ett nytt objekt av den begärda gränssnittstypen. Om den ska skickas via metoden måste lämplig metod anropas efter skapandet för att initiera värdena. Metoden används för att skapa s när det är antingen opraktiskt eller onödigt för användaren att skapa dem själv. I fall där den tillhandahållna implementationen är otillräcklig kan användare tillhandahålla egna implementationer för användning med metoden. |

### Returvärde

Returnerar det nyss skapade eventet av den angivna händelsetypen.

### Undantag

| undantag | villkor |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Uppstår om implementationen inte stödjer den begärda gränssnittstypen |

### Se även

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
