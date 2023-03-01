---
title: Class KeyboardEvent
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Dom.Events.KeyboardEvent klas. De KeyboardEventinterface biedt specifieke contextuele informatie over toetsenbordapparaten. Elke toetsenbordgebeurtenis verwijst naar een toets met behulp van een waarde. Toetsenbordgebeurtenissen zijn gewoonlijk gericht op het element dat de focus heeft.
type: docs
weight: 830
url: /nl/net/aspose.html.dom.events/keyboardevent/
---
## KeyboardEvent class

De KeyboardEvent-interface biedt specifieke contextuele informatie over toetsenbordapparaten. Elke toetsenbordgebeurtenis verwijst naar een toets met behulp van een waarde. Toetsenbordgebeurtenissen zijn gewoonlijk gericht op het element dat de focus heeft.

```csharp
public class KeyboardEvent : UIEvent
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [KeyboardEvent](keyboardevent/#constructor)(string) | Initialiseert een nieuw exemplaar van het`KeyboardEvent` klasse. |
| [KeyboardEvent](keyboardevent/#constructor_1)(string, IDictionary&lt;string, object&gt;) | Initialiseert een nieuw exemplaar van het`KeyboardEvent` klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AltKey](../../aspose.html.dom.events/keyboardevent/altkey/) { get; } | waar als de Alt (alternatieve) (of "Option") toetsmodifier actief was. De niet-geïnitialiseerde waarde van dit kenmerk MOET onwaar zijn. |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | Wordt gebruikt om aan te geven of een evenement al dan niet een bruisend evenement is. Als de gebeurtenis kan bubbelen, is de waarde waar, anders is de waarde onwaar. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | Wordt gebruikt om aan te geven of de standaardactie van een gebeurtenis kan worden voorkomen. Als de standaardactie kan worden voorkomen, is de waarde waar, anders is de waarde onwaar. |
| [Code](../../aspose.html.dom.events/keyboardevent/code/) { get; } | De code bevat een tekenreeks die de fysieke toets identificeert die wordt ingedrukt. De waarde wordt niet beïnvloed door de huidige toetsenbordindeling of wijzigingsstatus, dus een bepaalde toets retourneert altijd dezelfde waarde. |
| [CtrlKey](../../aspose.html.dom.events/keyboardevent/ctrlkey/) { get; } | waar als de wijzigingstoets Control (control) actief was. De niet-geïnitialiseerde waarde van dit attribuut MOET onwaar zijn. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | Wordt gebruikt om de[`IEventTarget`](../ieventtarget/) van wie[`IEventListener`](../ieventlistener/) s worden momenteel verwerkt. Dit is vooral handig tijdens het vastleggen en bellen. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | Retourneert waar als preventDefault() is aangeroepen terwijl de annuleerbare kenmerkwaarde waar is, en anders onwaar. |
| [Detail](../../aspose.html.dom.events/uievent/detail/) { get; } | Specificeert wat gedetailleerde informatie over de gebeurtenis, afhankelijk van het type gebeurtenis. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | Wordt gebruikt om aan te geven welke fase van de gebeurtenisstroom momenteel wordt geëvalueerd. |
| [IsComposing](../../aspose.html.dom.events/keyboardevent/iscomposing/) { get; } | waar als de sleutelgebeurtenis plaatsvindt als onderdeel van een compositiesessie, dwz na een compositiestartgebeurtenis en vóór de overeenkomstige compositieeindgebeurtenis. De niet-geïnitialiseerde waarde van dit kenmerk MOET onwaar zijn. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | Het isTrusted-attribuut moet de waarde teruggeven waarnaar het geïnitialiseerd is. Wanneer een gebeurtenis wordt gemaakt, moet het attribuut worden geïnitialiseerd op false. |
| [Key](../../aspose.html.dom.events/keyboardevent/key/) { get; } | De toets bevat de toetswaarde van de ingedrukte toets. Als de waarde een gedrukte weergave heeft, MOET het een niet-lege Unicode-tekenreeks zijn, conform het algoritme voor het bepalen van de sleutelwaarde die in deze specificatie is gedefinieerd. Als de waarde een controlesleutel is die geen gedrukte weergave heeft, MOET het een van de sleutelwaarden zijn die zijn gedefinieerd in de set sleutelwaarden, zoals bepaald door het algoritme voor het bepalen van de sleutelwaarde. Implementaties die geen sleutel kunnen identificeren, MOETEN de sleutelwaarde Unidentified. gebruiken |
| [Location](../../aspose.html.dom.events/keyboardevent/location/) { get; } | Het location attribuut bevat een indicatie van de logische locatie van de sleutel op het apparaat. |
| [MetaKey](../../aspose.html.dom.events/keyboardevent/metakey/) { get; } | waar als de meta (Meta) key modifier actief was. |
| [Repeat](../../aspose.html.dom.events/keyboardevent/repeat/) { get; } | waar als de toets langdurig is ingedrukt. Het ingedrukt houden van een toets MOET resulteren in het herhalen van de gebeurtenissen keydown, vóór invoer, invoer in deze volgorde, met een snelheid bepaald door de systeemconfiguratie. Voor mobiele apparaten die het gedrag van lang indrukken van toetsen vertonen, MOET de eerste toetsgebeurtenis met een herhalingsattribuutwaarde waar MOETEN dienen als indicatie van lang indrukken van toetsen. De tijdsduur dat de toets ingedrukt MOET worden om te beginnen met herhalen is afhankelijk van de configuratie. |
| [ShiftKey](../../aspose.html.dom.events/keyboardevent/shiftkey/) { get; } | waar als de wijzigingstoets shift (Shift) actief was. |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | Wordt gebruikt om de[`IEventTarget`](../ieventtarget/) waarnaar het evenement oorspronkelijk is verzonden. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | Wordt gebruikt om de tijd (in milliseconden ten opzichte van het tijdperk) op te geven waarop de gebeurtenis is gemaakt. Vanwege het feit dat sommige systemen deze informatie mogelijk niet verstrekken, is de waarde van timeStamp mogelijk niet beschikbaar voor alle gebeurtenissen. Indien niet beschikbaar , wordt een waarde van 0 geretourneerd. Voorbeelden van epochetijd zijn de tijd van de systeemstart of 0:0:0 UTC 1 januari 1970. |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | De naam van de gebeurtenis (niet hoofdlettergevoelig). De naam moet een XML-naam zijn. |
| [View](../../aspose.html.dom.events/uievent/view/) { get; } | Het attribuut view identificeert het venster van waaruit de gebeurtenis is gegenereerd. De niet-geïnitialiseerde waarde van dit attribuut MOET null zijn. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halenType . |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | De[`InitEvent`](../event/initevent/) methode wordt gebruikt om de waarde van een te initialiseren[`Event`](../event/) gemaakt door the [`IDocumentEvent`](../idocumentevent/) interface. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | Als een evenement kan worden geannuleerd, wordt de[`PreventDefault`](../event/preventdefault/) methode wordt gebruikt om aan te geven dat de gebeurtenis moet worden geannuleerd, wat betekent dat elke standaardactie die normaal gesproken door de implementatie wordt ondernomen als gevolg van de gebeurtenis, niet zal plaatsvinden. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | Het aanroepen van deze methode voorkomt dat de gebeurtenis gebeurtenislisteners bereikt die zijn geregistreerd na de huidige en wanneer deze in een boomstructuur wordt verzonden, wordt ook voorkomen dat de gebeurtenis andere objecten bereikt. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | De[`StopPropagation`](../event/stoppropagation/) methode wordt gebruikt om verdere verspreiding van een gebeurtenis tijdens de gebeurtenisstroom te voorkomen. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [DOM_KEY_LOCATION_LEFT](../../aspose.html.dom.events/keyboardevent/dom_key_location_left/) | De geactiveerde sleutel is afkomstig van de linker sleutellocatie (wanneer er meer dan één mogelijke locatie voor deze sleutel is). |
| const [DOM_KEY_LOCATION_NUMPAD](../../aspose.html.dom.events/keyboardevent/dom_key_location_numpad/) | De activering van de toets vond plaats op het numerieke toetsenbord of met een virtuele toets die overeenkomt met het numerieke toetsenbord (wanneer er meer dan één mogelijke locatie voor deze toets is). Merk op dat de NumLock-sleutel altijd moet worden gecodeerd met een locatie van DOM_KEY_LOCATION_STANDARD. |
| const [DOM_KEY_LOCATION_RIGHT](../../aspose.html.dom.events/keyboardevent/dom_key_location_right/) | De sleutelactivering is afkomstig van de juiste sleutellocatie (wanneer er meer dan één mogelijke locatie voor deze sleutel is). |
| const [DOM_KEY_LOCATION_STANDARD](../../aspose.html.dom.events/keyboardevent/dom_key_location_standard/) | De activering van de toets MAG NIET worden onderscheiden als de linker- of rechterversie van de toets, en (behalve de NumLock-toets) is niet afkomstig van het numerieke toetsenblok (of is niet afkomstig van een virtuele toets die overeenkomt met het numerieke toetsenblok). |

### Zie ook

* class [UIEvent](../uievent/)
* naamruimte [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* montage [Aspose.HTML](../../)


