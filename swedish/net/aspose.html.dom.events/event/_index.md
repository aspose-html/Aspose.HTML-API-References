---
title: Class Event
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Dom.Events.Event klass. DenEvent används för att tillhandahålla kontextuell information om en händelse till hanteraren som bearbetar händelsen.
type: docs
weight: 770
url: /sv/net/aspose.html.dom.events/event/
---
## Event class

Den`Event` används för att tillhandahålla kontextuell information om en händelse till hanteraren som bearbetar händelsen.

```csharp
public class Event : DOMObject
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Event](event/#constructor)(string) | Initierar en ny instans av`Event` class. |
| [Event](event/#constructor_1)(string, IDictionary&lt;string, object&gt;) | Initierar en ny instans av`Event` class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | Används för att indikera om en händelse är en bubblande händelse eller inte. Om händelsen kan bubbla är värdet sant, annars är värdet false. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | Används för att indikera om en händelse kan förhindras eller inte. Om standardåtgärden kan förhindras är värdet sant, annars är värdet false. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | Används för att indikera[`IEventTarget`](../ieventtarget/) vars[`IEventListener`](../ieventlistener/) s bearbetas för närvarande. Detta är särskilt användbart under fångst och bubbling. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | Returnerar true om preventDefault() anropades medan det annullerbara attributvärdet är sant, och annars false. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | Används för att indikera vilken fas av händelseflödet som för närvarande utvärderas. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | isTrusted-attributet måste returnera värdet som det initierades till. När en händelse skapas måste attributet initieras till false. |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | Används för att indikera[`IEventTarget`](../ieventtarget/) som händelsen ursprungligen skickades till. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | Används för att ange tidpunkten (i millisekunder i förhållande till epok) då händelsen skapades. På grund av det faktum att vissa system kanske inte tillhandahåller denna information, kanske värdet av timeStamp inte är tillgängligt för alla händelser. När inte tillgängligt , kommer ett värde på 0 att returneras. Exempel på epoktid är tidpunkten för systemets start eller 0:0:0 UTC 1 januari 1970. |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | Namnet på händelsen (skiftlägeskänsligt). Namnet måste vara ett XML-namn. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektType . |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | Den[`InitEvent`](./initevent/) metod används för att initiera värdet av en`Event` skapad genom [`IDocumentEvent`](../idocumentevent/) gränssnitt. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | Om en händelse kan avbrytas,[`PreventDefault`](./preventdefault/) metod används för att indikera att händelsen ska avbrytas, vilket betyder att någon standardåtgärd som normalt vidtas av implementeringen som ett resultat av händelsen inte kommer att inträffa. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | Att anropa den här metoden förhindrar händelsen från att nå alla händelseavlyssnare som är registrerade efter den aktuella och när den skickas i ett träd förhindras även händelsen från att nå andra objekt. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | Den[`StopPropagation`](./stoppropagation/) metod används för att förhindra ytterligare spridning av en händelse under händelseflödet. |

## Fält

| namn | Beskrivning |
| --- | --- |
| const [AtTargetPhase](../../aspose.html.dom.events/event/attargetphase/) | Den aktuella händelsefasen är fångstfasen. |
| const [BubblingPhase](../../aspose.html.dom.events/event/bubblingphase/) | Den aktuella händelsefasen är den bubblande fasen. |
| const [CapturingPhase](../../aspose.html.dom.events/event/capturingphase/) | Händelsen utvärderas för närvarande vid målet[`IEventTarget`](../ieventtarget/) . |
| const [NonePhase](../../aspose.html.dom.events/event/nonephase/) | Händelser som för närvarande inte skickas är i denna fas. |

### Anmärkningar

Ett objekt som implementerar`Event` skickas vanligtvis som den första parametern till en händelsehanterare. Mer specifik kontextinformation skickas till händelsehanterare genom att härleda ytterligare gränssnitt från`Event` som innehåller information som är direkt relaterad till den typ av händelse de åtföljer. Dessa härledda gränssnitt implementeras också av objektet som skickas till händelseavlyssnaren.

### Se även

* class [DOMObject](../../aspose.html.dom/domobject/)
* namnutrymme [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* hopsättning [Aspose.HTML](../../)


