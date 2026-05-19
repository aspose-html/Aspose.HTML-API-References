---
title: "Document.CreateEvent"
second_title: "Aspose.HTML voor Java API-referentie"
description: "Document‑methode. Maakt een Event van een type dat door de implementatie wordt ondersteund."
type: docs

url: /nl/java/com.aspose.html.dom/document/createevent/
---
## Document.CreateEvent method

Maakt een [`Event`](../../../com.aspose.html.dom.events/event/) van een type dat door de implementatie wordt ondersteund.

```java
public Event CreateEvent(String eventType)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eventType | String | De eventType‑parameter geeft het type van de [`Event`](../../../com.aspose.html.dom.events/event/)‑interface op die moet worden aangemaakt. Als de opgegeven [`Event`](../../../com.aspose.html.dom.events/event/)‑interface wordt ondersteund door de implementatie, zal deze methode een nieuw [`Event`](../../../com.aspose.html.dom.events/event/) van het gevraagde interfacetype retourneren. Als het [`Event`](../../../com.aspose.html.dom.events/event/) moet worden verzonden via de [`DispatchEvent`](../../../com.aspose.html.dom.events/ieventtarget/dispatchevent/)‑methode, moet de juiste [`InitEvent`](../../../com.aspose.html.dom.events/event/initevent/)‑methode na het aanmaken worden aangeroepen om de waarden van het [`Event`](../../../com.aspose.html.dom.events/event/) te initialiseren. |

### Retourwaarde

Het nieuw aangemaakte [`Event`](../../../com.aspose.html.dom.events/event/)

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [dOMException](../../domexception/) | NOT_SUPPORTED_ERR: Opgeworpen als de implementatie het gevraagde type van de [`Event`](../../../com.aspose.html.dom.events/event/) interface niet ondersteunt |

### Zie ook

* class [Event](../../../com.aspose.html.dom.events/event/)
* class [Document](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
