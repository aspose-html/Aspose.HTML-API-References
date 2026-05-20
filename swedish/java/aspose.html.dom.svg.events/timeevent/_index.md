---
title: "TimeEvent‑klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.svg.events.TimeEvent‑klass. TimeEvent‑gränssnittet tillhandahåller specifik kontextuell information som är associerad med Time‑händelser. De olika typerna av händelser som kan inträffa är beginEvent, endEvent och repeatEvent."
type: docs

url: /sv/java/com.aspose.html.dom.svg.events/timeevent/
---
## TimeEvent class

TimeEvent‑gränssnittet tillhandahåller specifik kontextuell information kopplad till tids‑händelser. De olika typerna av händelser som kan förekomma är: beginEvent, endEvent och repeatEvent.

```java
public class TimeEvent : Event
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Används för att ange om ett evenemang är ett bubblande evenemang eller inte. Om evenemanget kan bubbla är värdet sant, annars är värdet falskt. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Används för att ange om ett evenemang kan ha sin standardåtgärd förhindrad eller inte. Om standardåtgärden kan förhindras är värdet sant, annars falskt. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Används för att ange den [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/) vars [`IEventListener`](../../com.aspose.html.dom.events/ieventlistener/)s för närvarande bearbetas. Detta är särskilt användbart under fångst och bubbla. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Returnerar sant om preventDefault() anropades medan attributet cancelable är sant, annars falskt. |
| [getDetail](../../com.aspose.html.dom.svg.events/timeevent/detail/) Anger viss detaljinformation om händelsen, beroende på händelsetypen. För denna händelsetyp indikerar den repetitionsnumret för animationen. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Används för att ange vilken fas av händelseflödet som för närvarande utvärderas. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Attributet isTrusted måste returnera det värde som det initierades med. När ett händelseobjekt skapas måste attributet initieras till false. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Används för att ange den [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/) till vilken händelsen ursprungligen skickades. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Används för att ange tidpunkten (i millisekunder relativt till epoken) då händelsen skapades. På grund av att vissa system kanske inte tillhandahåller denna information kan värdet för timeStamp vara otillgängligt för vissa händelser. När det inte är tillgängligt returneras värdet 0. Exempel på epoktider är systemets starttid eller 0:0:0 UTC 1 januari 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) Namnet på händelsen (skiftlägesokänsligt). Namnet måste vara ett XML-namn. |
| [getView](../../com.aspose.html.dom.svg.events/timeevent/view/) View‑attributet identifierar den AbstractView [DOM2VIEWS] från vilken händelsen genererades. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektet. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | Metoden [`InitEvent`](../../com.aspose.html.dom.events/event/initevent/) används för att initiera värdet på ett [`Event`](../../com.aspose.html.dom.events/event/) som skapats via [`IDocumentEvent`](../../com.aspose.html.dom.events/idocumentevent/)-gränssnittet. |
| [initTimeEvent](../../com.aspose.html.dom.svg.events/timeevent/inittimeevent/)(String, IAbstractView, long) | Metoden initTimeEvent används för att initiera värdet på ett TimeEvent som skapats via DocumentEvent‑gränssnittet. Denna metod får endast anropas innan TimeEvent har skickats via dispatchEvent‑metoden, även om den kan anropas flera gånger under den fasen om det behövs. Om den anropas flera gånger har det sista anropet företräde. |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Om en händelse kan avbrytas, används metoden [`PreventDefault`](../../com.aspose.html.dom.events/event/preventdefault/) för att ange att händelsen ska avbrytas, vilket innebär att någon standardåtgärd som normalt utförs av implementeringen som ett resultat av händelsen inte kommer att ske. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Att anropa den här metoden förhindrar att händelsen når några händelselyssnare som registrerats efter den aktuella och, när den sänds i ett träd, förhindrar även att händelsen når andra objekt. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | Metoden [`StopPropagation`](../../com.aspose.html.dom.events/event/stoppropagation/) används för att förhindra ytterligare spridning av en händelse under händelseflödet. |

### Se även

* class [Event](../../com.aspose.html.dom.events/event/)
* package [com.aspose.html.dom.svg.events](../../com.aspose.html.dom.svg.events/)
* package [Aspose.HTML](../../)
