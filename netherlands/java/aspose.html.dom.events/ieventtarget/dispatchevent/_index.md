---
title: "IEventTarget.DispatchEvent"
second_title: "Aspose.HTML voor Java API-referentie"
description: "IEventTarget‑methode. Verstuurd een Event naar het opgegeven EventTarget en roept synchrone de betrokken EventListeners aan in de juiste volgorde. De normale regels voor gebeurtenisverwerking, inclusief de capture‑ en optionele bubbling‑fase, zijn ook van toepassing op events die handmatig met dispatchEvent worden verstuurd."
type: docs

url: /nl/java/com.aspose.html.dom.events/ieventtarget/dispatchevent/
---
## IEventTarget.DispatchEvent method

Verzendt een Event naar het opgegeven EventTarget (synchroon) en roept de betrokken EventListeners in de juiste volgorde aan. De normale event‑verwerkingsregels (inclusief de capture‑ en optionele bubbling‑fase) zijn ook van toepassing op events die handmatig worden verzonden met dispatchEvent().

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
| [dOMException](../../../com.aspose.html.dom/domexception/) | Exceptions die door event‑handlers worden gegooid, worden gerapporteerd als niet‑afgevangen exceptions. De event‑handlers draaien op een geneste call‑stack; ze blokkeren de aanroeper totdat ze voltooid zijn, maar exceptions worden niet doorgegeven aan de aanroeper. |

## Opmerkingen

Events die op deze manier worden verzonden, hebben hetzelfde capture‑ en bubbling‑gedrag als events die rechtstreeks door de implementatie worden verzonden. Het doelwit van het event is de op die wordt aangeroepen.

### Zie ook

* class [Event](../../event/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
