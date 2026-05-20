---
title: "MediaQueryList-klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.window.MediaQueryList-klass. Ett MediaQueryList-objekt lagrar information om en mediaselektion som tillämpas på ett dokument med stöd för både omedelbar och händelsedriven matchning mot dokumentets tillstånd. Se CSSOM View Module-specifikationen https//www.w3.org/TR/cssom-view/the-mediaquerylist-interface"
type: docs

url: /sv/java/com.aspose.html.window/mediaquerylist/
---
## MediaQueryList class

Ett MediaQueryList‑objekt lagrar information om en mediefråga som tillämpas på ett dokument, med stöd för både omedelbar och händelsedriven matchning mot dokumentets tillstånd. Se CSSOM View Module‑specifikationen: [https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface](https://www.w3.org/TR/cssom-view/#the-mediaquerylist-interface)

```java
public class MediaQueryList : EventTarget
```

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [getDocument](../../com.aspose.html.window/mediaquerylist/document/) Kontextobjektets associerade dokument. |
| [getMatches](../../com.aspose.html.window/mediaquerylist/matches/) Ett booleskt värde som returnerar true om dokumentet för närvarande matchar mediaselektlistan, annars false. |
| [getMedia](../../com.aspose.html.window/mediaquerylist/media/) En sträng som representerar en serialiserad mediaselektion. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener) | addEventListener()-metoden i [`EventTarget `](../../com.aspose.html.dom/eventtarget/)‑gränssnittet ställer in en funktion som kommer att anropas närhelst det specificerade händelsen levereras till målet. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, DOMEventHandler, bool) | addEventListener()-metoden i [EventTarget ](T:com.aspose.html.dom.EventTarget)gränssnittet ställer in en funktion som kommer att anropas när den specificerade händelsen levereras till målet. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/)(String, IEventListener, bool) | addEventListener()-metoden i [EventTarget ](T:com.aspose.html.dom.EventTarget)gränssnittet ställer in en funktion som kommer att anropas när den specificerade händelsen levereras till målet. |
| [addListener](../../com.aspose.html.window/mediaquerylist/addlistener/)(IEventListener) | Lägg till händelselyssnare för MediaQueryList:s matchningsstatusändring. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Skickar en händelse till den specificerade [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (synkront) och anropar de berörda EventListeners i rätt ordning. De vanliga reglerna för händelsebehandling (inklusive fångst- och valfri bubbelfas) gäller också för händelser som skickas manuellt med [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Utför applikationsdefinierade uppgifter som är kopplade till att frigöra, släppa eller återställa ohanterade resurser. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektet. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener) | Denna metod möjliggör borttagning av event listeners från event target. Om en event listener tas bort från ett event target medan den bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Event Listeners kan aldrig anropas efter att de har tagits bort. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, DOMEventHandler, bool) | Denna metod möjliggör borttagning av event listeners från event target. Om en event listener tas bort från ett event target medan den bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Event Listeners kan aldrig anropas efter att de har tagits bort. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/)(String, IEventListener, bool) | Denna metod möjliggör borttagning av event listeners från event target. Om en event listener tas bort från ett event target medan den bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Event Listeners kan aldrig anropas efter att de har tagits bort. |
| [removeListener](../../com.aspose.html.window/mediaquerylist/removelistener/)(IEventListener) | Ta bort händelselyssnare för MediaQueryList:s matchningsstatusändring. |

## Händelser

| Namn | Beskrivning |
| --- | --- |
| event [OnChange](../../com.aspose.html.window/mediaquerylist/onchange/) | Händelse som avfyras på MediaQueryList när matchningsstatusen ändras. |

### Se även

* class [EventTarget](../../com.aspose.html.dom/eventtarget/)
* package [com.aspose.html.window](../../com.aspose.html.window/)
* package [Aspose.HTML](../../)
