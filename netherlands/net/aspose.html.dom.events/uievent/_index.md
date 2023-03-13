---
title: Class UIEvent
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Dom.Events.UIEvent klas. De UIEventinterface biedt specifieke contextuele informatie die verband houdt met gebeurtenissen in de gebruikersinterface.
type: docs
weight: 850
url: /nl/net/aspose.html.dom.events/uievent/
---
## UIEvent class

De UIEvent-interface biedt specifieke contextuele informatie die verband houdt met gebeurtenissen in de gebruikersinterface.

```csharp
public class UIEvent : Event
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [UIEvent](uievent/#constructor)(string) | Initialiseert een nieuw exemplaar van het`UIEvent` klasse. |
| [UIEvent](uievent/#constructor_1)(string, IDictionary&lt;string, object&gt;) | Initialiseert een nieuw exemplaar van het`UIEvent` klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | Wordt gebruikt om aan te geven of een evenement al dan niet een bruisend evenement is. Als de gebeurtenis kan bubbelen, is de waarde waar, anders is de waarde onwaar. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | Wordt gebruikt om aan te geven of de standaardactie van een gebeurtenis kan worden voorkomen. Als de standaardactie kan worden voorkomen, is de waarde waar, anders is de waarde onwaar. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | Wordt gebruikt om de[`IEventTarget`](../ieventtarget/) van wie[`IEventListener`](../ieventlistener/) s worden momenteel verwerkt. Dit is vooral handig tijdens het vastleggen en bellen. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | Retourneert waar als preventDefault() is aangeroepen terwijl de annuleerbare kenmerkwaarde waar is, en anders onwaar. |
| [Detail](../../aspose.html.dom.events/uievent/detail/) { get; } | Specificeert wat gedetailleerde informatie over de gebeurtenis, afhankelijk van het type gebeurtenis. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | Wordt gebruikt om aan te geven welke fase van de gebeurtenisstroom momenteel wordt geëvalueerd. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | Het isTrusted-attribuut moet de waarde teruggeven waarnaar het geïnitialiseerd is. Wanneer een gebeurtenis wordt gemaakt, moet het attribuut worden geïnitialiseerd op false. |
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

### Zie ook

* class [Event](../event/)
* naamruimte [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* montage [Aspose.HTML](../../)


