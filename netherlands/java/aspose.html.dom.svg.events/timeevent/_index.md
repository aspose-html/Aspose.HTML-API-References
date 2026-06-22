---
title: "TimeEvent Klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.svg.events.TimeEvent klasse. De TimeEvent‑interface biedt specifieke contextuele informatie die verband houdt met Time‑gebeurtenissen. De verschillende typen gebeurtenissen die kunnen optreden zijn beginEvent, endEvent en repeatEvent."
type: docs

url: /nl/java/com.aspose.html.dom.svg.events/timeevent/
---
## TimeEvent class

De TimeEvent-interface biedt specifieke contextuele informatie die verband houdt met tijdgebeurtenissen. De verschillende soorten gebeurtenissen die kunnen optreden zijn: beginEvent, endEvent en repeatEvent.

```java
public class TimeEvent : Event
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Wordt gebruikt om aan te geven of een gebeurtenis een bubbelende gebeurtenis is. Als de gebeurtenis kan bubbelen, is de waarde true, anders is de waarde false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Wordt gebruikt om aan te geven of een gebeurtenis zijn standaardactie kan voorkomen. Als de standaardactie kan worden voorkomen, is de waarde true, anders is de waarde false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Gebruikt om aan te geven de [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/) waarvan de [`IEventListener`](../../com.aspose.html.dom.events/ieventlistener/)s momenteel worden verwerkt. Dit is bijzonder nuttig tijdens het capturen en bubbelen. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Retourneert true als preventDefault() werd aangeroepen terwijl de cancelable‑attribuutwaarde true is, en anders false. |
| [getDetail](../../com.aspose.html.dom.svg.events/timeevent/detail/) Specificeert enige detailinformatie over het Event, afhankelijk van het type gebeurtenis. Voor dit type gebeurtenis geeft het het herhalingsnummer voor de animatie aan. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Wordt gebruikt om aan te geven welke fase van de gebeurtenisstroom momenteel wordt geëvalueerd. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Het isTrusted‑attribuut moet de waarde retourneren waarmee het is geïnitialiseerd. Wanneer een gebeurtenis wordt aangemaakt, moet het attribuut worden geïnitialiseerd op false. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Gebruikt om aan te geven de [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/) waaraan het evenement oorspronkelijk is verzonden. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Wordt gebruikt om de tijd (in milliseconden ten opzichte van de epoch) op te geven waarop het evenement is aangemaakt. Omdat sommige systemen deze informatie mogelijk niet leveren, kan de waarde van timeStamp voor sommige evenementen niet beschikbaar zijn. Wanneer deze niet beschikbaar is, wordt een waarde van 0 geretourneerd. Voorbeelden van epoch‑tijd zijn de tijd van het systeemstart of 0:0:0 UTC 1 januari 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) De naam van het evenement (niet hoofdlettergevoelig). De naam moet een XML‑naam zijn. |
| [getView](../../com.aspose.html.dom.svg.events/timeevent/view/) Het view‑attribuut identificeert de AbstractView [DOM2VIEWS] waaruit het evenement is gegenereerd. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halen. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | De [`InitEvent`](../../com.aspose.html.dom.events/event/initevent/) methode wordt gebruikt om de waarde van een [`Event`](../../com.aspose.html.dom.events/event/) te initialiseren die is gecreëerd via de[`IDocumentEvent`](../../com.aspose.html.dom.events/idocumentevent/) interface. |
| [initTimeEvent](../../com.aspose.html.dom.svg.events/timeevent/inittimeevent/)(String, IAbstractView, long) | De initTimeEvent‑methode wordt gebruikt om de waarde van een TimeEvent te initialiseren die via de DocumentEvent‑interface is gecreëerd. Deze methode mag alleen worden aangeroepen voordat de TimeEvent is verzonden via de dispatchEvent‑methode, hoewel hij tijdens die fase indien nodig meerdere keren kan worden aangeroepen. Als hij meerdere keren wordt aangeroepen, heeft de laatste aanroep voorrang. |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Als een evenement annuleerbaar is, wordt de [`PreventDefault`](../../com.aspose.html.dom.events/event/preventdefault/) methode gebruikt om aan te geven dat het evenement moet worden geannuleerd, wat betekent dat elke standaardactie die normaal door de implementatie zou worden uitgevoerd als gevolg van het evenement niet zal plaatsvinden. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Het aanroepen van deze methode voorkomt dat het evenement eventuele event‑listeners bereikt die na de huidige zijn geregistreerd en, wanneer het in een boom wordt verzonden, voorkomt het ook dat het evenement andere objecten bereikt. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | De [`StopPropagation`](../../com.aspose.html.dom.events/event/stoppropagation/) methode wordt gebruikt om verdere verspreiding van een evenement tijdens de gebeurtenisstroom te voorkomen. |

### Zie ook

* class [Event](../../com.aspose.html.dom.events/event/)
* package [com.aspose.html.dom.svg.events](../../com.aspose.html.dom.svg.events/)
* package [Aspose.HTML](../../)
