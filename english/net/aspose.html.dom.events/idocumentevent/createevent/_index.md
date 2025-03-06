---
title: IDocumentEvent.CreateEvent
second_title: Aspose.HTML for .NET API Reference
description: IDocumentEvent CreateEvent method. The createEvent method is used in creating Events when it is either inconvenient or unnecessary for the user to create an Event themselves
type: docs
weight: 10
url: /net/aspose.html.dom.events/idocumentevent/createevent/
---
## IDocumentEvent.CreateEvent method

The createEvent method is used in creating Events when it is either inconvenient or unnecessary for the user to create an Event themselves

```csharp
public Event CreateEvent(string eventType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| eventType | String | The eventType parameter specifies the type of interface to be created. If the interface specified is supported by the implementation this method will return a new of the interface type requested. If the is to be dispatched via the method the appropriate method must be called after creation in order to initialize the values. The method is used in creating s when it is either inconvenient or unnecessary for the user to create an themselves. In cases where the implementation provided is insufficient, users may supply their own implementations for use with the method. |

### Return Value

Returns the newly created event of the specified event type.

### Exceptions

| exception | condition |
| --- | --- |
| [DOMException](../../../aspose.html.dom/domexception/) | NOT_SUPPORTED_ERR: Raised if theimplementation does not support the type of interface requested |

### See Also

* class [Event](../../event/)
* interface [IDocumentEvent](../)
* namespace [Aspose.Html.Dom.Events](../../../aspose.html.dom.events/)
* assembly [Aspose.HTML](../../../)
