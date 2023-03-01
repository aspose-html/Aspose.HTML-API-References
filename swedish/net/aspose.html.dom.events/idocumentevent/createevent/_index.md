---
title: IDocumentEvent.CreateEvent
second_title: Aspose.HTML för .NET API Referens
description: IDocumentEvent metod. Skapar enEvent av en typ som stöds av implementeringen.
type: docs
weight: 10
url: /sv/net/aspose.html.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

Skapar en[`Event`](../../event/) av en typ som stöds av implementeringen.

```csharp
public Event CreateEvent(string eventType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| eventType | String | EventType-parametern anger typen av[`Event`](../../event/) gränssnitt som ska skapas.  Om[`Event`](../../event/)det angivna gränssnittet stöds av implementeringen denna metod kommer att returnera en new [`Event`](../../event/) av den begärda gränssnittstypen. Om[`Event`](../../event/)ska skickas via[`DispatchEvent`](../../../aspose.html.dom/eventtarget/dispatchevent/) metod lämplig [`InitEvent`](../../event/initevent/) metoden måste anropas efter skapandet för att initiera[`Event`](../../event/) s värden. |

### Returvärde

Den nyskapade[`Event`](../../event/)

### Undantag

| undantag | skick |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Ökas om implementeringen inte stöder typen av[`Event`](../../event/) gränssnitt begärt |

### Se även

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* namnutrymme [Aspose.Html.Dom.Events](../../idocumentevent/)
* hopsättning [Aspose.HTML](../../../)


