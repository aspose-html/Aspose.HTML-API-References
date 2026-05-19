---
title: "Event klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.events.Event class. Dit wordt gebruikt om contextuele informatie over een gebeurtenis te bieden aan de handler die de gebeurtenis verwerkt."
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
| [Event](event/#constructor)(String) | Initialiseert een nieuw exemplaar van de `Event`-klasse. |
| [Event](event/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Wordt gebruikt om aan te geven of een gebeurtenis een bubbling‑gebeurtenis is of niet. Als de gebeurtenis kan bubbelen, is de waarde true, anders is de waarde false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Wordt gebruikt om aan te geven of een gebeurtenis zijn standaardactie kan voorkomen. Als de standaardactie kan worden voorkomen, is de waarde true, anders is de waarde false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Wordt gebruikt om het [`IEventTarget`](../ieventtarget/) aan te geven waarvan de [`IEventListener`](../ieventlistener/)s momenteel worden verwerkt. Dit is bijzonder nuttig tijdens het capturen en bubbelen. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Retourneert true als preventDefault() werd aangeroepen terwijl de cancelable‑attribuutwaarde true is, en anders false. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Wordt gebruikt om aan te geven welke fase van de gebeurtenisstroom momenteel wordt geëvalueerd. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Het isTrusted-attribuut moet de waarde retourneren waarmee het is geïnitialiseerd. Wanneer een gebeurtenis wordt gemaakt, moet het attribuut worden geïnitialiseerd op false. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Gebruikt om de [`IEventTarget`](../ieventtarget/) aan te geven waaraan het evenement oorspronkelijk werd verzonden. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Gebruikt om de tijd (in milliseconden ten opzichte van het epoch) op te geven waarop het evenement werd gecreëerd. Omdat sommige systemen deze informatie mogelijk niet leveren, kan de waarde van timeStamp voor sommige evenementen niet beschikbaar zijn. Wanneer niet beschikbaar, wordt een waarde van 0 geretourneerd. Voorbeelden van epoch-tijd zijn de tijd van het systeemstart of 0:0:0 UTC 1 januari 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) De naam van het evenement (niet hoofdlettergevoelig). De naam moet een XML‑naam zijn. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halen. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | De [`InitEvent`](./initevent/)‑methode wordt gebruikt om de waarde van een `Event` te initialiseren die via de [`IDocumentEvent`](../idocumentevent/)‑interface is gemaakt. |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Als een gebeurtenis annuleerbaar is, wordt de [`PreventDefault`](./preventdefault/)‑methode gebruikt om aan te geven dat de gebeurtenis moet worden geannuleerd, wat betekent dat elke standaardactie die normaal door de implementatie wordt uitgevoerd als gevolg van de gebeurtenis niet zal plaatsvinden. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Het aanroepen van deze methode voorkomt dat het evenement andere event‑listeners bereikt die na de huidige zijn geregistreerd en wanneer het in een boom wordt verzonden, voorkomt het ook dat het evenement andere objecten bereikt. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | De [`StopPropagation`](./stoppropagation/)‑methode wordt gebruikt om verdere propagatie van een gebeurtenis tijdens de gebeurtenisstroom te voorkomen. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [AtTargetPhase](../../com.aspose.html.dom.events/event/attargetphase/) | De huidige gebeurtenisfase is de capture‑fase. |
| const [BubblingPhase](../../com.aspose.html.dom.events/event/bubblingphase/) | De huidige gebeurtenisfase is de bubbling‑fase. |
| const [CapturingPhase](../../com.aspose.html.dom.events/event/capturingphase/) | De gebeurtenis wordt momenteel geëvalueerd bij het doelwit [`IEventTarget`](../ieventtarget/). |
| const [NonePhase](../../com.aspose.html.dom.events/event/nonephase/) | Gebeurtenissen die momenteel niet worden verzonden, bevinden zich in deze fase. |

## Opmerkingen

Een object dat de implementeert, wordt doorgaans als eerste parameter aan een gebeurtenis‑handler doorgegeven. Meer specifieke contextinformatie wordt aan gebeurtenis‑handlers doorgegeven door extra interfaces af te leiden die informatie bevatten die rechtstreeks betrekking heeft op het type gebeurtenis dat ze begeleiden. Deze afgeleide interfaces worden ook geïmplementeerd door het object dat aan de gebeurtenisluisteraar wordt doorgegeven.

### Zie ook

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
