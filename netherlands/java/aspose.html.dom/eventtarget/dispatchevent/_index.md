---
title: "EventTarget.DispatchEvent"
second_title: "Aspose.HTML voor Java API-referentie"
description: "EventTarget‑methode. Verstuurd een gebeurtenis naar het opgegeven EventTarget en roept synchronisch de betrokken EventListeners aan in de juiste volgorde. De normale regels voor gebeurtenisverwerking, inclusief de capture‑ en optionele bubbling‑fase, zijn ook van toepassing op handmatig met dispatchEvent verzonden gebeurtenissen."
type: docs

url: /nl/java/com.aspose.html.dom/eventtarget/dispatchevent/
---
## EventTarget.DispatchEvent method

Verstuurt een gebeurtenis naar het opgegeven [`EventTarget`](../../../com.aspose.html.dom.events/ieventtarget/), (synchronisch) en roept de betrokken EventListeners in de juiste volgorde aan. De normale regels voor gebeurtenisverwerking (inclusief de capture‑ en optionele bubbling‑fase) zijn ook van toepassing op handmatig met [`dispatchEvent()`](../../../com.aspose.html.dom.events/ieventtarget/dispatchevent/) verzonden gebeurtenissen.

```java
public bool DispatchEvent(Event @event)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| event | Event | Specificeert het type gebeurtenis, het gedrag en de contextuele informatie die gebruikt moet worden bij het verwerken van de gebeurtenis. |

### Retourwaarde

De retourwaarde van geeft aan of een van de listeners die de gebeurtenis hebben afgehandeld, is aangeroepen. Als is aangeroepen, is de waarde false, anders is de waarde true.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [dOMException](../../domexception/) |  |

## Opmerkingen

Op deze manier verzonden events hebben hetzelfde capture‑ en bubbling‑gedrag als events die rechtstreeks door de implementatie worden verzonden. Het doelwit van het event is de op welke wordt aangeroepen.

### Zie ook

* class [Event](../../../com.aspose.html.dom.events/event/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
