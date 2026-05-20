---
title: "WheelEvent‑klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.events.WheelEvent‑klass. WheelEvent‑gränssnittet tillhandahåller specifik kontextuell information kopplad till hjulhändelser. För att skapa en instans av WheelEvent‑gränssnittet, använd WheelEvent‑konstruktorn och skicka ett valfritt WheelEventInit‑lexikon."
type: docs

url: /sv/java/com.aspose.html.dom.events/wheelevent/
---
## WheelEvent class

WheelEvent‑gränssnittet tillhandahåller specifik kontextuell information som är associerad med hjulhändelser. För att skapa en instans av WheelEvent‑gränssnittet, använd WheelEvent‑konstruktorn och skicka med ett valfritt WheelEventInit‑lexikon.

```java
public class WheelEvent : MouseEvent
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [WheelEvent](wheelevent/#constructor)(String) | Initierar en ny instans av `WheelEvent`‑klassen. |
| [WheelEvent](wheelevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getAltKey](../../com.aspose.html.dom.events/mouseevent/altkey/) Referera till altKey‑attributet. |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Används för att ange om ett evenemang är ett bubblande evenemang eller inte. Om evenemanget kan bubbla är värdet sant, annars är värdet falskt. |
| [getButton](../../com.aspose.html.dom.events/mouseevent/button/) Under mus‑event som orsakas av nedtryckning eller släpp av en musknapp, MÅSTE button användas för att ange vilken pekarenhet‑knapp som ändrade tillstånd. |
| [getButtons](../../com.aspose.html.dom.events/mouseevent/buttons/) Under alla mus‑event MÅSTE buttons användas för att ange vilken kombination av musknappar som för närvarande är nedtryckta, uttryckt som en bitmask. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Används för att ange om ett evenemang kan ha sin standardåtgärd förhindrad eller inte. Om standardåtgärden kan förhindras är värdet sant, annars falskt. |
| [getClientX](../../com.aspose.html.dom.events/mouseevent/clientx/) Den horisontella koordinaten där eventet inträffade i förhållande till den viewport som är associerad med eventet. |
| [getClientY](../../com.aspose.html.dom.events/mouseevent/clienty/) Den vertikala koordinaten där eventet inträffade i förhållande till den viewport som är associerad med eventet. |
| [getCtrlKey](../../com.aspose.html.dom.events/mouseevent/ctrlkey/) Referera till ctrlKey‑attributet. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Används för att ange den [`IEventTarget`](../ieventtarget/) vars [`IEventListener`](../ieventlistener/)s för närvarande bearbetas. Detta är särskilt användbart under fångst och bubbling. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Returnerar sant om preventDefault() anropades medan attributet cancelable är sant, annars falskt. |
| [getDeltaMode](../../com.aspose.html.dom.events/wheelevent/deltamode/) deltaMode‑attributet innehåller en indikation på enheterna för mätning av delta‑värdena. Standardvärdet är DOM_DELTA_PIXEL (pixlar). |
| [getDeltaX](../../com.aspose.html.dom.events/wheelevent/deltax/) I användaragenter där standardåtgärden för hjulhändelsen är att rulla, måste värdet vara mätningen längs x‑axeln (i pixlar, rader eller sidor) som ska rullas när händelsen inte avbryts. Annars är detta en implementationsspecifik mätning (i pixlar, rader eller sidor) av rörelsen av en hjulenhet runt x‑axeln. |
| [getDeltaY](../../com.aspose.html.dom.events/wheelevent/deltay/) I användaragenter där standardåtgärden för hjulhändelsen är att rulla, måste värdet vara mätningen längs y‑axeln (i pixlar, rader eller sidor) som ska rullas när händelsen inte avbryts. Annars är detta en implementationsspecifik mätning (i pixlar, rader eller sidor) av rörelsen av en hjulenhet runt y‑axeln. |
| [getDeltaZ](../../com.aspose.html.dom.events/wheelevent/deltaz/) I användaragenter där standardåtgärden för hjulhändelsen är att rulla, måste värdet vara mätningen längs z‑axeln (i pixlar, rader eller sidor) som ska rullas när händelsen inte avbryts. Annars är detta en implementationsspecifik mätning (i pixlar, rader eller sidor) av rörelsen av en hjulenhet runt z‑axeln. |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) Anger viss detaljerad information om händelsen, beroende på händelsetyp. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Används för att ange vilken fas av händelseflödet som för närvarande utvärderas. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Attributet isTrusted måste returnera det värde som det initierades med. När ett händelseobjekt skapas måste attributet initieras till false. |
| [getMetaKey](../../com.aspose.html.dom.events/mouseevent/metakey/) Referera till metaKey‑attributet. |
| [getRelatedTarget](../../com.aspose.html.dom.events/mouseevent/relatedtarget/) Används för att identifiera ett sekundärt EventTarget relaterat till ett UI‑händelse, beroende på händelsetypen. |
| [getScreenX](../../com.aspose.html.dom.events/mouseevent/screenx/) Den horisontella koordinaten där händelsen inträffade i förhållande till skärmens koordinatsystems ursprung. |
| [getScreenY](../../com.aspose.html.dom.events/mouseevent/screeny/) Den vertikala koordinaten där händelsen inträffade i förhållande till skärmens koordinatsystems ursprung. |
| [getShiftKey](../../com.aspose.html.dom.events/mouseevent/shiftkey/) Se attributet shiftKey. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Används för att ange [`IEventTarget`](../ieventtarget/) till vilken händelsen ursprungligen skickades. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Används för att ange tidpunkten (i millisekunder relativt till epoken) då händelsen skapades. På grund av att vissa system kanske inte tillhandahåller denna information kan värdet för timeStamp vara otillgängligt för vissa händelser. När det inte är tillgängligt returneras värdet 0. Exempel på epoktider är systemets starttid eller 0:0:0 UTC 1 januari 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) Namnet på händelsen (skiftlägesokänsligt). Namnet måste vara ett XML-namn. |
| [getView](../../com.aspose.html.dom.events/uievent/view/) View‑attributet identifierar det fönster från vilket händelsen genererades. Det oinitierade värdet för detta attribut MÅSTE vara null. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektet. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | Metoden [`InitEvent`](../event/initevent/) används för att initiera värdet för en [`Event`](../event/) som skapats genom [`IDocumentEvent`](../idocumentevent/)-gränssnittet. |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Om en händelse kan avbrytas används [`PreventDefault`](../event/preventdefault/)-metoden för att ange att händelsen ska avbrytas, vilket innebär att någon standardåtgärd som normalt utförs av implementationen som ett resultat av händelsen inte kommer att ske. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Att anropa den här metoden förhindrar att händelsen når några händelselyssnare som registrerats efter den aktuella och, när den sänds i ett träd, förhindrar även att händelsen når andra objekt. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | Metoden [`StopPropagation`](../event/stoppropagation/) används för att förhindra vidare spridning av en händelse under händelseflödet. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [DOM_DELTA_LINE](../../com.aspose.html.dom.events/wheelevent/dom_delta_line/) | Mätenheterna för delta MÅSTE vara enskilda textrader. Detta gäller för många formulärkontroller. |
| const [DOM_DELTA_PAGE](../../com.aspose.html.dom.events/wheelevent/dom_delta_page/) | Mätenheterna för delta MÅSTE vara sidor, antingen definierade som en enda skärm eller som en avgränsad sida. |
| const [DOM_DELTA_PIXEL](../../com.aspose.html.dom.events/wheelevent/dom_delta_pixel/) | Mätenheterna för delta MÅSTE vara pixlar. Detta är det vanligaste fallet i de flesta operativsystem och implementationskonfigurationer. |

### Se även

* class [MouseEvent](../mouseevent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
