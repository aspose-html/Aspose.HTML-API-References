---
title: "EventTarget.DispatchEvent"
second_title: "Aspose.HTML för Java API-referens"
description: "EventTarget-metod. Skickar ett Event till det angivna EventTarget synkront och anropar de påverkade EventListeners i rätt ordning. De vanliga händelsebehandlingsreglerna, inklusive fångst- och valfri bubbelfas, gäller även för händelser som skickas manuellt med dispatchEvent."
type: docs

url: /sv/java/com.aspose.html.dom/eventtarget/dispatchevent/
---
## EventTarget.DispatchEvent method

Skickar ett Event till det angivna [`EventTarget`](../../../com.aspose.html.dom.events/ieventtarget/), (synkront) och anropar de påverkade EventListeners i rätt ordning. De vanliga händelsebehandlingsreglerna (inklusive fångst- och valfri bubbelfas) gäller även för händelser som skickas manuellt med [`dispatchEvent()`](../../../com.aspose.html.dom.events/ieventtarget/dispatchevent/).

```java
public bool DispatchEvent(Event @event)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| händelse | Händelse | Anger händelsetypen, beteendet och kontextuell information som ska användas vid bearbetning av händelsen. |

### Returvärde

Returvärdet indikerar om någon av lyssnarna som hanterade händelsen anropades. Om den anropades är värdet falskt, annars är värdet sant.

### Undantag

| undantag | villkor |
| --- | --- |
| [dOMException](../../domexception/) |  |

## Anmärkningar

Händelser som skickas på detta sätt får samma fångst‑ och bubbelförlopp som händelser som skickas direkt av implementationen. Målet för händelsen är den på vilken som anropas.

### Se även

* class [Event](../../../com.aspose.html.dom.events/event/)
* class [EventTarget](../)
* package [com.aspose.html.dom](../../../com.aspose.html.dom/)
* package [Aspose.HTML](../../../)
