---
title: "EventTarget.DispatchEvent"
second_title: "Aspose.HTML voor Java API-referentie"
description: "EventTarget-methode. Verstuurd een Event naar de opgegeven EventTarget synchronisch en roept de betrokken EventListeners in de juiste volgorde aan. De normale regels voor gebeurtenisverwerking, inclusief de capture- en optionele bubbling-fase, zijn ook van toepassing op events die handmatig worden verzonden met dispatchEvent"
type: docs

url: /nl/java/com.aspose.html.dom/eventtarget/dispatchevent/
---
## EventTarget.DispatchEvent method

Verstuurt een Event naar de opgegeven [`EventTarget`](../../../com.aspose.html.dom.events/ieventtarget/), (synchronisch) en roept de betrokken EventListeners in de juiste volgorde aan. De normale regels voor gebeurtenisverwerking (inclusief de capture- en optionele bubbling-fase) zijn ook van toepassing op events die handmatig worden verzonden met [`dispatchEvent()`](../../../com.aspose.html.dom.events/ieventtarget/dispatchevent/).

```java
public bool DispatchEvent(Event @event)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| gebeurtenis | Gebeurtenis | Specificeert het type event, het gedrag en de contextuele informatie die gebruikt moeten worden bij het verwerken van het event. |

### Retourwaarde

De retourwaarde van geeft aan of een van de listeners die het event hebben afgehandeld, is aangeroepen. Als is aangeroepen, is de waarde false, anders is de waarde true.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [dOMException](../../domexception/) |  |

## Opmerkingen

Events die op deze manier worden verzonden, hebben hetzelfde capture‑ en bubbling‑gedrag als events die rechtstreeks door de implementatie worden verzonden. Het doelwit van het event is de op die wordt aangeroepen.

### Zie ook

* class [Event](../../../com.aspose.html.dom.events/event/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
