---
title: IDocumentEvent.CreateEvent
second_title: Aspose.HTML for .NET API Reference
description: IDocumentEvent CreateEvent method. Creates an Event of a type supported by the implementation
type: docs
weight: 10
url: /net/aspose.html.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

Creates an [`Event`](../../event/) of a type supported by the implementation.

```csharp
public Event CreateEvent(string eventType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| eventType | String | The eventType parameter specifies the type of [`Event`](../../event/) interface to be created.  If the [`Event`](../../event/) interface specified is supported by the implementation this method will return a new [`Event`](../../event/) of the interface type requested. If the [`Event`](../../event/) is to be dispatched via the [`DispatchEvent`](../../../aspose.html.dom/eventtarget/dispatchevent/) method the appropriate [`InitEvent`](../../event/initevent/) method must be called after creation in order to initialize the [`Event`](../../event/)'s values. |

### Return Value

The newly created [`Event`](../../event/)

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Raised if the implementation does not support the type of [`Event`](../../event/) interface requested |

### See Also

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* namespace [Aspose.Html.Dom.Events](../../../aspose.html.dom.events/)
* assembly [Aspose.HTML](../../../)
