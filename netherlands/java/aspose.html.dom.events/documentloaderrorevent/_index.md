---
title: "DocumentLoadErrorEvent Klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.events.DocumentLoadErrorEvent klasse. De DocumentLoadErrorEvent treedt op wanneer de aangevraagde bron niet beschikbaar is."
type: docs

url: /nl/java/com.aspose.html.dom.events/documentloaderrorevent/
---
## DocumentLoadErrorEvent class

Het DocumentLoadErrorEvent treedt op wanneer de gevraagde bron niet beschikbaar is.

```java
public class DocumentLoadErrorEvent : ErrorEvent
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Wordt gebruikt om aan te geven of een gebeurtenis een bubbelende gebeurtenis is. Als de gebeurtenis kan bubbelen, is de waarde true, anders is de waarde false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Wordt gebruikt om aan te geven of een gebeurtenis zijn standaardactie kan voorkomen. Als de standaardactie kan worden voorkomen, is de waarde true, anders is de waarde false. |
| [getColNo](../../com.aspose.html.dom.events/errorevent/colno/) Het colno‑attribuut moet de waarde retourneren waarmee het is geïnitialiseerd. Wanneer het object wordt aangemaakt, moet dit attribuut op nul worden geïnitialiseerd. Het vertegenwoordigt het kolomnummer waar de fout in het script optrad. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Wordt gebruikt om het [`IEventTarget`](../ieventtarget/) aan te geven waarvan de [`IEventListener`](../ieventlistener/)s momenteel worden verwerkt. Dit is bijzonder nuttig tijdens het vastleggen en bubbelen. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Retourneert true als preventDefault() werd aangeroepen terwijl de cancelable‑attribuutwaarde true is, en anders false. |
| [getError](../../com.aspose.html.dom.events/errorevent/error/) Het error‑attribuut moet de waarde retourneren waarmee het is geïnitialiseerd. Wanneer het object wordt aangemaakt, moet dit attribuut op null worden geïnitialiseerd. Waar toepasselijk wordt het ingesteld op het object dat de fout vertegenwoordigt (bijv. het exceptie‑object in het geval van een niet‑afgevangen DOM‑exceptie). |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Wordt gebruikt om aan te geven welke fase van de gebeurtenisstroom momenteel wordt geëvalueerd. |
| [getFileName](../../com.aspose.html.dom.events/errorevent/filename/) Het filename‑attribuut moet de waarde retourneren waarmee het is geïnitialiseerd. Wanneer het object wordt aangemaakt, moet dit attribuut worden geïnitialiseerd op de lege String. Het vertegenwoordigt de absolute URL van het script waarin de fout oorspronkelijk optrad. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Het isTrusted‑attribuut moet de waarde retourneren waarmee het is geïnitialiseerd. Wanneer een gebeurtenis wordt aangemaakt, moet het attribuut worden geïnitialiseerd op false. |
| [getLineNo](../../com.aspose.html.dom.events/errorevent/lineno/) Het lineno‑attribuut moet de waarde retourneren waarmee het is geïnitialiseerd. Wanneer het object wordt aangemaakt, moet dit attribuut op nul worden geïnitialiseerd. Het vertegenwoordigt het regelnummer waarop de fout in het script optrad. |
| [getMessage](../../com.aspose.html.dom.events/errorevent/message/) Het message‑attribuut moet de waarde retourneren waarmee het is geïnitialiseerd. Wanneer het object wordt aangemaakt, moet dit attribuut worden geïnitialiseerd op de lege String. Het vertegenwoordigt het foutbericht. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Wordt gebruikt om de [`IEventTarget`](../ieventtarget/) aan te geven waarnaar het evenement oorspronkelijk is verzonden. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Wordt gebruikt om de tijd (in milliseconden ten opzichte van de epoch) op te geven waarop het evenement is aangemaakt. Omdat sommige systemen deze informatie mogelijk niet leveren, kan de waarde van timeStamp voor sommige evenementen niet beschikbaar zijn. Wanneer deze niet beschikbaar is, wordt een waarde van 0 geretourneerd. Voorbeelden van epoch‑tijd zijn de tijd van het systeemstart of 0:0:0 UTC 1 januari 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) De naam van het evenement (niet hoofdlettergevoelig). De naam moet een XML‑naam zijn. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halen. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | De [`InitEvent`](../event/initevent/) methode wordt gebruikt om de waarde van een [`Event`](../event/) te initialiseren die via de [`IDocumentEvent`](../idocumentevent/) interface is gemaakt. |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Als een evenement annuleerbaar is, wordt de [`PreventDefault`](../event/preventdefault/) methode gebruikt om aan te geven dat het evenement moet worden geannuleerd, wat betekent dat elke standaardactie die normaal door de implementatie als gevolg van het evenement zou worden uitgevoerd, niet zal plaatsvinden. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Het aanroepen van deze methode voorkomt dat het evenement eventuele event‑listeners bereikt die na de huidige zijn geregistreerd en, wanneer het in een boom wordt verzonden, voorkomt het ook dat het evenement andere objecten bereikt. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | De [`StopPropagation`](../event/stoppropagation/) methode wordt gebruikt om verdere propagatie van een evenement tijdens de gebeurtenisstroom te voorkomen. |

### Zie ook

* class [ErrorEvent](../errorevent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
