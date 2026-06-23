---
title: "EventTarget-klass"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.EventTarget-klass. EventTarget‑gränssnittet implementeras av objekt som kan ta emot händelser och kan ha lyssnare för dem. Med andra ord implementerar varje händelse‑mål de tre metoder som är associerade med detta gränssnitt."
type: docs

url: /sv/java/com.aspose.html.dom/eventtarget/
---
## EventTarget class

EventTarget‑gränssnittet implementeras av objekt som kan ta emot händelser och kan ha lyssnare för dem. Med andra ord implementerar alla händelse‑mål de tre metoderna som är associerade med detta gränssnitt.

[`Element`](../element/), and its children, as well as [`Document`](../document/) and Window, are the most common event targets, but other objects can be event targets, too.

```java
public class EventTarget : DOMObject, IDisposable, IEventTarget
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [EventTarget](eventtarget/)() | Initierar en ny instans av EventTarget‑objektet. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_1)(String, IEventListener) | addEventListener()-metoden i `EventTarget `‑gränssnittet ställer in en funktion som kommer att anropas varje gång den specificerade händelsen levereras till målet. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/#addeventlistener)(String, DOMEventHandler, bool) | addEventListener()-metoden i [EventTarget ](T:com.aspose.html.dom.EventTarget)gränssnittet ställer in en funktion som kommer att anropas när den specificerade händelsen levereras till målet. |
| [addEventListener](../../com.aspose.html.dom/eventtarget/addeventlistener/#addeventlistener_2)(String, IEventListener, bool) | addEventListener()-metoden i [EventTarget ](T:com.aspose.html.dom.EventTarget)gränssnittet ställer in en funktion som kommer att anropas när den specificerade händelsen levereras till målet. |
| [dispatchEvent](../../com.aspose.html.dom/eventtarget/dispatchevent/)(Event) | Skickar ett Event till den specificerade [`EventTarget`](../../com.aspose.html.dom.events/ieventtarget/), (synkront) och anropar de påverkade EventListeners i rätt ordning. De vanliga händelsebehandlingsreglerna (inklusive fångst- och valfri bubbelfas) gäller också för händelser som skickas manuellt med [`dispatchEvent()`](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/). |
| [dispose](../../com.aspose.html.dom/eventtarget/dispose/)() | Utför applikationsdefinierade uppgifter som är kopplade till att frigöra, släppa eller återställa ohanterade resurser. |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | Denna metod används för att hämta ECMAScript-objektet. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_1)(String, IEventListener) | Denna metod möjliggör borttagning av event‑lyssnare från händelsemålet. Om en tas bort från ett mål medan det bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Event Listeners kan aldrig anropas efter att de har tagits bort. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener)(String, DOMEventHandler, bool) | Denna metod möjliggör borttagning av event‑lyssnare från händelsemålet. Om en tas bort från ett mål medan det bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Event Listeners kan aldrig anropas efter att de har tagits bort. |
| [removeEventListener](../../com.aspose.html.dom/eventtarget/removeeventlistener/#removeeventlistener_2)(String, IEventListener, bool) | Denna metod möjliggör borttagning av event‑lyssnare från händelsemålet. Om en tas bort från ett mål medan det bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Event Listeners kan aldrig anropas efter att de har tagits bort. |

### Se även

* class [DOMObject](../domobject/)
* interface [IEventTarget](../../com.aspose.html.dom.events/ieventtarget/)
* package [com.aspose.html.dom](../../com.aspose.html.dom/)
* package [Aspose.HTML](../../)
