---
title: "IEventTarget.DispatchEvent"
second_title: "Aspose.HTML voor Java API-referentie"
description: "IEventTarget‑methode. Verstuurd een Event naar de opgegeven EventTarget synchronisch en roept de betrokken EventListeners in de juiste volgorde aan. De normale regels voor gebeurtenisverwerking, inclusief de capture‑ en optionele bubbling‑fase, zijn ook van toepassing op events die handmatig worden verstuurd met dispatchEvent."
type: docs

url: /nl/java/com.aspose.html.dom.events/ieventtarget/dispatchevent/
---
## IEventTarget.DispatchEvent method

Verzendt een Event naar de opgegeven EventTarget, (synchroon) waarbij de betrokken EventListeners in de juiste volgorde worden aangeroepen. De normale event‑verwerkingsregels (inclusief de capture‑ en optionele bubbling‑fase) zijn ook van toepassing op events die handmatig worden verzonden met dispatchEvent().

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
| [dOMException](../../../com.aspose.html.dom/domexception/) | Door event‑handlers gegooide uitzonderingen worden gerapporteerd als niet‑afgevangen uitzonderingen. De event‑handlers draaien op een geneste call‑stack; ze blokkeren de aanroeper totdat ze voltooid zijn, maar uitzonderingen worden niet naar de aanroeper doorgegeven. |

## Opmerkingen

Op deze manier verzonden events hebben hetzelfde capture‑ en bubbling‑gedrag als events die rechtstreeks door de implementatie worden verzonden. Het doelwit van het event is de op welke wordt aangeroepen.

### Zie ook

* class [Event](../../event/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
