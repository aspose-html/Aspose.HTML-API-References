---
title: "IDocumentEvent.CreateEvent"
second_title: "Aspose.HTML voor Java API-referentie"
description: "IDocumentEvent‑methode. De createEvent‑methode wordt gebruikt bij het maken van Events wanneer het voor de gebruiker onhandig of overbodig is om zelf een Event te creëren."
type: docs

url: /nl/java/com.aspose.html.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

De createEvent‑methode wordt gebruikt bij het maken van Events wanneer het voor de gebruiker onhandig of onnodig is om zelf een Event te creëren.

```java
public Event CreateEvent(String eventType)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eventType | String | De eventType‑parameter specificeert het type interface dat moet worden gecreëerd. Als de opgegeven interface wordt ondersteund door de implementatie, zal deze methode een nieuw object van het gevraagde interface‑type retourneren. Als de via de methode moet worden verzonden, moet de juiste methode na creatie worden aangeroepen om de waarden te initialiseren. De methode wordt gebruikt bij het maken van s wanneer het voor de gebruiker onhandig of overbodig is om zelf een te creëren. In gevallen waarin de geleverde implementatie onvoldoende is, kunnen gebruikers hun eigen implementaties leveren voor gebruik met de methode. |

### Retourwaarde

Retourneert het nieuw gemaakte event van het opgegeven event‑type.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Wordt opgegeven als de implementatie het gevraagde interface‑type niet ondersteunt. |

### Zie ook

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
