---
title: "IDocumentEvent.CreateEvent"
second_title: "Aspose.HTML voor Java API-referentie"
description: "IDocumentEvent‑methode. De createEvent‑methode wordt gebruikt bij het maken van Events wanneer het voor de gebruiker onhandig of onnodig is om zelf een Event te creëren."
type: docs

url: /nl/java/com.aspose.html.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

De createEvent‑methode wordt gebruikt bij het aanmaken van Events wanneer het voor de gebruiker onhandig of onnodig is om zelf een Event te creëren.

```java
public Event CreateEvent(String eventType)
```

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eventType | String | De eventType‑parameter specificeert het type interface dat moet worden gecreëerd. Als de opgegeven interface wordt ondersteund door de implementatie, zal deze methode een nieuw object van het gevraagde interfacetype retourneren. Als de via de methode moet worden verzonden, moet de juiste methode na de creatie worden aangeroepen om de waarden te initialiseren. De methode wordt gebruikt bij het creëren van s wanneer het voor de gebruiker onhandig of onnodig is om ze zelf te maken. In gevallen waarin de door de implementatie geleverde niet voldoende is, kunnen gebruikers hun eigen implementaties leveren voor gebruik met de methode. |

### Retourwaarde

Retourneert het nieuw aangemaakte event van het opgegeven eventtype.

### Uitzonderingen

| uitzondering | conditie |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Opgeworpen als theimplementation het gevraagde interfacetype niet ondersteunt |

### Zie ook

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
