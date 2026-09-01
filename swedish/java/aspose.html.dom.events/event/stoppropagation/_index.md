---
title: "Event.StopPropagation"
second_title: "Aspose.HTML för Java API-referens"
description: "Event‑metod. StopPropagation‑metoden används för att förhindra vidare spridning av ett event under händelseflödet."
type: docs

url: /sv/java/com.aspose.html.dom.events/event/stoppropagation/
---
## Event.StopPropagation method

`StopPropagation`‑metoden används för att förhindra vidare spridning av ett event under händelseflödet.

```java
public void StopPropagation()
```

## Anmärkningar

Om denna metod anropas av någon [`IEventListener`](../../ieventlistener/) kommer eventet att sluta spridas genom trädet. Eventet kommer att slutföra utskick till alla lyssnare på det aktuella [`IEventTarget`](../../ieventtarget/) innan händelseflödet stoppas. Denna metod kan användas under vilken fas som helst av händelseflödet.

### Se även

* class [Event](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
