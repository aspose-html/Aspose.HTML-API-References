---
title: "SVGZoomEvent‑klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.svg.events.SVGZoomEvent‑klass. Zoom‑händelsen inträffar när användaren initierar en åtgärd som får den aktuella vyn av SVG‑dokumentfragmentet att skalas om. Händelsehanterare känns endast igen på svg‑element."
type: docs

url: /sv/java/com.aspose.html.dom.svg.events/svgzoomevent/
---
## SVGZoomEvent class

Zoom‑händelsen inträffar när användaren initierar en åtgärd som får den aktuella vyn av SVG‑dokumentfragmentet att skalas om. Händelsehanterare känns bara igen på ‘svg’-element.

```java
public class SVGZoomEvent : Event
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Används för att ange om ett händelse är ett bubblande händelse. Om händelsen kan bubbla är värdet sant, annars falskt. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Används för att ange om en händelse kan ha sin standardåtgärd förhindrad. Om standardåtgärden kan förhindras är värdet sant, annars falskt. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Används för att ange den [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/) vars [`IEventListener`](../../com.aspose.html.dom.events/ieventlistener/)s för närvarande bearbetas. Detta är särskilt användbart under fångst och bubbla. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Returnerar sant om preventDefault() anropades medan det avbrytbara attributets värde är sant, annars falskt. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Används för att ange vilken fas av händelseflödet som för närvarande utvärderas. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) Attributet isTrusted måste returnera det värde som det initierades till. När en händelse skapas måste attributet initieras till false. |
| [getNewScale](../../com.aspose.html.dom.svg.events/svgzoomevent/newscale/) Skalfaktorn som kommer att gälla efter att zoom‑operationen har behandlats. |
| [getNewTranslate](../../com.aspose.html.dom.svg.events/svgzoomevent/newtranslate/) Översättningsvärdena som kommer att gälla efter att zoom‑operationen har behandlats. SVGPoint‑objektet är skrivskyddat. |
| [getPreviousScale](../../com.aspose.html.dom.svg.events/svgzoomevent/previousscale/) Skalfaktorn från tidigare zoom‑operationer som var i kraft innan zoom‑operationen inträffade. |
| [getPreviousTranslate](../../com.aspose.html.dom.svg.events/svgzoomevent/previoustranslate/) Översättningsvärdena från tidigare zoom‑operationer som var i kraft innan zoom‑operationen inträffade. SVGPoint‑objektet är skrivskyddat. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Används för att ange den [`IEventTarget`](../../com.aspose.html.dom.events/ieventtarget/) till vilken händelsen ursprungligen skickades. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Används för att ange tiden (i millisekunder relativt till epoken) då händelsen skapades. På grund av att vissa system kanske inte tillhandahåller denna information kan värdet för timeStamp vara otillgängligt för vissa händelser. När det inte är tillgängligt returneras värdet 0. Exempel på epoktider är systemets starttid eller 0:0:0 UTC 1 januari 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) Namnet på händelsen (skiftlägesokänsligt). Namnet måste vara ett XML-namn. |
| [getZoomRectScreen](../../com.aspose.html.dom.svg.events/svgzoomevent/zoomrectscreen/) Den specificerade zoom‑rektangeln i skärm‑enheter. SVGRect‑objektet är skrivskyddat. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektet. |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | Metoden [`InitEvent`](../../com.aspose.html.dom.events/event/initevent/) används för att initiera värdet för ett [`Event`](../../com.aspose.html.dom.events/event/) skapat via [`IDocumentEvent`](../../com.aspose.html.dom.events/idocumentevent/)-gränssnittet. |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | Om en händelse kan avbrytas används metoden [`PreventDefault`](../../com.aspose.html.dom.events/event/preventdefault/) för att ange att händelsen ska avbrytas, vilket innebär att någon standardåtgärd som normalt utförs av implementationen som ett resultat av händelsen inte kommer att ske. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Att anropa den här metoden förhindrar att händelsen når några händelselyssnare som registrerats efter den aktuella och när den skickas i ett träd förhindrar den även att händelsen når andra objekt. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | Metoden [`StopPropagation`](../../com.aspose.html.dom.events/event/stoppropagation/) används för att förhindra ytterligare spridning av en händelse under händelseflödet. |

### Se även

* class [Event](../../com.aspose.html.dom.events/event/)
* package [com.aspose.html.dom.svg.events](../../com.aspose.html.dom.svg.events/)
* package [Aspose.HTML](../../)
