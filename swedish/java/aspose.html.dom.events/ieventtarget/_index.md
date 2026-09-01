---
title: "IEventTarget‑gränssnitt"
second_title: "Aspose.HTML för Java API-referens"
description: "com.aspose.html.dom.events.IEventTarget‑gränssnitt. EventTarget‑gränssnittet implementeras av alla noder i en implementation som stödjer DOM‑händelsemodellen. Därför kan detta gränssnitt erhållas genom att använda bindningsspecifika kastmetoder på en instans av Node‑gränssnittet. Gränssnittet möjliggör registrering och borttagning av Event‑lyssnare samt sändning av händelser till dem."
type: docs

url: /sv/java/com.aspose.html.dom.events/ieventtarget/
---
## IEventTarget interface

Den EventTarget‑gränssnittet implementeras av alla noder i en implementation som stödjer DOM‑händelsemodellen. Därför kan detta gränssnitt erhållas genom att använda bindningsspecifika kastningsmetoder på en instans av Node‑gränssnittet. Gränssnittet möjliggör registrering och borttagning av Event‑lyssnare på en och sändning av händelser till den.

```java
public interface IEventTarget
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [addEventListener](../../com.aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener)(String, IEventListener) | EventTarget‑metoden addEventListener() ställer in en funktion som kommer att anropas varje gång den specificerade händelsen levereras till målet. |
| [addEventListener](../../com.aspose.html.dom.events/ieventtarget/addeventlistener/#addeventlistener_1)(String, IEventListener, bool) | EventTarget‑metoden addEventListener() ställer in en funktion som kommer att anropas varje gång den specificerade händelsen levereras till målet. |
| [dispatchEvent](../../com.aspose.html.dom.events/ieventtarget/dispatchevent/)(Event) | Skickar en händelse till det specificerade EventTarget, (synkront) och anropar de berörda Event‑lyssnarna i rätt ordning. De vanliga händelsebehandlingsreglerna (inklusive fångst‑ och valfri bubbelfas) gäller även för händelser som skickas manuellt med dispatchEvent(). |
| [removeEventListener](../../com.aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener)(String, IEventListener) | Denna metod möjliggör borttagning av event‑lyssnare från händelsemålet. Om en tas bort från ett mål medan det bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Event Listeners kan aldrig anropas efter att de har tagits bort. |
| [removeEventListener](../../com.aspose.html.dom.events/ieventtarget/removeeventlistener/#removeeventlistener_1)(String, IEventListener, bool) | Denna metod möjliggör borttagning av event‑lyssnare från händelsemålet. Om en tas bort från ett mål medan det bearbetar en händelse, kommer den inte att utlösas av de aktuella åtgärderna. Event Listeners kan aldrig anropas efter att de har tagits bort. |

### Se även

* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
