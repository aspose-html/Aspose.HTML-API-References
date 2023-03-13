---
title: Class TimeEvent
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Dom.Svg.Events.TimeEvent klass. TimeEventgränssnittet tillhandahåller specifik kontextuell information associerad med Timehändelser. De olika typerna av händelser som kan inträffa är beginEvent endEvent och repeatEvent.
type: docs
weight: 1340
url: /sv/net/aspose.html.dom.svg.events/timeevent/
---
## TimeEvent class

TimeEvent-gränssnittet tillhandahåller specifik kontextuell information associerad med Time-händelser. De olika typerna av händelser som kan inträffa är: beginEvent, endEvent och repeatEvent.

```csharp
public class TimeEvent : Event
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | Används för att indikera om en händelse är en bubblande händelse eller inte. Om händelsen kan bubbla är värdet sant, annars är värdet false. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | Används för att indikera om en händelse kan förhindras eller inte. Om standardåtgärden kan förhindras är värdet sant, annars är värdet false. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | Används för att indikera[`IEventTarget`](../../aspose.html.dom.events/ieventtarget/) vars[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) s bearbetas för närvarande. Detta är särskilt användbart under fångst och bubbling. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | Returnerar true om preventDefault() anropades medan det annullerbara attributvärdet är sant, och annars false. |
| [Detail](../../aspose.html.dom.svg.events/timeevent/detail/) { get; } | Anger viss detaljinformation om händelsen, beroende på typen av händelse. För den här händelsetypen, indikerar det upprepade numret för animeringen. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | Används för att indikera vilken fas av händelseflödet som för närvarande utvärderas. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | isTrusted-attributet måste returnera värdet som det initierades till. När en händelse skapas måste attributet initieras till false. |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | Används för att indikera[`IEventTarget`](../../aspose.html.dom.events/ieventtarget/) som händelsen ursprungligen skickades till. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | Används för att ange tidpunkten (i millisekunder i förhållande till epok) då händelsen skapades. På grund av det faktum att vissa system kanske inte tillhandahåller denna information, kanske värdet av timeStamp inte är tillgängligt för alla händelser. När inte tillgängligt , kommer ett värde på 0 att returneras. Exempel på epoktid är tidpunkten för systemets start eller 0:0:0 UTC 1 januari 1970. |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | Namnet på händelsen (skiftlägeskänsligt). Namnet måste vara ett XML-namn. |
| [View](../../aspose.html.dom.svg.events/timeevent/view/) { get; } | View-attributet identifierar den AbstractView [DOM2VIEWS] från vilken händelsen genererades. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektType . |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | Den[`InitEvent`](../../aspose.html.dom.events/event/initevent/) metod används för att initiera värdet av en[`Event`](../../aspose.html.dom.events/event/) skapad genom [`IDocumentEvent`](../../aspose.html.dom.events/idocumentevent/) gränssnitt. |
| [InitTimeEvent](../../aspose.html.dom.svg.events/timeevent/inittimeevent/)(string, IAbstractView, long) | Metoden initTimeEvent används för att initiera värdet på en TimeEvent som skapats via DocumentEvent-gränssnittet. Denna metod kan endast anropas innan TimeEvent har skickats via dispatchEvent-metoden, även om den kan anropas flera gånger under den fasen om det behövs. Om den anropas flera gånger har den slutliga anropet företräde. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | Om en händelse kan avbrytas,[`PreventDefault`](../../aspose.html.dom.events/event/preventdefault/) metod används för att indikera att händelsen ska avbrytas, vilket betyder att någon standardåtgärd som normalt vidtas av implementeringen som ett resultat av händelsen inte kommer att inträffa. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | Att anropa den här metoden förhindrar händelsen från att nå alla händelseavlyssnare som är registrerade efter den aktuella och när den skickas i ett träd förhindras även händelsen från att nå andra objekt. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | Den[`StopPropagation`](../../aspose.html.dom.events/event/stoppropagation/) metod används för att förhindra ytterligare spridning av en händelse under händelseflödet. |

### Se även

* class [Event](../../aspose.html.dom.events/event/)
* namnutrymme [Aspose.Html.Dom.Svg.Events](../../aspose.html.dom.svg.events/)
* hopsättning [Aspose.HTML](../../)


