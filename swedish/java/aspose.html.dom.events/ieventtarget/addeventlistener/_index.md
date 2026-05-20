---
title: "IEventTarget.AddEventListener"
second_title: "Aspose.HTML för Java API-referens"
description: "IEventTarget‑metod. EventTarget‑metoden addEventListener ställer in en funktion som kommer att anropas när den angivna händelsen levereras till målet."
type: docs

url: /sv/java/com.aspose.html.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(String, IEventListener) {#addeventlistener}

EventTarget‑metoden addEventListener() ställer in en funktion som kommer att anropas varje gång den specificerade händelsen levereras till målet.

Vanliga mål är Element, Document och Window, men målet kan vara vilket objekt som helst som stödjer händelser (t.ex. XMLHttpRequest).

```java
public void AddEventListener(String type, IEventListener listener)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typ | String | En skiftlägeskänslig String som representerar händelsetypen att lyssna på. |
| lyssnare | IEventListener | Tar ett gränssnitt som implementeras av användaren och som innehåller de metoder som ska anropas när händelsen inträffar. |

## Anmärkningar

Om en läggs till i en medan den bearbetar en händelse, kommer den inte att triggas av de aktuella åtgärderna men kan triggas under ett senare steg i händelseflödet, såsom bubbelfasen. Om flera identiska Event Listeners registreras på samma med samma parametrar så kasseras dubblettinstanserna. De orsakar inte att den anropas två gånger och eftersom de kasseras behöver de inte tas bort med metoden.

### Se även

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener, bool) {#addeventlistener_1}

EventTarget‑metoden addEventListener() ställer in en funktion som kommer att anropas varje gång den specificerade händelsen levereras till målet.

Vanliga mål är Element, Document och Window, men målet kan vara vilket objekt som helst som stödjer händelser (t.ex. XMLHttpRequest).

```java
public void AddEventListener(String type, IEventListener listener, bool useCapture)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typ | String | En skiftlägeskänslig String som representerar händelsetypen att lyssna på. |
| lyssnare | IEventListener | Tar ett gränssnitt som implementeras av användaren och som innehåller de metoder som ska anropas när händelsen inträffar. |
| useCapture | Boolean | Om true, indikerar useCapture att användaren vill initiera fångst. Efter att fångst initierats kommer alla händelser av den angivna typen att skickas till de registrerade innan de skickas till några Event Targets under dem i trädet. Händelser som bubblar uppåt genom trädet kommer inte att trigga en utsedd att använda fångst. |

## Anmärkningar

Om en läggs till i en medan den bearbetar en händelse, kommer den inte att triggas av de aktuella åtgärderna men kan triggas under ett senare steg i händelseflödet, såsom bubbelfasen. Om flera identiska Event Listeners registreras på samma med samma parametrar så kasseras dubblettinstanserna. De orsakar inte att den anropas två gånger och eftersom de kasseras behöver de inte tas bort med metoden.

### Se även

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
