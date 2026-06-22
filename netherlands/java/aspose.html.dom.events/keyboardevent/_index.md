---
title: "KeyboardEvent‑klasse"
second_title: "Aspose.HTML voor Java API-referentie"
description: "com.aspose.html.dom.events.KeyboardEvent‑klasse. De KeyboardEvent‑interface biedt specifieke contextuele informatie die verband houdt met toetsenbordapparaten. Elk toetsenbord‑evenement verwijst naar een toets met behulp van een waarde. Toetsenbord‑evenementen worden meestal gericht op het element dat de focus heeft."
type: docs

url: /nl/java/com.aspose.html.dom.events/keyboardevent/
---
## KeyboardEvent class

De KeyboardEvent-interface biedt specifieke contextuele informatie die verband houdt met toetsenbordapparaten. Elke toetsenbordgebeurtenis verwijst naar een toets met behulp van een waarde. Toetsenbordgebeurtenissen worden doorgaans gericht op het element dat de focus heeft.

```java
public class KeyboardEvent : UIEvent
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [KeyboardEvent](keyboardevent/#constructor)(String) | Initialiseert een nieuw exemplaar van de `KeyboardEvent`‑klasse. |
| [KeyboardEvent](keyboardevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [getAltKey](../../com.aspose.html.dom.events/keyboardevent/altkey/) true als de Alt‑ (alternatief) (of "Option")‑toetsmodifier actief was. De niet‑geïnitialiseerde waarde van dit attribuut MOET false zijn. |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Wordt gebruikt om aan te geven of een gebeurtenis een bubbelende gebeurtenis is. Als de gebeurtenis kan bubbelen, is de waarde true, anders is de waarde false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Wordt gebruikt om aan te geven of een gebeurtenis zijn standaardactie kan voorkomen. Als de standaardactie kan worden voorkomen, is de waarde true, anders is de waarde false. |
| [getCode](../../com.aspose.html.dom.events/keyboardevent/code/) De code bevat een String die de fysieke toets identificeert die wordt ingedrukt. De waarde wordt niet beïnvloed door de huidige toetsenbordindeling of modifier‑status, dus een bepaalde toets zal altijd dezelfde waarde retourneren. |
| [getCtrlKey](../../com.aspose.html.dom.events/keyboardevent/ctrlkey/) true als de Control‑ (control)‑toetsmodifier actief was. De niet‑geïnitialiseerde waarde van dit attribuut MOET false zijn. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Wordt gebruikt om het [`IEventTarget`](../ieventtarget/) aan te geven waarvan de [`IEventListener`](../ieventlistener/)s momenteel worden verwerkt. Dit is bijzonder nuttig tijdens het vastleggen en bubbelen. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Retourneert true als preventDefault() werd aangeroepen terwijl de cancelable‑attribuutwaarde true is, en anders false. |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) Specificeert enige detailinformatie over het Event, afhankelijk van het type evenement. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Wordt gebruikt om aan te geven welke fase van de gebeurtenisstroom momenteel wordt geëvalueerd. |
| [getIsComposing](../../com.aspose.html.dom.events/keyboardevent/iscomposing/) true als het toetsevenement plaatsvindt als onderdeel van een compositiesessie, d.w.z. na een compositionstart‑evenement en vóór het overeenkomstige compositionend‑evenement. De niet‑geïnitialiseerde waarde van dit attribuut MOET false zijn. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Het isTrusted‑attribuut moet de waarde retourneren waarmee het is geïnitialiseerd. Wanneer een gebeurtenis wordt aangemaakt, moet het attribuut worden geïnitialiseerd op false. |
| [getKey](../../com.aspose.html.dom.events/keyboardevent/key/) De key bevat de sleutelwaarde van de ingedrukte toets. Als de waarde een afgedrukte weergave heeft, MOET dit een niet‑lege Unicode‑teken‑String zijn, conform het algoritme voor het bepalen van de sleutelwaarde zoals gedefinieerd in deze specificatie. Als de waarde een controle‑toets is zonder afgedrukte weergave, MOET dit een van de in de sleutelwaardenset gedefinieerde sleutelwaarden zijn, bepaald door het algoritme voor het bepalen van de sleutelwaarde. Implementaties die geen toets kunnen identificeren MOETEN de sleutelwaarde "Unidentified" gebruiken. |
| [getLocation](../../com.aspose.html.dom.events/keyboardevent/location/) Het location‑attribuut bevat een indicatie van de logische locatie van de toets op het apparaat. |
| [getMetaKey](../../com.aspose.html.dom.events/keyboardevent/metakey/) true als de meta‑ (Meta)‑toetsmodifier actief was. |
| [getRepeat](../../com.aspose.html.dom.events/keyboardevent/repeat/) true als de toets gedurende een langere tijd is ingedrukt. Het ingedrukt houden van een toets MOET ertoe leiden dat de gebeurtenissen keydown, beforeinput, input in deze volgorde worden herhaald, met een snelheid bepaald door de systeemconfiguratie. Voor mobiele apparaten met lang‑toets‑gedrag moet het eerste toetsevenement met een repeat‑attribuutwaarde van true dienen als indicatie van een lange toetsindruk. De tijdsduur dat de toets MOET worden ingedrukt om te beginnen met herhalen is afhankelijk van de configuratie. |
| [getShiftKey](../../com.aspose.html.dom.events/keyboardevent/shiftkey/) true als de shift‑ (Shift)‑toetsmodifier actief was. |
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

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [DOM_KEY_LOCATION_LEFT](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_left/) | De geactiveerde toets kwam voort uit de linker‑toetslocatie (wanneer er meer dan één mogelijke locatie voor deze toets bestaat). |
| const [DOM_KEY_LOCATION_NUMPAD](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_numpad/) | De toetsactivatie is ontstaan op het numerieke toetsenbord of met een virtuele toets die overeenkomt met het numerieke toetsenbord (wanneer er meer dan één mogelijke locatie voor deze toets is). Merk op dat de NumLock-toets altijd moet worden gecodeerd met een locatie van DOM_KEY_LOCATION_STANDARD. |
| const [DOM_KEY_LOCATION_RIGHT](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_right/) | De toetsactivatie is ontstaan vanaf de rechtertoetslocatie (wanneer er meer dan één mogelijke locatie voor deze toets is). |
| const [DOM_KEY_LOCATION_STANDARD](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_standard/) | De toetsactivatie MAG NIET worden onderscheiden als de linker- of rechterversie van de toets, en (behalve de NumLock-toets) is niet ontstaan vanaf het numerieke toetsenbord (of is niet ontstaan met een virtuele toets die overeenkomt met het numerieke toetsenbord). |

### Zie ook

* class [UIEvent](../uievent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
