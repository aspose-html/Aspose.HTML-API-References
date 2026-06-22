---
title: "SVGSVGElement.CreateEvent"
second_title: "Aspose.HTML voor Java API-referentie"
description: "SVGSVGElement-methode. Maakt een Event van een type dat door de implementatie wordt ondersteund."
type: docs

url: /nl/java/com.aspose.html.dom.svg/svgsvgelement/createevent/
---
## SVGSVGElement.CreateEvent method

Maakt een [`Event`](../../../com.aspose.html.dom.events/event/) van een type dat door de implementatie wordt ondersteund.

```java
public Event CreateEvent(String eventType)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eventType | String | De eventType-parameter specificeert het type van de [`Event`](../../../com.aspose.html.dom.events/event/) interface die moet worden aangemaakt. Als de gespecificeerde [`Event`](../../../com.aspose.html.dom.events/event/) interface wordt ondersteund door de implementatie, zal deze methode een nieuwe[`Event`](../../../com.aspose.html.dom.events/event/) van het aangevraagde interface‑type retourneren. Als de [`Event`](../../../com.aspose.html.dom.events/event/) moet worden verzonden via de [`DispatchEvent`](../../../com.aspose.html.dom/eventtarget/dispatchevent/) methode, moet de juiste[`InitEvent`](../../../com.aspose.html.dom.events/event/initevent/) methode na creatie worden aangeroepen om de waarden van de [`Event`](../../../com.aspose.html.dom.events/event/) te initialiseren. |

### Retourwaarde

De nieuw aangemaakte [`Event`](../../../com.aspose.html.dom.events/event/)

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Opgetreden als de implementatie het aangevraagde type van de [`Event`](../../../com.aspose.html.dom.events/event/) interface niet ondersteunt |

### Zie ook

* class [Event](../../../com.aspose.html.dom.events/event/)
* class [SVGSVGElement](../)
* package [com.aspose.html.dom.svg](../../../com.aspose.html.dom.svg/)
* package [Aspose.HTML](../../../)
