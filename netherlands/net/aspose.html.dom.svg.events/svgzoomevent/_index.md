---
title: Class SVGZoomEvent
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Dom.Svg.Events.SVGZoomEvent klas. De zoomgebeurtenis vindt plaats wanneer de gebruiker een actie start die ervoor zorgt dat de huidige weergave van het SVGdocumentfragment opnieuw wordt geschaald. Event handlers worden alleen herkend op svg elementen.
type: docs
weight: 1330
url: /nl/net/aspose.html.dom.svg.events/svgzoomevent/
---
## SVGZoomEvent class

De zoomgebeurtenis vindt plaats wanneer de gebruiker een actie start die ervoor zorgt dat de huidige weergave van het SVG-documentfragment opnieuw wordt geschaald. Event handlers worden alleen herkend op 'svg' elementen.

```csharp
public class SVGZoomEvent : Event
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | Wordt gebruikt om aan te geven of een evenement al dan niet een bruisend evenement is. Als de gebeurtenis kan bubbelen, is de waarde waar, anders is de waarde onwaar. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | Wordt gebruikt om aan te geven of de standaardactie van een gebeurtenis kan worden voorkomen. Als de standaardactie kan worden voorkomen, is de waarde waar, anders is de waarde onwaar. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | Wordt gebruikt om de[`IEventTarget`](../../aspose.html.dom.events/ieventtarget/) van wie[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) s worden momenteel verwerkt. Dit is vooral handig tijdens het vastleggen en bellen. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | Retourneert waar als preventDefault() is aangeroepen terwijl de annuleerbare kenmerkwaarde waar is, en anders onwaar. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | Wordt gebruikt om aan te geven welke fase van de gebeurtenisstroom momenteel wordt geëvalueerd. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | Het isTrusted-attribuut moet de waarde teruggeven waarnaar het geïnitialiseerd is. Wanneer een gebeurtenis wordt gemaakt, moet het attribuut worden geïnitialiseerd op false. |
| [NewScale](../../aspose.html.dom.svg.events/svgzoomevent/newscale/) { get; } | De schaalfactor die van kracht zal zijn nadat de zoombewerking is verwerkt. |
| [NewTranslate](../../aspose.html.dom.svg.events/svgzoomevent/newtranslate/) { get; } | De vertaalwaarden die van kracht zullen zijn nadat de zoombewerking is verwerkt. Het SVGPoint-object is alleen-lezen. |
| [PreviousScale](../../aspose.html.dom.svg.events/svgzoomevent/previousscale/) { get; } | De schaalfactor van eerdere zoombewerkingen die van kracht was voordat de zoombewerking plaatsvond. |
| [PreviousTranslate](../../aspose.html.dom.svg.events/svgzoomevent/previoustranslate/) { get; } | De vertaalwaarden van eerdere zoombewerkingen die van kracht waren voordat de zoombewerking plaatsvond. Het SVGPoint-object is alleen-lezen. |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | Wordt gebruikt om de[`IEventTarget`](../../aspose.html.dom.events/ieventtarget/) waarnaar het evenement oorspronkelijk is verzonden. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | Wordt gebruikt om de tijd (in milliseconden ten opzichte van het tijdperk) op te geven waarop de gebeurtenis is gemaakt. Vanwege het feit dat sommige systemen deze informatie mogelijk niet verstrekken, is de waarde van timeStamp mogelijk niet beschikbaar voor alle gebeurtenissen. Indien niet beschikbaar , wordt een waarde van 0 geretourneerd. Voorbeelden van epochetijd zijn de tijd van de systeemstart of 0:0:0 UTC 1 januari 1970. |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | De naam van de gebeurtenis (niet hoofdlettergevoelig). De naam moet een XML-naam zijn. |
| [ZoomRectScreen](../../aspose.html.dom.svg.events/svgzoomevent/zoomrectscreen/) { get; } | De opgegeven zoomrechthoek in schermeenheden. Het SVGRect-object is alleen-lezen. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halenType . |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | De[`InitEvent`](../../aspose.html.dom.events/event/initevent/) methode wordt gebruikt om de waarde van een te initialiseren[`Event`](../../aspose.html.dom.events/event/) gemaakt door the [`IDocumentEvent`](../../aspose.html.dom.events/idocumentevent/) interface. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | Als een evenement kan worden geannuleerd, wordt de[`PreventDefault`](../../aspose.html.dom.events/event/preventdefault/) methode wordt gebruikt om aan te geven dat de gebeurtenis moet worden geannuleerd, wat betekent dat elke standaardactie die normaal gesproken door de implementatie wordt ondernomen als gevolg van de gebeurtenis, niet zal plaatsvinden. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | Het aanroepen van deze methode voorkomt dat de gebeurtenis gebeurtenislisteners bereikt die zijn geregistreerd na de huidige en wanneer deze in een boomstructuur wordt verzonden, wordt ook voorkomen dat de gebeurtenis andere objecten bereikt. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | De[`StopPropagation`](../../aspose.html.dom.events/event/stoppropagation/) methode wordt gebruikt om verdere verspreiding van een gebeurtenis tijdens de gebeurtenisstroom te voorkomen. |

### Zie ook

* class [Event](../../aspose.html.dom.events/event/)
* naamruimte [Aspose.Html.Dom.Svg.Events](../../aspose.html.dom.svg.events/)
* montage [Aspose.HTML](../../)


