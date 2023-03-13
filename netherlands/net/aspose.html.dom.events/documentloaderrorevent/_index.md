---
title: Class DocumentLoadErrorEvent
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Dom.Events.DocumentLoadErrorEvent klas. DeDocumentLoadErrorEvent treedt op wanneer de aangevraagde bron niet beschikbaar is.
type: docs
weight: 750
url: /nl/net/aspose.html.dom.events/documentloaderrorevent/
---
## DocumentLoadErrorEvent class

De`DocumentLoadErrorEvent` treedt op wanneer de aangevraagde bron niet beschikbaar is.

```csharp
public class DocumentLoadErrorEvent : ErrorEvent
```

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | Wordt gebruikt om aan te geven of een evenement al dan niet een bruisend evenement is. Als de gebeurtenis kan bubbelen, is de waarde waar, anders is de waarde onwaar. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | Wordt gebruikt om aan te geven of de standaardactie van een gebeurtenis kan worden voorkomen. Als de standaardactie kan worden voorkomen, is de waarde waar, anders is de waarde onwaar. |
| [ColNo](../../aspose.html.dom.events/errorevent/colno/) { get; } | Het colno-attribuut moet de waarde retourneren waarnaar het is geïnitialiseerd. Wanneer het object wordt gemaakt, moet dit attribuut op nul worden geïnitialiseerd. Het vertegenwoordigt het kolomnummer waar de fout is opgetreden in het script. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | Wordt gebruikt om de[`IEventTarget`](../ieventtarget/) van wie[`IEventListener`](../ieventlistener/) s worden momenteel verwerkt. Dit is vooral handig tijdens het vastleggen en bellen. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | Retourneert waar als preventDefault() is aangeroepen terwijl de annuleerbare kenmerkwaarde waar is, en anders onwaar. |
| [Error](../../aspose.html.dom.events/errorevent/error/) { get; } | Het foutattribuut moet de waarde teruggeven waarop het geïnitialiseerd is. Wanneer het object wordt gemaakt, moet dit attribuut worden geïnitialiseerd op null. Waar van toepassing wordt het ingesteld op het object dat de fout vertegenwoordigt (bijvoorbeeld het uitzonderingsobject in het geval van een niet-afgevangen DOM-uitzondering). |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | Wordt gebruikt om aan te geven welke fase van de gebeurtenisstroom momenteel wordt geëvalueerd. |
| [FileName](../../aspose.html.dom.events/errorevent/filename/) { get; } | Het bestandsnaamattribuut moet de waarde teruggeven waarop het geïnitialiseerd is. Wanneer het object wordt gemaakt, moet dit attribuut worden geïnitialiseerd naar de lege tekenreeks. Het vertegenwoordigt de absolute URL van het script waarin de fout oorspronkelijk optrad. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | Het isTrusted-attribuut moet de waarde teruggeven waarnaar het geïnitialiseerd is. Wanneer een gebeurtenis wordt gemaakt, moet het attribuut worden geïnitialiseerd op false. |
| [LineNo](../../aspose.html.dom.events/errorevent/lineno/) { get; } | Het lineno-attribuut moet de waarde teruggeven waarnaar het was geïnitialiseerd. Wanneer het object wordt gemaakt, moet dit attribuut op nul worden geïnitialiseerd. Het vertegenwoordigt het regelnummer waar de fout is opgetreden in het script. |
| [Message](../../aspose.html.dom.events/errorevent/message/) { get; } | Het berichtattribuut moet de waarde retourneren waarop het was geïnitialiseerd. Wanneer het object wordt gemaakt, moet dit attribuut worden geïnitialiseerd naar de lege tekenreeks. Het vertegenwoordigt de foutmelding. |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | Wordt gebruikt om de[`IEventTarget`](../ieventtarget/) waarnaar het evenement oorspronkelijk is verzonden. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | Wordt gebruikt om de tijd (in milliseconden ten opzichte van het tijdperk) op te geven waarop de gebeurtenis is gemaakt. Vanwege het feit dat sommige systemen deze informatie mogelijk niet verstrekken, is de waarde van timeStamp mogelijk niet beschikbaar voor alle gebeurtenissen. Indien niet beschikbaar , wordt een waarde van 0 geretourneerd. Voorbeelden van epochetijd zijn de tijd van de systeemstart of 0:0:0 UTC 1 januari 1970. |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | De naam van de gebeurtenis (niet hoofdlettergevoelig). De naam moet een XML-naam zijn. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Deze methode wordt gebruikt om het ECMAScript-object op te halenType . |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | De[`InitEvent`](../event/initevent/) methode wordt gebruikt om de waarde van een te initialiseren[`Event`](../event/) gemaakt door the [`IDocumentEvent`](../idocumentevent/) interface. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | Als een evenement kan worden geannuleerd, wordt de[`PreventDefault`](../event/preventdefault/) methode wordt gebruikt om aan te geven dat de gebeurtenis moet worden geannuleerd, wat betekent dat elke standaardactie die normaal gesproken door de implementatie wordt ondernomen als gevolg van de gebeurtenis, niet zal plaatsvinden. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | Het aanroepen van deze methode voorkomt dat de gebeurtenis gebeurtenislisteners bereikt die zijn geregistreerd na de huidige en wanneer deze in een boomstructuur wordt verzonden, wordt ook voorkomen dat de gebeurtenis andere objecten bereikt. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | De[`StopPropagation`](../event/stoppropagation/) methode wordt gebruikt om verdere verspreiding van een gebeurtenis tijdens de gebeurtenisstroom te voorkomen. |

### Zie ook

* class [ErrorEvent](../errorevent/)
* naamruimte [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* montage [Aspose.HTML](../../)


