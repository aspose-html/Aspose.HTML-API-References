---
title: IEventTarget.DispatchEvent
second_title: Aspose.HTML för .NET API Referens
description: IEventTarget metod. Denna metod tillåter sändning av händelser till implementeringshändelsemodellen.
type: docs
weight: 20
url: /sv/net/aspose.html.dom.events/ieventtarget/dispatchevent/
---
## IEventTarget.DispatchEvent method

Denna metod tillåter sändning av händelser till implementeringshändelsemodellen.

```csharp
public bool DispatchEvent(Event @event)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| event | Event | Anger händelsetyp, beteende och kontextuell information som ska användas vid bearbetning av händelsen. |

### Returvärde

Returvärdet för[`DispatchEvent`](../../../aspose.html.dom/eventtarget/dispatchevent/) indikerar om någon av lyssnarna som hanterade händelsen ringde[`PreventDefault`](../../event/preventdefault/) . Om[`PreventDefault`](../../event/preventdefault/) kallades värdet är falskt, annars är värdet sant.

### Undantag

| undantag | skick |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) |  |

### Anmärkningar

Händelser som skickas på detta sätt kommer att ha samma uppfångande och bubblande beteende som händelser som skickas direkt av implementeringen. Målet för händelsen är[`EventTarget`](../../../aspose.html.dom/eventtarget/) på vilken[`DispatchEvent`](../../../aspose.html.dom/eventtarget/dispatchevent/) heter.

### Se även

* class [Event](../../event/)
* interface [IEventTarget](../)
* namnutrymme [Aspose.Html.Dom.Events](../../ieventtarget/)
* hopsättning [Aspose.HTML](../../../)


