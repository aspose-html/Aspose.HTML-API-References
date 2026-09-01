---
title: "IEventTarget.DispatchEvent"
second_title: "Aspose.HTML för Java API-referens"
description: "IEventTarget‑metod. Skickar ett Event till den angivna EventTarget synkront och anropar de påverkade EventListeners i rätt ordning. De normala händelsebehandlingsreglerna, inklusive capture‑ och valfri bubbling‑fas, gäller också för händelser som skickas manuellt med dispatchEvent."
type: docs

url: /sv/java/com.aspose.html.dom.events/ieventtarget/dispatchevent/
---
## IEventTarget.DispatchEvent method

Skickar en händelse till det specificerade EventTarget, (synkront) och anropar de berörda Event‑lyssnarna i rätt ordning. De vanliga händelsebehandlingsreglerna (inklusive fångst‑ och valfri bubbelfas) gäller även för händelser som skickas manuellt med dispatchEvent().

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
| [dOMException](../../../com.aspose.html.dom/domexception/) | Undantag som kastas av händelsehanterare rapporteras som okontrollerade undantag. Händelsehanterarna körs på en nästlad anropsstack; de blockerar anroparen tills de är klara, men undantag sprider sig inte till anroparen. |

## Anmärkningar

Händelser som skickas på detta sätt kommer att ha samma capture‑ och bubbling‑beteende som händelser som skickas direkt av implementationen. Målet för händelsen är den on som anropas.

### Se även

* class [Event](../../event/)
* interface [IEventTarget](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
