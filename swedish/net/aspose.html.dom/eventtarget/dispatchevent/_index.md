---
title: EventTarget.DispatchEvent
second_title: Aspose.HTML för .NET API Referens
description: EventTarget metod. Denna metod tillåter sändning av händelser till implementeringshändelsemodellen.
type: docs
weight: 20
url: /sv/net/aspose.html.dom/eventtarget/dispatchevent/
---
## EventTarget.DispatchEvent method

Denna metod tillåter sändning av händelser till implementeringshändelsemodellen.

```csharp
public bool DispatchEvent(Event @event)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| event | Event | Anger händelsetyp, beteende och kontextuell information som ska användas vid bearbetning av händelsen. |

### Returvärde

Returvärdet för`DispatchEvent` indikerar om någon av lyssnarna som hanterade händelsen ringde[`PreventDefault`](../../../aspose.html.dom.events/event/preventdefault/) . Om[`PreventDefault`](../../../aspose.html.dom.events/event/preventdefault/) kallades värdet är falskt, annars är värdet sant.

### Undantag

| undantag | skick |
| --- | --- |
| [DOMException](../../domexception/) |  |

### Anmärkningar

Händelser som skickas på detta sätt kommer att ha samma uppfångande och bubblande beteende som händelser som skickas direkt av implementeringen. Målet för händelsen är[`EventTarget`](../) på vilken`DispatchEvent` heter.

### Se även

* class [Event](../../../aspose.html.dom.events/event/)
* class [EventTarget](../)
* namnutrymme [Aspose.Html.Dom](../../eventtarget/)
* hopsättning [Aspose.HTML](../../../)


