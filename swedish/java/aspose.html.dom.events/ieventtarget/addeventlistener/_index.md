---
title: "IEventTarget.AddEventListener"
second_title: "Aspose.HTML för Java API-referens"
description: "IEventTarget‑metod. EventTarget‑metoden addEventListener ställer in en funktion som kommer att anropas närhelst den angivna händelsen levereras till målet."
type: docs

url: /sv/java/com.aspose.html.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(String, IEventListener) {#addeventlistener}

EventTarget‑metoden addEventListener() ställer in en funktion som kommer att anropas varje gång den specificerade händelsen levereras till målet.

Vanliga mål är Element, Document och Window, men målet kan vara vilket objekt som helst som stödjer händelser (såsom XMLHttpRequest).

```java
public void AddEventListener(String type, IEventListener listener)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typ | String | En skiftlägeskänslig String som representerar händelsetypen att lyssna på. |
| lyssnare | IEventListener | Tar ett gränssnitt som implementeras av användaren och som innehåller metoderna som ska anropas när händelsen inträffar. |

## Anmärkningar

Om en lyssnare läggs till en lyssnare medan den bearbetar en händelse, kommer den inte att triggas av de aktuella åtgärderna men kan triggas under ett senare steg i händelseflödet, såsom bubbling‑fasen. Om flera identiska Event Listeners registreras på samma objekt med samma parametrar, kasseras de duplicerade instanserna. De orsakar inte att lyssnaren anropas två gånger och eftersom de kasseras behöver de inte tas bort med metoden.

### Se även

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener, bool) {#addeventlistener_1}

EventTarget‑metoden addEventListener() ställer in en funktion som kommer att anropas varje gång den specificerade händelsen levereras till målet.

Vanliga mål är Element, Document och Window, men målet kan vara vilket objekt som helst som stödjer händelser (såsom XMLHttpRequest).

```java
public void AddEventListener(String type, IEventListener listener, bool useCapture)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typ | String | En skiftlägeskänslig String som representerar händelsetypen att lyssna på. |
| lyssnare | IEventListener | Tar ett gränssnitt som implementeras av användaren och som innehåller metoderna som ska anropas när händelsen inträffar. |
| useCapture | Boolean | Om true, useCapture indikerar att användaren vill initiera capture. Efter att capture har initierats kommer alla händelser av den angivna typen att skickas till de registrerade innan de skickas till någon Event Target under dem i trädet. Händelser som bubblar uppåt genom trädet kommer inte att trigga en angiven att använda capture. |

## Anmärkningar

Om en lyssnare läggs till en lyssnare medan den bearbetar en händelse, kommer den inte att triggas av de aktuella åtgärderna men kan triggas under ett senare steg i händelseflödet, såsom bubbling‑fasen. Om flera identiska Event Listeners registreras på samma objekt med samma parametrar, kasseras de duplicerade instanserna. De orsakar inte att lyssnaren anropas två gånger och eftersom de kasseras behöver de inte tas bort med metoden.

### Se även

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
