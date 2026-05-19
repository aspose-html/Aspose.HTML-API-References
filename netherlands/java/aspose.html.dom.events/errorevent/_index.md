---
title: "ErrorEvent-klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.events.ErrorEvent-klasse. De ErrorEvent biedt contextuele informatie over fouten die zich tijdens runtime hebben voorgedaan"
type: docs

url: /nl/java/com.aspose.html.dom.events/errorevent/
---
## ErrorEvent class

De ErrorEvent biedt contextuele informatie over fouten die zich tijdens runtime hebben voorgedaan.

```java
public class ErrorEvent : Event
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [ErrorEvent](errorevent/#constructor_1)(Exception) | Initialiseert een nieuw exemplaar van de `ErrorEvent`-klasse. |
| [ErrorEvent](errorevent/#constructor)(IDictionary&lt;String, object&gt;) |  |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Wordt gebruikt om aan te geven of een gebeurtenis een bubbling‑gebeurtenis is of niet. Als de gebeurtenis kan bubbelen, is de waarde true, anders is de waarde false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Wordt gebruikt om aan te geven of een gebeurtenis zijn standaardactie kan voorkomen. Als de standaardactie kan worden voorkomen, is de waarde true, anders is de waarde false. |
| [getColNo](../../com.aspose.html.dom.events/errorevent/colno/) Het colno‑attribuut moet de waarde retourneren waarmee het is geïnitialiseerd. Wanneer het object wordt aangemaakt, moet dit attribuut op nul worden geïnitialiseerd. Het vertegenwoordigt het kolomnummer waar de fout in het script optrad. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Wordt gebruikt om het [`IEventTarget`](../ieventtarget/) aan te geven waarvan de [`IEventListener`](../ieventlistener/)s momenteel worden verwerkt. Dit is bijzonder nuttig tijdens het capturen en bubbelen. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Retourneert true als preventDefault() werd aangeroepen terwijl de cancelable‑attribuutwaarde true is, en anders false. |
| [getError](../../com.aspose.html.dom.events/errorevent/error/) Het error‑attribuut moet de waarde retourneren waarmee het is geïnitialiseerd. Wanneer het object wordt aangemaakt, moet dit attribuut op null worden geïnitialiseerd. Waar passend, wordt het ingesteld op het object dat de fout vertegenwoordigt (bijv. het exceptie‑object in het geval van een niet-afgevangen DOM‑exceptie). |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Wordt gebruikt om aan te geven welke fase van de gebeurtenisstroom momenteel wordt geëvalueerd. |
| [getFileName](../../com.aspose.html.dom.events/errorevent/filename/) Het filename‑attribuut moet de waarde retourneren waarmee het is geïnitialiseerd. Wanneer het object wordt aangemaakt, moet dit attribuut op een lege string worden geïnitialiseerd. Het vertegenwoordigt de absolute URL van het script waarin de fout oorspronkelijk optrad. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Het isTrusted-attribuut moet de waarde retourneren waarmee het is geïnitialiseerd. Wanneer een gebeurtenis wordt gemaakt, moet het attribuut worden geïnitialiseerd op false. |
| [getLineNo](../../com.aspose.html.dom.events/errorevent/lineno/) Het lineno-attribuut moet de waarde retourneren waarmee het is geïnitialiseerd. Wanneer het object wordt gemaakt, moet dit attribuut worden geïnitialiseerd op nul. Het vertegenwoordigt het regelnummmer waarop de fout in het script optrad. |
| [getMessage](../../com.aspose.html.dom.events/errorevent/message/) Het message-attribuut moet de waarde retourneren waarmee het is geïnitialiseerd. Wanneer het object wordt gemaakt, moet dit attribuut worden geïnitialiseerd op de lege String. Het vertegenwoordigt het foutbericht. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Gebruikt om de [`IEventTarget`](../ieventtarget/) aan te geven waaraan het evenement oorspronkelijk werd verzonden. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Gebruikt om de tijd (in milliseconden ten opzichte van het epoch) op te geven waarop het evenement werd gecreëerd. Omdat sommige systemen deze informatie mogelijk niet leveren, kan de waarde van timeStamp voor sommige evenementen niet beschikbaar zijn. Wanneer niet beschikbaar, wordt een waarde van 0 geretourneerd. Voorbeelden van epoch-tijd zijn de tijd van het systeemstart of 0:0:0 UTC 1 januari 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) De naam van het evenement (niet hoofdlettergevoelig). De naam moet een XML‑naam zijn. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halen. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | De [`InitEvent`](../event/initevent/) methode wordt gebruikt om de waarde van een [`Event`](../event/) te initialiseren die via de[`IDocumentEvent`](../idocumentevent/) interface is gemaakt. |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Als een evenement annuleerbaar is, wordt de [`PreventDefault`](../event/preventdefault/) methode gebruikt om aan te geven dat het evenement moet worden geannuleerd, wat betekent dat elke standaardactie die normaal door de implementatie zou worden uitgevoerd als gevolg van het evenement niet zal plaatsvinden. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Het aanroepen van deze methode voorkomt dat het evenement andere event‑listeners bereikt die na de huidige zijn geregistreerd en wanneer het in een boom wordt verzonden, voorkomt het ook dat het evenement andere objecten bereikt. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | De [`StopPropagation`](../event/stoppropagation/) methode wordt gebruikt om verdere propagatie van een evenement tijdens de gebeurtenisstroom te voorkomen. |

### Zie ook

* class [Event](../event/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
