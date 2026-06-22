---
title: "FocusEvent Klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.events.FocusEvent klasse. De FocusEvent interface biedt specifieke contextuele informatie die verband houdt met focus‑gebeurtenissen."
type: docs

url: /nl/java/com.aspose.html.dom.events/focusevent/
---
## FocusEvent class

De FocusEvent-interface biedt specifieke contextuele informatie die verband houdt met focusgebeurtenissen.

```java
public class FocusEvent : UIEvent
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [FocusEvent](focusevent/#constructor)(String) | Initialiseert een nieuw exemplaar van de `FocusEvent` klasse. |
| [FocusEvent](focusevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Wordt gebruikt om aan te geven of een gebeurtenis een bubbelende gebeurtenis is. Als de gebeurtenis kan bubbelen, is de waarde true, anders is de waarde false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Wordt gebruikt om aan te geven of een gebeurtenis zijn standaardactie kan voorkomen. Als de standaardactie kan worden voorkomen, is de waarde true, anders is de waarde false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Wordt gebruikt om het [`IEventTarget`](../ieventtarget/) aan te geven waarvan de [`IEventListener`](../ieventlistener/)s momenteel worden verwerkt. Dit is bijzonder nuttig tijdens het vastleggen en bubbelen. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Retourneert true als preventDefault() werd aangeroepen terwijl de cancelable‑attribuutwaarde true is, en anders false. |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) Specificeert enige detailinformatie over het Event, afhankelijk van het type evenement. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Wordt gebruikt om aan te geven welke fase van de gebeurtenisstroom momenteel wordt geëvalueerd. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Het isTrusted‑attribuut moet de waarde retourneren waarmee het is geïnitialiseerd. Wanneer een gebeurtenis wordt aangemaakt, moet het attribuut worden geïnitialiseerd op false. |
| [getRelatedTarget](../../com.aspose.html.dom.events/focusevent/relatedtarget/) Wordt gebruikt om een secundaire EventTarget te identificeren die gerelateerd is aan een Focus‑gebeurtenis, afhankelijk van het type gebeurtenis. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Wordt gebruikt om de [`IEventTarget`](../ieventtarget/) aan te geven waarnaar het evenement oorspronkelijk is verzonden. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Wordt gebruikt om de tijd (in milliseconden ten opzichte van de epoch) op te geven waarop het evenement is aangemaakt. Omdat sommige systemen deze informatie mogelijk niet leveren, kan de waarde van timeStamp voor sommige evenementen niet beschikbaar zijn. Wanneer deze niet beschikbaar is, wordt een waarde van 0 geretourneerd. Voorbeelden van epoch‑tijd zijn de tijd van het systeemstart of 0:0:0 UTC 1 januari 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) De naam van het evenement (niet hoofdlettergevoelig). De naam moet een XML‑naam zijn. |
| [getView](../../com.aspose.html.dom.events/uievent/view/) Het view‑attribuut identificeert het Window waaruit het evenement is gegenereerd. De niet‑geïnitialiseerde waarde van dit attribuut MOET null zijn. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halen. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | De [`InitEvent`](../event/initevent/) methode wordt gebruikt om de waarde van een [`Event`](../event/) te initialiseren die via de [`IDocumentEvent`](../idocumentevent/) interface is gemaakt. |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Als een evenement annuleerbaar is, wordt de [`PreventDefault`](../event/preventdefault/) methode gebruikt om aan te geven dat het evenement moet worden geannuleerd, wat betekent dat elke standaardactie die normaal door de implementatie als gevolg van het evenement zou worden uitgevoerd, niet zal plaatsvinden. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Het aanroepen van deze methode voorkomt dat het evenement eventuele event‑listeners bereikt die na de huidige zijn geregistreerd en, wanneer het in een boom wordt verzonden, voorkomt het ook dat het evenement andere objecten bereikt. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | De [`StopPropagation`](../event/stoppropagation/) methode wordt gebruikt om verdere propagatie van een evenement tijdens de gebeurtenisstroom te voorkomen. |

### Zie ook

* class [UIEvent](../uievent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
