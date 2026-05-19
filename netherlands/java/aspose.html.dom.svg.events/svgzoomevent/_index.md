---
title: "SVGZoomEvent-klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.svg.events.SVGZoomEvent-klasse. Het zoom‑evenement treedt op wanneer de gebruiker een actie start die de huidige weergave van het SVG‑documentfragment opnieuw schaalt. Event‑handlers worden alleen herkend op svg‑elementen."
type: docs

url: /nl/java/com.aspose.html.dom.svg.events/svgzoomevent/
---
## SVGZoomEvent class

Het zoom‑gebeurtenis treedt op wanneer de gebruiker een actie start die ervoor zorgt dat de huidige weergave van het SVG‑documentfragment wordt herschaald. Event‑handlers worden alleen herkend op ‘svg’-elementen.

```java
public class SVGZoomEvent : Event
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Wordt gebruikt om aan te geven of een gebeurtenis een bubbling‑gebeurtenis is of niet. Als de gebeurtenis kan bubbelen, is de waarde true, anders is de waarde false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Wordt gebruikt om aan te geven of een gebeurtenis zijn standaardactie kan voorkomen. Als de standaardactie kan worden voorkomen, is de waarde true, anders is de waarde false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Wordt gebruikt om aan te geven welke [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/) wiens [`IEventListener`](../../com.aspose.html.dom.events/ieventlistener/)s momenteel worden verwerkt. Dit is bijzonder nuttig tijdens het capturen en bubbelen. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Retourneert true als preventDefault() werd aangeroepen terwijl de cancelable‑attribuutwaarde true is, en anders false. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Wordt gebruikt om aan te geven welke fase van de gebeurtenisstroom momenteel wordt geëvalueerd. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Het isTrusted-attribuut moet de waarde retourneren waarmee het is geïnitialiseerd. Wanneer een gebeurtenis wordt gemaakt, moet het attribuut worden geïnitialiseerd op false. |
| [getNewScale](../../com.aspose.html.dom.svg.events/svgzoomevent/newscale/) De schaalfactor die van kracht zal zijn nadat de zoom‑bewerking is verwerkt. |
| [getNewTranslate](../../com.aspose.html.dom.svg.events/svgzoomevent/newtranslate/) De translatie‑waarden die van kracht zullen zijn nadat de zoom‑bewerking is verwerkt. Het SVGPoint‑object is alleen-lezen. |
| [getPreviousScale](../../com.aspose.html.dom.svg.events/svgzoomevent/previousscale/) De schaalfactor van eerdere zoom‑bewerkingen die van kracht was voordat de zoom‑bewerking plaatsvond. |
| [getPreviousTranslate](../../com.aspose.html.dom.svg.events/svgzoomevent/previoustranslate/) De translatie‑waarden van eerdere zoom‑bewerkingen die van kracht waren voordat de zoom‑bewerking plaatsvond. Het SVGPoint‑object is alleen-lezen. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Wordt gebruikt om aan te geven welk [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/) waarnaar het evenement oorspronkelijk werd verzonden. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Gebruikt om de tijd (in milliseconden ten opzichte van het epoch) op te geven waarop het evenement werd gecreëerd. Omdat sommige systemen deze informatie mogelijk niet leveren, kan de waarde van timeStamp voor sommige evenementen niet beschikbaar zijn. Wanneer niet beschikbaar, wordt een waarde van 0 geretourneerd. Voorbeelden van epoch-tijd zijn de tijd van het systeemstart of 0:0:0 UTC 1 januari 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) De naam van het evenement (niet hoofdlettergevoelig). De naam moet een XML‑naam zijn. |
| [getZoomRectScreen](../../com.aspose.html.dom.svg.events/svgzoomevent/zoomrectscreen/) De opgegeven zoom‑rechthoek in scherm‑eenheden. Het SVGRect‑object is alleen-lezen. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halen. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | De [`InitEvent`](../../com.aspose.html.dom.events/event/initevent/) methode wordt gebruikt om de waarde van een [`Event`](../../com.aspose.html.dom.events/event/) te initialiseren die via de[`IDocumentEvent`](../../com.aspose.html.dom.events/idocumentevent/) interface is aangemaakt. |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Als een evenement annuleerbaar is, wordt de [`PreventDefault`](../../com.aspose.html.dom.events/event/preventdefault/)‑methode gebruikt om aan te geven dat het evenement moet worden geannuleerd, wat betekent dat elke standaardactie die normaal door de implementatie wordt uitgevoerd als gevolg van het evenement niet zal plaatsvinden. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Het aanroepen van deze methode voorkomt dat het evenement andere event‑listeners bereikt die na de huidige zijn geregistreerd en wanneer het in een boom wordt verzonden, voorkomt het ook dat het evenement andere objecten bereikt. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | De [`StopPropagation`](../../com.aspose.html.dom.events/event/stoppropagation/)‑methode wordt gebruikt om verdere verspreiding van een evenement tijdens de gebeurtenisstroom te voorkomen. |

### Zie ook

* class [Event](../../com.aspose.html.dom.events/event/)
* package [com.aspose.html.dom.svg.events](../../com.aspose.html.dom.svg.events/)
* package [Aspose.HTML](../../)
