---
title: "CustomEvent Klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.events.CustomEvent klass. Händelser som använder CustomEvent‑gränssnittet kan användas för att bära anpassad data"
type: docs

url: /sv/java/com.aspose.html.dom.events/customevent/
---
## CustomEvent class

Händelser som använder CustomEvent‑gränssnittet kan användas för att bära anpassad data.

```java
public class CustomEvent : Event
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [CustomEvent](customevent/#constructor)(String) | Initierar en ny instans av klassen `CustomEvent`. |
| [CustomEvent](customevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Används för att ange om ett evenemang är ett bubblande evenemang eller inte. Om evenemanget kan bubbla är värdet sant, annars är värdet falskt. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Används för att ange om ett evenemang kan ha sin standardåtgärd förhindrad eller inte. Om standardåtgärden kan förhindras är värdet sant, annars falskt. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Används för att ange den [`IEventTarget`](../ieventtarget/) vars [`IEventListener`](../ieventlistener/)s för närvarande bearbetas. Detta är särskilt användbart under fångst och bubbling. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Returnerar sant om preventDefault() anropades medan attributet cancelable är sant, annars falskt. |
| [getDetail](../../com.aspose.html.dom.events/customevent/detail/) Hämtar den anpassade datan. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Används för att ange vilken fas av händelseflödet som för närvarande utvärderas. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Attributet isTrusted måste returnera det värde som det initierades med. När ett händelseobjekt skapas måste attributet initieras till false. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Används för att ange [`IEventTarget`](../ieventtarget/) till vilken händelsen ursprungligen skickades. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Används för att ange tidpunkten (i millisekunder relativt till epoken) då händelsen skapades. På grund av att vissa system kanske inte tillhandahåller denna information kan värdet för timeStamp vara otillgängligt för vissa händelser. När det inte är tillgängligt returneras värdet 0. Exempel på epoktider är systemets starttid eller 0:0:0 UTC 1 januari 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) Namnet på händelsen (skiftlägesokänsligt). Namnet måste vara ett XML-namn. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektet. |
| [initCustomEvent](../../com.aspose.html.dom.events/customevent/initcustomevent/)(String, bool, bool, object) | /// Metoden [`InitEvent`](../event/initevent/) används för att initiera värdet av ett [`Event`](../event/) skapat via [`IDocumentEvent`](../idocumentevent/)‑gränssnittet. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | Metoden [`InitEvent`](../event/initevent/) används för att initiera värdet för en [`Event`](../event/) som skapats genom [`IDocumentEvent`](../idocumentevent/)-gränssnittet. |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Om en händelse kan avbrytas används [`PreventDefault`](../event/preventdefault/)-metoden för att ange att händelsen ska avbrytas, vilket innebär att någon standardåtgärd som normalt utförs av implementationen som ett resultat av händelsen inte kommer att ske. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Att anropa den här metoden förhindrar att händelsen når några händelselyssnare som registrerats efter den aktuella och, när den sänds i ett träd, förhindrar även att händelsen når andra objekt. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | Metoden [`StopPropagation`](../event/stoppropagation/) används för att förhindra vidare spridning av en händelse under händelseflödet. |

### Se även

* class [Event](../event/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
