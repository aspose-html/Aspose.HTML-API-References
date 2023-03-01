---
title: Class MouseEvent
second_title: Aspose.HTML voor .NET API-referentie
description: Aspose.Html.Dom.Events.MouseEvent klas. De MouseEventinterface biedt specifieke contextuele informatie over Mousegebeurtenissen.
type: docs
weight: 840
url: /nl/net/aspose.html.dom.events/mouseevent/
---
## MouseEvent class

De MouseEvent-interface biedt specifieke contextuele informatie over Mouse-gebeurtenissen.

```csharp
public class MouseEvent : UIEvent
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [MouseEvent](mouseevent/#constructor)(string) | Initialiseert een nieuw exemplaar van het`MouseEvent` klasse. |
| [MouseEvent](mouseevent/#constructor_1)(string, IDictionary&lt;string, object&gt;) | Initialiseert een nieuw exemplaar van het`MouseEvent` klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [AltKey](../../aspose.html.dom.events/mouseevent/altkey/) { get; } | Verwijs naar het altKey-attribuut. |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | Wordt gebruikt om aan te geven of een evenement al dan niet een bruisend evenement is. Als de gebeurtenis kan bubbelen, is de waarde waar, anders is de waarde onwaar. |
| [Button](../../aspose.html.dom.events/mouseevent/button/) { get; } | Tijdens muisgebeurtenissen die worden veroorzaakt door het indrukken of loslaten van een muisknop, MOET de knop worden gebruikt om aan te geven welke aanwijzerknop van status is veranderd. |
| [Buttons](../../aspose.html.dom.events/mouseevent/buttons/) { get; } | Tijdens muisgebeurtenissen MOETEN knoppen worden gebruikt om aan te geven welke combinatie van muisknoppen momenteel wordt ingedrukt, uitgedrukt als een bitmasker. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | Wordt gebruikt om aan te geven of de standaardactie van een gebeurtenis kan worden voorkomen. Als de standaardactie kan worden voorkomen, is de waarde waar, anders is de waarde onwaar. |
| [ClientX](../../aspose.html.dom.events/mouseevent/clientx/) { get; } | De horizontale coördinaat waarop de gebeurtenis plaatsvond ten opzichte van de viewport die aan de gebeurtenis is gekoppeld. |
| [ClientY](../../aspose.html.dom.events/mouseevent/clienty/) { get; } | De verticale coördinaat waarop de gebeurtenis plaatsvond ten opzichte van de viewport die aan de gebeurtenis is gekoppeld. |
| [CtrlKey](../../aspose.html.dom.events/mouseevent/ctrlkey/) { get; } | Verwijs naar het ctrlKey-attribuut. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | Wordt gebruikt om de[`IEventTarget`](../ieventtarget/) van wie[`IEventListener`](../ieventlistener/) s worden momenteel verwerkt. Dit is vooral handig tijdens het vastleggen en bellen. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | Retourneert waar als preventDefault() is aangeroepen terwijl de annuleerbare kenmerkwaarde waar is, en anders onwaar. |
| [Detail](../../aspose.html.dom.events/uievent/detail/) { get; } | Specificeert wat gedetailleerde informatie over de gebeurtenis, afhankelijk van het type gebeurtenis. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | Wordt gebruikt om aan te geven welke fase van de gebeurtenisstroom momenteel wordt geëvalueerd. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | Het isTrusted-attribuut moet de waarde teruggeven waarnaar het geïnitialiseerd is. Wanneer een gebeurtenis wordt gemaakt, moet het attribuut worden geïnitialiseerd op false. |
| [MetaKey](../../aspose.html.dom.events/mouseevent/metakey/) { get; } | Verwijs naar het metaKey-attribuut. |
| [RelatedTarget](../../aspose.html.dom.events/mouseevent/relatedtarget/) { get; } | Gebruikt om een secundair EventTarget te identificeren gerelateerd aan een UI-gebeurtenis, afhankelijk van het type gebeurtenis. |
| [ScreenX](../../aspose.html.dom.events/mouseevent/screenx/) { get; } | De horizontale coördinaat waarop de gebeurtenis plaatsvond ten opzichte van de oorsprong van het schermcoördinatensysteem. |
| [ScreenY](../../aspose.html.dom.events/mouseevent/screeny/) { get; } | De verticale coördinaat waarop de gebeurtenis plaatsvond ten opzichte van de oorsprong van het schermcoördinatensysteem. |
| [ShiftKey](../../aspose.html.dom.events/mouseevent/shiftkey/) { get; } | Verwijs naar het shiftKey-attribuut. |
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

* class [UIEvent](../uievent/)
* naamruimte [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* montage [Aspose.HTML](../../)


