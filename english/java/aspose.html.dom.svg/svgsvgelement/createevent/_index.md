---
title: SVGSVGElement.CreateEvent
second_title: Aspose.HTML for Java API Reference
description: SVGSVGElement method. Creates an Event of a type supported by the implementation
type: docs
weight: 110
url: /java/com.aspose.html.dom.svg/svgsvgelement/createevent/
---
## SVGSVGElement.CreateEvent method

Creates an [`Event`](../../../com.aspose.html.dom.events/event/) of a type supported by the implementation.

```java
public Event CreateEvent(String eventType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| eventType | String | The eventType parameter specifies the type of [`Event`](../../../com.aspose.html.dom.events/event/) interface to be created.If the [`Event`](../../../com.aspose.html.dom.events/event/) interface specified is supported by the implementation this method will return a new[`Event`](../../../com.aspose.html.dom.events/event/) of the interface type requested. If the [`Event`](../../../com.aspose.html.dom.events/event/) is to be dispatched via the [`DispatchEvent`](../../../com.aspose.html.dom/eventtarget/dispatchevent/) method the appropriate[`InitEvent`](../../../com.aspose.html.dom.events/event/initevent/) method must be called after creation in order to initialize the [`Event`](../../../com.aspose.html.dom.events/event/)'s values. |

### Return Value

The newly created [`Event`](../../../com.aspose.html.dom.events/event/)

### Exceptions

| exception | condition |
| --- | --- |
| [dOMException](../../../com.aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Raised if the implementation does not support the type of [`Event`](../../../com.aspose.html.dom.events/event/) interface requested |

### See Also

* class [Event](../../../com.aspose.html.dom.events/event/)
* class [SVGSVGElement](../)
* package [com.aspose.html.Dom.Svg](../../svgsvgelement/)
* package [Aspose.HTML](../../../)
