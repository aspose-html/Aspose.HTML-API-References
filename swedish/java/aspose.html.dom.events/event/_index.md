---
title: "Event-klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.events.Event-klass. Den används för att tillhandahålla kontextuell information om ett event till den hanterare som bearbetar eventet."
type: docs

url: /sv/java/com.aspose.html.dom.events/event/
---
## Event class

Den används för att tillhandahålla kontextuell information om en händelse till hanteraren som bearbetar händelsen.

```java
public class Event : DOMObject
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Event](event/#constructor)(String) | Initierar en ny instans av `Event`-klassen. |
| [Event](event/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Används för att ange om ett händelse är ett bubblande händelse. Om händelsen kan bubbla är värdet sant, annars falskt. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Används för att ange om en händelse kan ha sin standardåtgärd förhindrad. Om standardåtgärden kan förhindras är värdet sant, annars falskt. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Används för att ange den [`IEventTarget`](../ieventtarget/) vars [`IEventListener`](../ieventlistener/)s för närvarande bearbetas. Detta är särskilt användbart under fångst och bubbla. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Returnerar sant om preventDefault() anropades medan det avbrytbara attributets värde är sant, annars falskt. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Används för att ange vilken fas av händelseflödet som för närvarande utvärderas. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Attributet isTrusted måste returnera det värde som det initierades till. När en händelse skapas måste attributet initieras till false. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Används för att ange [`IEventTarget`](../ieventtarget/) till vilken händelsen ursprungligen skickades. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Används för att ange tiden (i millisekunder relativt till epoken) då händelsen skapades. På grund av att vissa system kanske inte tillhandahåller denna information kan värdet för timeStamp vara otillgängligt för vissa händelser. När det inte är tillgängligt returneras värdet 0. Exempel på epoktider är systemets starttid eller 0:0:0 UTC 1 januari 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) Namnet på händelsen (skiftlägesokänsligt). Namnet måste vara ett XML-namn. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektet. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | Metoden [`InitEvent`](./initevent/) används för att initiera värdet på ett `Event` skapat via [`IDocumentEvent`](../idocumentevent/)-gränssnittet. |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Om ett event kan avbrytas används metoden [`PreventDefault`](./preventdefault/) för att ange att eventet ska avbrytas, vilket innebär att någon standardåtgärd som normalt utförs av implementationen som ett resultat av eventet inte kommer att ske. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Att anropa den här metoden förhindrar att händelsen når några händelselyssnare som registrerats efter den aktuella och när den skickas i ett träd förhindrar den även att händelsen når andra objekt. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | Metoden [`StopPropagation`](./stoppropagation/) används för att förhindra ytterligare spridning av ett event under händelseflödet. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [AtTargetPhase](../../com.aspose.html.dom.events/event/attargetphase/) | Den aktuella eventfasen är fångstfasen. |
| const [BubblingPhase](../../com.aspose.html.dom.events/event/bubblingphase/) | Den aktuella eventfasen är bubbelfasen. |
| const [CapturingPhase](../../com.aspose.html.dom.events/event/capturingphase/) | Eventet utvärderas för närvarande på målet [`IEventTarget`](../ieventtarget/). |
| const [NonePhase](../../com.aspose.html.dom.events/event/nonephase/) | Event som för närvarande inte har skickats är i denna fas. |

## Anmärkningar

Ett objekt som implementerar det passas i allmänhet som den första parametern till en händelsehanterare. Mer specifik kontextinformation skickas till händelsehanterare genom att härleda ytterligare gränssnitt som innehåller information som direkt relaterar till typen av händelse de följer med. Dessa härledda gränssnitt implementeras också av objektet som skickas till händelselyssnaren.

### Se även

* class [DOMObject](../../com.aspose.html.dom/domobject/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
