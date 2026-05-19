---
title: "MouseEvent klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.events.MouseEvent class. De MouseEvent‑interface biedt specifieke contextuele informatie die verband houdt met muisgebeurtenissen."
type: docs

url: /nl/java/com.aspose.html.dom.events/mouseevent/
---
## MouseEvent class

De MouseEvent interface biedt specifieke contextuele informatie die verband houdt met muisgebeurtenissen.

```java
public class MouseEvent : UIEvent
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [MouseEvent](mouseevent/#constructor)(String) | Initialiseert een nieuw exemplaar van de `MouseEvent`‑klasse. |
| [MouseEvent](mouseevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getAltKey](../../com.aspose.html.dom.events/mouseevent/altkey/) Verwijs naar het altKey‑attribuut. |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Wordt gebruikt om aan te geven of een gebeurtenis een bubbling‑gebeurtenis is of niet. Als de gebeurtenis kan bubbelen, is de waarde true, anders is de waarde false. |
| [getButton](../../com.aspose.html.dom.events/mouseevent/button/) Tijdens muisgebeurtenissen veroorzaakt door het indrukken of loslaten van een muisknop, moet button WORDEN GEBRUIKT om aan te geven welke aanwijzerapparaatknop van status is veranderd. |
| [getButtons](../../com.aspose.html.dom.events/mouseevent/buttons/) Tijdens alle muisgebeurtenissen moeten buttons WORDEN GEBRUIKT om aan te geven welke combinatie van muisknoppen momenteel wordt ingedrukt, weergegeven als een bitmasker. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Wordt gebruikt om aan te geven of een gebeurtenis zijn standaardactie kan voorkomen. Als de standaardactie kan worden voorkomen, is de waarde true, anders is de waarde false. |
| [getClientX](../../com.aspose.html.dom.events/mouseevent/clientx/) De horizontale coördinaat waarop de gebeurtenis plaatsvond ten opzichte van de viewport die bij de gebeurtenis hoort. |
| [getClientY](../../com.aspose.html.dom.events/mouseevent/clienty/) De verticale coördinaat waarop de gebeurtenis plaatsvond ten opzichte van de viewport die bij de gebeurtenis hoort. |
| [getCtrlKey](../../com.aspose.html.dom.events/mouseevent/ctrlkey/) Verwijs naar het ctrlKey‑attribuut. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Wordt gebruikt om het [`IEventTarget`](../ieventtarget/) aan te geven waarvan de [`IEventListener`](../ieventlistener/)s momenteel worden verwerkt. Dit is bijzonder nuttig tijdens het capturen en bubbelen. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Retourneert true als preventDefault() werd aangeroepen terwijl de cancelable‑attribuutwaarde true is, en anders false. |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) Specificeert enige detailinformatie over het Event, afhankelijk van het type evenement. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Wordt gebruikt om aan te geven welke fase van de gebeurtenisstroom momenteel wordt geëvalueerd. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Het isTrusted-attribuut moet de waarde retourneren waarmee het is geïnitialiseerd. Wanneer een gebeurtenis wordt gemaakt, moet het attribuut worden geïnitialiseerd op false. |
| [getMetaKey](../../com.aspose.html.dom.events/mouseevent/metakey/) Verwijs naar het metaKey‑attribuut. |
| [getRelatedTarget](../../com.aspose.html.dom.events/mouseevent/relatedtarget/) Gebruikt om een secundaire EventTarget te identificeren die gerelateerd is aan een UI‑event, afhankelijk van het type event. |
| [getScreenX](../../com.aspose.html.dom.events/mouseevent/screenx/) De horizontale coördinaat waarop het event plaatsvond ten opzichte van de oorsprong van het schermcoördinatensysteem. |
| [getScreenY](../../com.aspose.html.dom.events/mouseevent/screeny/) De verticale coördinaat waarop het event plaatsvond ten opzichte van de oorsprong van het schermcoördinatensysteem. |
| [getShiftKey](../../com.aspose.html.dom.events/mouseevent/shiftkey/) Verwijs naar het shiftKey‑attribuut. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Gebruikt om de [`IEventTarget`](../ieventtarget/) aan te geven waaraan het evenement oorspronkelijk werd verzonden. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Gebruikt om de tijd (in milliseconden ten opzichte van het epoch) op te geven waarop het evenement werd gecreëerd. Omdat sommige systemen deze informatie mogelijk niet leveren, kan de waarde van timeStamp voor sommige evenementen niet beschikbaar zijn. Wanneer niet beschikbaar, wordt een waarde van 0 geretourneerd. Voorbeelden van epoch-tijd zijn de tijd van het systeemstart of 0:0:0 UTC 1 januari 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) De naam van het evenement (niet hoofdlettergevoelig). De naam moet een XML‑naam zijn. |
| [getView](../../com.aspose.html.dom.events/uievent/view/) Het view‑attribuut identificeert het Window waaruit het evenement werd gegenereerd. De niet‑geïnitialiseerde waarde van dit attribuut MOET null zijn. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halen. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | De [`InitEvent`](../event/initevent/) methode wordt gebruikt om de waarde van een [`Event`](../event/) te initialiseren die via de[`IDocumentEvent`](../idocumentevent/) interface is gemaakt. |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Als een evenement annuleerbaar is, wordt de [`PreventDefault`](../event/preventdefault/) methode gebruikt om aan te geven dat het evenement moet worden geannuleerd, wat betekent dat elke standaardactie die normaal door de implementatie zou worden uitgevoerd als gevolg van het evenement niet zal plaatsvinden. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Het aanroepen van deze methode voorkomt dat het evenement andere event‑listeners bereikt die na de huidige zijn geregistreerd en wanneer het in een boom wordt verzonden, voorkomt het ook dat het evenement andere objecten bereikt. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | De [`StopPropagation`](../event/stoppropagation/) methode wordt gebruikt om verdere propagatie van een evenement tijdens de gebeurtenisstroom te voorkomen. |

### Zie ook

* class [UIEvent](../uievent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
