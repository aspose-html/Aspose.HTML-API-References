---
title: SVGSVGElement.CreateEvent
second_title: Aspose.HTML för .NET API Referens
description: SVGSVGElement metod. Skapar enEvent av en typ som stöds av implementeringen.
type: docs
weight: 110
url: /sv/net/aspose.html.dom.svg/svgsvgelement/createevent/
---
## SVGSVGElement.CreateEvent method

Skapar en[`Event`](../../../aspose.html.dom.events/event/) av en typ som stöds av implementeringen.

```csharp
public Event CreateEvent(string eventType)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| eventType | String | EventType-parametern anger typen av[`Event`](../../../aspose.html.dom.events/event/) gränssnitt som ska skapas.  Om[`Event`](../../../aspose.html.dom.events/event/)det angivna gränssnittet stöds av implementeringen denna metod kommer att returnera en new [`Event`](../../../aspose.html.dom.events/event/) av den begärda gränssnittstypen. Om[`Event`](../../../aspose.html.dom.events/event/)ska skickas via[`DispatchEvent`](../../../aspose.html.dom/eventtarget/dispatchevent/) metod lämplig [`InitEvent`](../../../aspose.html.dom.events/event/initevent/) metoden måste anropas efter skapandet för att initiera[`Event`](../../../aspose.html.dom.events/event/) s värden. |

### Returvärde

Den nyskapade[`Event`](../../../aspose.html.dom.events/event/)

### Undantag

| undantag | skick |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Ökas om implementeringen inte stöder typen av[`Event`](../../../aspose.html.dom.events/event/) gränssnitt begärt |

### Se även

* class [Event](../../../aspose.html.dom.events/event/)
* class [SVGSVGElement](../)
* namnutrymme [Aspose.Html.Dom.Svg](../../svgsvgelement/)
* hopsättning [Aspose.HTML](../../../)


