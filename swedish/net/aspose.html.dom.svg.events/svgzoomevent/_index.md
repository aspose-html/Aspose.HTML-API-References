---
title: Class SVGZoomEvent
second_title: Aspose.HTML för .NET API Referens
description: Aspose.Html.Dom.Svg.Events.SVGZoomEvent klass. Zoomhändelsen inträffar när användaren initierar en åtgärd som gör att den aktuella vyn av SVGdokumentfragmentet skalas om. Händelsehanterare känns bara igen på svgelement.
type: docs
weight: 1330
url: /sv/net/aspose.html.dom.svg.events/svgzoomevent/
---
## SVGZoomEvent class

Zoomhändelsen inträffar när användaren initierar en åtgärd som gör att den aktuella vyn av SVG-dokumentfragmentet skalas om. Händelsehanterare känns bara igen på "svg"-element.

```csharp
public class SVGZoomEvent : Event
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Bubbles](../../aspose.html.dom.events/event/bubbles/) { get; } | Används för att indikera om en händelse är en bubblande händelse eller inte. Om händelsen kan bubbla är värdet sant, annars är värdet false. |
| [Cancelable](../../aspose.html.dom.events/event/cancelable/) { get; } | Används för att indikera om en händelse kan förhindras eller inte. Om standardåtgärden kan förhindras är värdet sant, annars är värdet false. |
| [CurrentTarget](../../aspose.html.dom.events/event/currenttarget/) { get; } | Används för att indikera[`IEventTarget`](../../aspose.html.dom.events/ieventtarget/) vars[`IEventListener`](../../aspose.html.dom.events/ieventlistener/) s bearbetas för närvarande. Detta är särskilt användbart under fångst och bubbling. |
| [DefaultPrevented](../../aspose.html.dom.events/event/defaultprevented/) { get; } | Returnerar true om preventDefault() anropades medan det annullerbara attributvärdet är sant, och annars false. |
| [EventPhase](../../aspose.html.dom.events/event/eventphase/) { get; } | Används för att indikera vilken fas av händelseflödet som för närvarande utvärderas. |
| [IsTrusted](../../aspose.html.dom.events/event/istrusted/) { get; } | isTrusted-attributet måste returnera värdet som det initierades till. När en händelse skapas måste attributet initieras till false. |
| [NewScale](../../aspose.html.dom.svg.events/svgzoomevent/newscale/) { get; } | Skalfaktorn som kommer att vara på plats efter att zoomoperationen har bearbetats. |
| [NewTranslate](../../aspose.html.dom.svg.events/svgzoomevent/newtranslate/) { get; } | Översättningsvärdena som kommer att vara på plats efter att zoomoperationen har bearbetats. SVGPoint-objektet är skrivskyddat. |
| [PreviousScale](../../aspose.html.dom.svg.events/svgzoomevent/previousscale/) { get; } | Skalfaktorn från tidigare zoomoperationer som var på plats innan zoomoperationen inträffade. |
| [PreviousTranslate](../../aspose.html.dom.svg.events/svgzoomevent/previoustranslate/) { get; } | Översättningsvärdena från tidigare zoomoperationer som var på plats innan zoomoperationen inträffade. SVGPoint-objektet är skrivskyddat. |
| [Target](../../aspose.html.dom.events/event/target/) { get; } | Används för att indikera[`IEventTarget`](../../aspose.html.dom.events/ieventtarget/) som händelsen ursprungligen skickades till. |
| [TimeStamp](../../aspose.html.dom.events/event/timestamp/) { get; } | Används för att ange tidpunkten (i millisekunder i förhållande till epok) då händelsen skapades. På grund av det faktum att vissa system kanske inte tillhandahåller denna information, kanske värdet av timeStamp inte är tillgängligt för alla händelser. När inte tillgängligt , kommer ett värde på 0 att returneras. Exempel på epoktid är tidpunkten för systemets start eller 0:0:0 UTC 1 januari 1970. |
| [Type](../../aspose.html.dom.events/event/type/) { get; } | Namnet på händelsen (skiftlägeskänsligt). Namnet måste vara ett XML-namn. |
| [ZoomRectScreen](../../aspose.html.dom.svg.events/svgzoomevent/zoomrectscreen/) { get; } | Den angivna zoomrektangeln i skärmenheter. SVGRect-objektet är skrivskyddat. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [GetPlatformType](../../aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektType . |
| [InitEvent](../../aspose.html.dom.events/event/initevent/)(string, bool, bool) | Den[`InitEvent`](../../aspose.html.dom.events/event/initevent/) metod används för att initiera värdet av en[`Event`](../../aspose.html.dom.events/event/) skapad genom [`IDocumentEvent`](../../aspose.html.dom.events/idocumentevent/) gränssnitt. |
| [PreventDefault](../../aspose.html.dom.events/event/preventdefault/)() | Om en händelse kan avbrytas,[`PreventDefault`](../../aspose.html.dom.events/event/preventdefault/) metod används för att indikera att händelsen ska avbrytas, vilket betyder att någon standardåtgärd som normalt vidtas av implementeringen som ett resultat av händelsen inte kommer att inträffa. |
| [StopImmediatePropagation](../../aspose.html.dom.events/event/stopimmediatepropagation/)() | Att anropa den här metoden förhindrar händelsen från att nå alla händelseavlyssnare som är registrerade efter den aktuella och när den skickas i ett träd förhindras även händelsen från att nå andra objekt. |
| [StopPropagation](../../aspose.html.dom.events/event/stoppropagation/)() | Den[`StopPropagation`](../../aspose.html.dom.events/event/stoppropagation/) metod används för att förhindra ytterligare spridning av en händelse under händelseflödet. |

### Se även

* class [Event](../../aspose.html.dom.events/event/)
* namnutrymme [Aspose.Html.Dom.Svg.Events](../../aspose.html.dom.svg.events/)
* hopsättning [Aspose.HTML](../../)


