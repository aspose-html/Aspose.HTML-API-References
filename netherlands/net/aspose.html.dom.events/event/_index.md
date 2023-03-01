---
title: Class Event
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Dom.Events.Event klas. DeEvent wordt gebruikt om contextuele informatie over een gebeurtenis te verstrekken aan de handler die de gebeurtenis verwerkt.
type: docs
weight: 770
url: /nl/net/aspose.html.dom.events/event/
---
## Event class

De`Event` wordt gebruikt om contextuele informatie over een gebeurtenis te verstrekken aan de handler die de gebeurtenis verwerkt.

```csharp
public class Event : DOMObject
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [Event](event/#constructor)(string) | Initialiseert een nieuw exemplaar van het`Event` klasse. |
| [Event](event/#constructor_1)(string, IDictionary&lt;string, object&gt;) | Initialiseert een nieuw exemplaar van het`Event` klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | Wordt gebruikt om aan te geven of een evenement al dan niet een bruisend evenement is. Als de gebeurtenis kan bubbelen, is de waarde waar, anders is de waarde onwaar. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | Wordt gebruikt om aan te geven of de standaardactie van een gebeurtenis kan worden voorkomen. Als de standaardactie kan worden voorkomen, is de waarde waar, anders is de waarde onwaar. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | Wordt gebruikt om de[`IEventTarget`](../ieventtarget/) van wie[`IEventListener`](../ieventlistener/) s worden momenteel verwerkt. Dit is vooral handig tijdens het vastleggen en bellen. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | Retourneert waar als preventDefault() is aangeroepen terwijl de annuleerbare kenmerkwaarde waar is, en anders onwaar. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | Wordt gebruikt om aan te geven welke fase van de gebeurtenisstroom momenteel wordt geëvalueerd. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | Het isTrusted-attribuut moet de waarde teruggeven waarnaar het geïnitialiseerd is. Wanneer een gebeurtenis wordt gemaakt, moet het attribuut worden geïnitialiseerd op false. |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | Wordt gebruikt om de[`IEventTarget`](../ieventtarget/) waarnaar het evenement oorspronkelijk is verzonden. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | Wordt gebruikt om de tijd (in milliseconden ten opzichte van het tijdperk) op te geven waarop de gebeurtenis is gemaakt. Vanwege het feit dat sommige systemen deze informatie mogelijk niet verstrekken, is de waarde van timeStamp mogelijk niet beschikbaar voor alle gebeurtenissen. Indien niet beschikbaar , wordt een waarde van 0 geretourneerd. Voorbeelden van epochetijd zijn de tijd van de systeemstart of 0:0:0 UTC 1 januari 1970. |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | De naam van de gebeurtenis (niet hoofdlettergevoelig). De naam moet een XML-naam zijn. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halenType . |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | De[`InitEvent`](./initevent/) methode wordt gebruikt om de waarde van een te initialiseren`Event` gemaakt door the [`IDocumentEvent`](../idocumentevent/) interface. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | Als een evenement kan worden geannuleerd, wordt de[`PreventDefault`](./preventdefault/) methode wordt gebruikt om aan te geven dat de gebeurtenis moet worden geannuleerd, wat betekent dat elke standaardactie die normaal gesproken door de implementatie wordt ondernomen als gevolg van de gebeurtenis, niet zal plaatsvinden. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | Het aanroepen van deze methode voorkomt dat de gebeurtenis gebeurtenislisteners bereikt die zijn geregistreerd na de huidige en wanneer deze in een boomstructuur wordt verzonden, wordt ook voorkomen dat de gebeurtenis andere objecten bereikt. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | De[`StopPropagation`](./stoppropagation/) methode wordt gebruikt om verdere verspreiding van een gebeurtenis tijdens de gebeurtenisstroom te voorkomen. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [AtTargetPhase](../../aspose.html.dom.events/event/attargetphase/) | De huidige gebeurtenisfase is de opnamefase. |
| const [BubblingPhase](../../aspose.html.dom.events/event/bubblingphase/) | De huidige gebeurtenisfase is de bubbling-fase. |
| const [CapturingPhase](../../aspose.html.dom.events/event/capturingphase/) | Het evenement wordt momenteel geëvalueerd op het doel[`IEventTarget`](../ieventtarget/) . |
| const [NonePhase](../../aspose.html.dom.events/event/nonephase/) | Gebeurtenissen die momenteel niet worden verzonden, bevinden zich in deze fase. |

### Opmerkingen

Een object dat de`Event` wordt over het algemeen doorgegeven als de eerste parameter aan een gebeurtenishandler. Meer specifieke contextinformatie wordt doorgegeven aan gebeurtenishandlers door aanvullende interfaces af te leiden van`Event` die informatie bevatten die rechtstreeks verband houdt met het type gebeurtenis dat ze vergezellen. Deze afgeleide interfaces worden ook geïmplementeerd door het object dat wordt doorgegeven aan de gebeurtenislistener.

### Zie ook

* class [DOMObject](../../aspose.html.dom/domobject/)
* naamruimte [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* montage [Aspose.HTML](../../)


