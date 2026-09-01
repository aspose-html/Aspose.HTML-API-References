---
title: "TimeEvent.InitTimeEvent"
second_title: "Aspose.HTML voor Java API-referentie"
description: "TimeEvent‑methode. De initTimeEvent‑methode wordt gebruikt om de waarde van een TimeEvent te initialiseren die via de DocumentEvent‑interface is aangemaakt. Deze methode mag alleen worden aangeroepen voordat de TimeEvent is verzonden via de dispatchEvent‑methode, hoewel hij indien nodig meerdere keren tijdens die fase kan worden aangeroepen. Als hij meerdere keren wordt aangeroepen, heeft de laatste aanroep voorrang."
type: docs

url: /nl/java/com.aspose.html.dom.svg.events/timeevent/inittimeevent/
---
## TimeEvent.InitTimeEvent method

De initTimeEvent‑methode wordt gebruikt om de waarde van een TimeEvent te initialiseren die via de DocumentEvent‑interface is gecreëerd. Deze methode mag alleen worden aangeroepen voordat de TimeEvent is verzonden via de dispatchEvent‑methode, hoewel hij tijdens die fase indien nodig meerdere keren kan worden aangeroepen. Als hij meerdere keren wordt aangeroepen, heeft de laatste aanroep voorrang.

```java
public void InitTimeEvent(String typeArg, IAbstractView viewArg, long detailArg)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| typeArg | String | Specificeert het type van het evenement. |
| viewArg | IAbstractView | Specificeert de AbstractView van het evenement. |
| detailArg | Int64 | Specificeert de detailinformatie van het evenement. |

### Zie ook

* interface [IAbstractView](../../../com.aspose.html.dom.views/iabstractview/)
* class [TimeEvent](../)
* package [com.aspose.html.dom.svg.events](../../../com.aspose.html.dom.svg.events/)
* package [Aspose.HTML](../../../)
