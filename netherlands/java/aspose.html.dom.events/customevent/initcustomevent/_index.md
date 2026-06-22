---
title: "CustomEvent.InitCustomEvent"
second_title: "Aspose.HTML voor Java API-referentie"
description: "CustomEvent-methode. /// De InitEvent-methode wordt gebruikt om de waarde van een Event te initialiseren die is gemaakt via de IDocumentEvent-interface"
type: docs

url: /nl/java/com.aspose.html.dom.events/customevent/initcustomevent/
---
## CustomEvent.InitCustomEvent method

/// De [`InitEvent`](../../event/initevent/)‑methode wordt gebruikt om de waarde van een [`Event`](../../event/) te initialiseren die is gemaakt via de [`IDocumentEvent`](../../idocumentevent/)‑interface.

```java
public void InitCustomEvent(String type, bool bubbles, bool cancelable, object detail)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | String | Het type gebeurtenis. |
| bubbels | Boolean | indien ingesteld op `true` [bubbels]. |
| annuleerbaar | Boolean | indien ingesteld op `true` [annuleerbaar]. |
| detail | Object | De aangepaste gegevens. |

## Opmerkingen

Deze methode mag alleen worden aangeroepen voordat het Event is verzonden via de [`DispatchEvent`](../../ieventtarget/dispatchevent/)‑methode, hoewel hij tijdens die fase meerdere keren kan worden aangeroepen indien nodig. Als hij meerdere keren wordt aangeroepen, heeft de laatste aanroep voorrang. Als hij wordt aangeroepen vanuit een subklasse van de Event‑interface, worden alleen de waarden die in de initEvent‑methode zijn gespecificeerd gewijzigd; alle andere attributen blijven ongewijzigd.

### Zie ook

* class [CustomEvent](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
