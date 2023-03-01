---
title: Class InputEvent
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Dom.Events.InputEvent klass. Indatahändelser skickas som aviseringar när DOM uppdateras.
type: docs
weight: 820
url: /sv/net/aspose.html.dom.events/inputevent/
---
## InputEvent class

Indatahändelser skickas som aviseringar när DOM uppdateras.

```csharp
public class InputEvent : UIEvent
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [InputEvent](inputevent/#constructor)(string) | Initierar en ny instans av`InputEvent` class. |
| [InputEvent](inputevent/#constructor_1)(string, IDictionary&lt;string, object&gt;) | Initierar en ny instans av`InputEvent` class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | Används för att indikera om en händelse är en bubblande händelse eller inte. Om händelsen kan bubbla är värdet sant, annars är värdet false. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | Används för att indikera om en händelse kan förhindras eller inte. Om standardåtgärden kan förhindras är värdet sant, annars är värdet false. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | Används för att indikera[`IEventTarget`](../ieventtarget/) vars[`IEventListener`](../ieventlistener/) s bearbetas för närvarande. Detta är särskilt användbart under fångst och bubbling. |
| [Data](../../aspose.html.dom.events/inputevent/data/) { get; } | Datan innehåller värdet av tecknen som genereras av en inmatningsmetod. Detta KAN vara ett enda Unicode-tecken eller en icke-tom sekvens av Unicode-tecken [Unicode]. Tecken SKA normaliseras enligt definitionen av Unicode-normaliseringsformen NFC, definierad i [UAX15]. Det här attributet KAN innehålla den tomma strängen. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | Returnerar true om preventDefault() anropades medan det annullerbara attributvärdet är sant, och annars false. |
| [Detail](../../aspose.html.dom.events/uievent/detail/) { get; } | Anger viss detaljinformation om händelsen, beroende på typen av händelse. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | Används för att indikera vilken fas av händelseflödet som för närvarande utvärderas. |
| [IsComposing](../../aspose.html.dom.events/inputevent/iscomposing/) { get; } | true om ingångshändelsen inträffar som en del av en sammansättningssession, dvs efter en sammansättningsstarthändelse och före motsvarande sammansättningssluthändelse. Det oinitierade värdet för detta attribut MÅSTE vara false. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | isTrusted-attributet måste returnera värdet som det initierades till. När en händelse skapas måste attributet initieras till false. |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | Används för att indikera[`IEventTarget`](../ieventtarget/) som händelsen ursprungligen skickades till. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | Används för att ange tidpunkten (i millisekunder i förhållande till epok) då händelsen skapades. På grund av det faktum att vissa system kanske inte tillhandahåller denna information, kanske värdet av timeStamp inte är tillgängligt för alla händelser. När inte tillgängligt , kommer ett värde på 0 att returneras. Exempel på epoktid är tidpunkten för systemets start eller 0:0:0 UTC 1 januari 1970. |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | Namnet på händelsen (skiftlägeskänsligt). Namnet måste vara ett XML-namn. |
| [View](../../aspose.html.dom.events/uievent/view/) { get; } | View-attributet identifierar fönstret från vilket händelsen genererades. Det oinitierade värdet för detta attribut MÅSTE vara null. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektType . |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | Den[`InitEvent`](../event/initevent/) metod används för att initiera värdet av en[`Event`](../event/) skapad genom [`IDocumentEvent`](../idocumentevent/) gränssnitt. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | Om en händelse kan avbrytas,[`PreventDefault`](../event/preventdefault/) metod används för att indikera att händelsen ska avbrytas, vilket betyder att någon standardåtgärd som normalt vidtas av implementeringen som ett resultat av händelsen inte kommer att inträffa. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | Att anropa den här metoden förhindrar händelsen från att nå alla händelseavlyssnare som är registrerade efter den aktuella och när den skickas i ett träd förhindras även händelsen från att nå andra objekt. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | Den[`StopPropagation`](../event/stoppropagation/) metod används för att förhindra ytterligare spridning av en händelse under händelseflödet. |

### Se även

* class [UIEvent](../uievent/)
* namnutrymme [Aspose.Html.Dom.Events](../../aspose.html.dom.events/)
* hopsättning [Aspose.HTML](../../)


