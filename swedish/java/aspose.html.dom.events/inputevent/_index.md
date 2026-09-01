---
title: "InputEvent klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.events.InputEvent klass. Input‑händelser skickas som notifikationer närhelst DOM uppdateras."
type: docs

url: /sv/java/com.aspose.html.dom.events/inputevent/
---
## InputEvent class

Inmatningshändelser skickas som aviseringar när DOM uppdateras.

```java
public class InputEvent : UIEvent
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [InputEvent](inputevent/#constructor)(String) | Initierar en ny instans av klassen `InputEvent`. |
| [InputEvent](inputevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Används för att ange om ett händelse är ett bubblande händelse. Om händelsen kan bubbla är värdet sant, annars falskt. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Används för att ange om en händelse kan ha sin standardåtgärd förhindrad. Om standardåtgärden kan förhindras är värdet sant, annars falskt. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Används för att ange den [`IEventTarget`](../ieventtarget/) vars [`IEventListener`](../ieventlistener/)s för närvarande bearbetas. Detta är särskilt användbart under fångst och bubbla. |
| [getData](../../com.aspose.html.dom.events/inputevent/data/) Data håller värdet på tecknen som genereras av en inmatningsmetod. Detta KAN vara ett enskilt Unicode‑tecken eller en icke‑tom sekvens av Unicode‑tecken [Unicode]. Tecken SKA normaliseras enligt Unicode‑normaliseringsformen NFC, definierad i [UAX15]. Detta attribut KAN innehålla den tomma strängen. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Returnerar sant om preventDefault() anropades medan det avbrytbara attributets värde är sant, annars falskt. |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) Anger viss detaljerad information om händelsen, beroende på händelsetypen. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Används för att ange vilken fas av händelseflödet som för närvarande utvärderas. |
| [getIsComposing](../../com.aspose.html.dom.events/inputevent/iscomposing/) sant om inmatningseventet inträffar som en del av en kompositionssession, d.v.s. efter ett compositionstart‑event och före motsvarande compositionend‑event. Det oinitierade värdet för detta attribut MÅSTE vara falskt. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Attributet isTrusted måste returnera det värde som det initierades till. När en händelse skapas måste attributet initieras till false. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Används för att ange [`IEventTarget`](../ieventtarget/) till vilken händelsen ursprungligen skickades. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Används för att ange tiden (i millisekunder relativt till epoken) då händelsen skapades. På grund av att vissa system kanske inte tillhandahåller denna information kan värdet för timeStamp vara otillgängligt för vissa händelser. När det inte är tillgängligt returneras värdet 0. Exempel på epoktider är systemets starttid eller 0:0:0 UTC 1 januari 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) Namnet på händelsen (skiftlägesokänsligt). Namnet måste vara ett XML-namn. |
| [getView](../../com.aspose.html.dom.events/uievent/view/) view‑attributet identifierar det fönster från vilket händelsen genererades. Det oinitierade värdet för detta attribut MÅSTE vara null. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektet. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | Metoden [`InitEvent`](../event/initevent/) används för att initiera värdet för ett [`Event`](../event/) som skapats via [`IDocumentEvent`](../idocumentevent/)‑gränssnittet. |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Om en händelse kan avbrytas används metoden [`PreventDefault`](../event/preventdefault/) för att ange att händelsen ska avbrytas, vilket innebär att någon standardåtgärd som normalt utförs av implementeringen som ett resultat av händelsen inte kommer att ske. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Att anropa den här metoden förhindrar att händelsen når några händelselyssnare som registrerats efter den aktuella och när den skickas i ett träd förhindrar den även att händelsen når andra objekt. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | Metoden [`StopPropagation`](../event/stoppropagation/) används för att förhindra ytterligare spridning av en händelse under händelseflödet. |

### Se även

* class [UIEvent](../uievent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
