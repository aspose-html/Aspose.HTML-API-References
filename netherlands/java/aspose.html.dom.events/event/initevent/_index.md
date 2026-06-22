---
title: "Event.InitEvent"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Event-methode. De InitEvent-methode wordt gebruikt om de waarde van een Event te initialiseren dat via de IDocumentEvent-interface is gemaakt."
type: docs

url: /nl/java/com.aspose.html.dom.events/event/initevent/
---
## Event.InitEvent method

De `InitEvent`-methode wordt gebruikt om de waarde van een [`Event`](../) te initialiseren die via de[`IDocumentEvent`](../../idocumentevent/) interface is gemaakt.

```java
public void InitEvent(String type, bool bubbles, bool cancelable)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | String | Het type gebeurtenis. |
| bubbels | Boolean | indien ingesteld op `true` [bubbels]. |
| annuleerbaar | Boolean | indien ingesteld op `true` [annuleerbaar]. |

## Opmerkingen

Deze methode mag alleen worden aangeroepen voordat het Event is verzonden via de [`DispatchEvent`](../../ieventtarget/dispatchevent/)‑methode, hoewel hij tijdens die fase meerdere keren kan worden aangeroepen indien nodig. Als hij meerdere keren wordt aangeroepen, heeft de laatste aanroep voorrang. Als hij wordt aangeroepen vanuit een subklasse van de Event‑interface, worden alleen de waarden die in de initEvent‑methode zijn gespecificeerd gewijzigd; alle andere attributen blijven ongewijzigd.

### Zie ook

* class [Event](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
