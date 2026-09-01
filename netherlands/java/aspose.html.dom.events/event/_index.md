---
title: "Evenementklasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.events.Event‑klasse. Deze wordt gebruikt om contextuele informatie over een gebeurtenis aan de handler die de gebeurtenis verwerkt te verstrekken."
type: docs

url: /nl/java/com.aspose.html.dom.events/event/
---
## Event class

De wordt gebruikt om contextuele informatie over een gebeurtenis aan de handler die de gebeurtenis verwerkt te bieden.

```java
public class Event : DOMObject
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [Event](event/#constructor)(String) | Initialiseert een nieuw exemplaar van de `Event`‑klasse. |
| [Event](event/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Wordt gebruikt om aan te geven of een gebeurtenis een bubbelende gebeurtenis is. Als de gebeurtenis kan bubbelen, is de waarde true, anders is de waarde false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Wordt gebruikt om aan te geven of een gebeurtenis zijn standaardactie kan voorkomen. Als de standaardactie kan worden voorkomen, is de waarde true, anders is de waarde false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Wordt gebruikt om het [`IEventTarget`](../ieventtarget/) aan te geven waarvan de [`IEventListener`](../ieventlistener/)s momenteel worden verwerkt. Dit is bijzonder nuttig tijdens het vastleggen en bubbelen. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Retourneert true als preventDefault() werd aangeroepen terwijl de cancelable‑attribuutwaarde true is, en anders false. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Wordt gebruikt om aan te geven welke fase van de gebeurtenisstroom momenteel wordt geëvalueerd. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Het isTrusted‑attribuut moet de waarde retourneren waarmee het is geïnitialiseerd. Wanneer een gebeurtenis wordt aangemaakt, moet het attribuut worden geïnitialiseerd op false. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Wordt gebruikt om de [`IEventTarget`](../ieventtarget/) aan te geven waarnaar het evenement oorspronkelijk is verzonden. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Wordt gebruikt om de tijd (in milliseconden ten opzichte van de epoch) op te geven waarop het evenement is aangemaakt. Omdat sommige systemen deze informatie mogelijk niet leveren, kan de waarde van timeStamp voor sommige evenementen niet beschikbaar zijn. Wanneer deze niet beschikbaar is, wordt een waarde van 0 geretourneerd. Voorbeelden van epoch‑tijd zijn de tijd van het systeemstart of 0:0:0 UTC 1 januari 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) De naam van het evenement (niet hoofdlettergevoelig). De naam moet een XML‑naam zijn. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halen. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | De [`InitEvent`](./initevent/)‑methode wordt gebruikt om de waarde van een `Event` te initialiseren die via de [`IDocumentEvent`](../idocumentevent/)‑interface is aangemaakt. |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Als een gebeurtenis annuleerbaar is, wordt de [`PreventDefault`](./preventdefault/)‑methode gebruikt om aan te geven dat de gebeurtenis moet worden geannuleerd, wat betekent dat elke standaardactie die normaal door de implementatie wordt uitgevoerd als gevolg van de gebeurtenis niet zal plaatsvinden. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Het aanroepen van deze methode voorkomt dat het evenement eventuele event‑listeners bereikt die na de huidige zijn geregistreerd en, wanneer het in een boom wordt verzonden, voorkomt het ook dat het evenement andere objecten bereikt. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | De [`StopPropagation`](./stoppropagation/)‑methode wordt gebruikt om verdere propagatie van een gebeurtenis tijdens de gebeurtenisstroom te voorkomen. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [AtTargetPhase](../../com.aspose.html.dom.events/event/attargetphase/) | De huidige gebeurtenisfase is de capture‑fase. |
| const [BubblingPhase](../../com.aspose.html.dom.events/event/bubblingphase/) | De huidige gebeurtenisfase is de bubbling‑fase. |
| const [CapturingPhase](../../com.aspose.html.dom.events/event/capturingphase/) | De gebeurtenis wordt momenteel geëvalueerd op het doelwit [`IEventTarget`](../ieventtarget/). |
| const [NonePhase](../../com.aspose.html.dom.events/event/nonephase/) | Gebeurtenissen die momenteel niet worden verzonden, bevinden zich in deze fase. |

## Opmerkingen

Een object dat de interface implementeert, wordt doorgaans als eerste parameter aan een gebeurtenis‑handler doorgegeven. Meer specifieke contextinformatie wordt aan gebeurtenis‑handlers doorgegeven door extra interfaces af te leiden die informatie bevatten die rechtstreeks betrekking heeft op het type gebeurtenis dat ze begeleiden. Deze afgeleide interfaces worden ook geïmplementeerd door het object dat aan de gebeurtenislistener wordt doorgegeven.

### Zie ook

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
