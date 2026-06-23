---
title: "EventTarget.AddEventListener"
second_title: "Aspose.HTML för Java API-referens"
description: "EventTarget-metod. addEventListener-metoden i EventTarget-gränssnittet ställer in en funktion som kommer att anropas närhelst den angivna händelsen levereras till målet."
type: docs

url: /sv/java/com.aspose.html.dom/eventtarget/addeventlistener/
---
## AddEventListener(String, DOMEventHandler, bool) {#addeventlistener}

addEventListener()-metoden i [EventTarget ](T:com.aspose.html.dom.EventTarget)gränssnittet ställer in en funktion som kommer att anropas när den specificerade händelsen levereras till målet.

Det fungerar genom att lägga till en funktion eller ett objekt som implementerar [EventListener](T:com.aspose.html.dom.events.IEventListener) i listan över händelselyssnare för den angivna händelsetypen på det EventTarget där den anropas. Om funktionen eller objektet redan finns i listan över händelselyssnare för detta mål, läggs de inte till en andra gång.

```java
public void AddEventListener(String type, DOMEventHandler handler, bool useCapture)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typ | String | Händelsetypen som användaren registrerar sig för |
| hanterare | DOMEventHandler | Tar emot en funktion som ska anropas när händelsen inträffar. |
| useCapture | Boolean | Om true, useCapture indikerar att användaren vill initiera capture. Efter att capture har initierats kommer alla händelser av den angivna typen att skickas till de registrerade innan de skickas till någon Event Target under dem i trädet. Händelser som bubblar uppåt genom trädet kommer inte att trigga en angiven att använda capture. |

## Anmärkningar

Om en lyssnare läggs till en lyssnare medan den bearbetar en händelse, kommer den inte att triggas av de aktuella åtgärderna men kan triggas under ett senare steg i händelseflödet, såsom bubbling‑fasen. Om flera identiska Event Listeners registreras på samma objekt med samma parametrar, kasseras de duplicerade instanserna. De orsakar inte att lyssnaren anropas två gånger och eftersom de kasseras behöver de inte tas bort med metoden.

### Se även

* delegate [DOMEventHandler](../../../com.aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener) {#addeventlistener_1}

addEventListener()-metoden i [`EventTarget `](../)-gränssnittet ställer in en funktion som kommer att anropas närhelst den angivna händelsen levereras till målet.

Det fungerar genom att lägga till en funktion eller ett objekt som implementerar [`EventListener`](../../../com.aspose.html.dom.events/ieventlistener/) i listan över händelselyssnare för den angivna händelsetypen på det EventTarget där den anropas. Om funktionen eller objektet redan finns i listan över händelselyssnare för detta mål, läggs de inte till en andra gång.

```java
public void AddEventListener(String type, IEventListener listener)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typ | String | Händelsetypen som användaren registrerar sig för |
| lyssnare | IEventListener | Tar ett gränssnitt som implementeras av användaren och som innehåller metoderna som ska anropas när händelsen inträffar. |

## Anmärkningar

Om en lyssnare läggs till en lyssnare medan den bearbetar en händelse, kommer den inte att triggas av de aktuella åtgärderna men kan triggas under ett senare steg i händelseflödet, såsom bubbling‑fasen. Om flera identiska Event Listeners registreras på samma objekt med samma parametrar, kasseras de duplicerade instanserna. De orsakar inte att lyssnaren anropas två gånger och eftersom de kasseras behöver de inte tas bort med metoden.

### Se även

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)

---

## AddEventListener(String, IEventListener, bool) {#addeventlistener_2}

addEventListener()-metoden i [EventTarget ](T:com.aspose.html.dom.EventTarget)gränssnittet ställer in en funktion som kommer att anropas när den specificerade händelsen levereras till målet.

Det fungerar genom att lägga till en funktion eller ett objekt som implementerar [EventListener](T:com.aspose.html.dom.events.IEventListener) i listan över händelselyssnare för den angivna händelsetypen på det EventTarget där den anropas. Om funktionen eller objektet redan finns i listan över händelselyssnare för detta mål, läggs de inte till en andra gång.

```java
public void AddEventListener(String type, IEventListener listener, bool useCapture)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| typ | String | Händelsetypen som användaren registrerar sig för |
| lyssnare | IEventListener | Tar ett gränssnitt som implementeras av användaren och som innehåller metoderna som ska anropas när händelsen inträffar. |
| useCapture | Boolean | Om true, useCapture indikerar att användaren vill initiera capture. Efter att capture har initierats kommer alla händelser av den angivna typen att skickas till de registrerade innan de skickas till någon Event Target under dem i trädet. Händelser som bubblar uppåt genom trädet kommer inte att trigga en angiven att använda capture. |

## Anmärkningar

Om en lyssnare läggs till en lyssnare medan den bearbetar en händelse, kommer den inte att triggas av de aktuella åtgärderna men kan triggas under ett senare steg i händelseflödet, såsom bubbling‑fasen. Om flera identiska Event Listeners registreras på samma objekt med samma parametrar, kasseras de duplicerade instanserna. De orsakar inte att lyssnaren anropas två gånger och eftersom de kasseras behöver de inte tas bort med metoden.

### Se även

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
