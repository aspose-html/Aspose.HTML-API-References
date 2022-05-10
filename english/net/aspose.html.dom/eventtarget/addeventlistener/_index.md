---
title: AddEventListener
second_title: Aspose.HTML for .NET API Reference
description: 
type: docs
weight: 10
url: /net/aspose.html.dom/eventtarget/addeventlistener/
---
## EventTarget.AddEventListener method (1 of 3)

This method allows the registration of event listeners on the event target.

```csharp
public void AddEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| Parameter | Type | Description |
| --- | --- | --- |
| type | String | The event type for which the user is registering |
| handler | DOMEventHandler | Takes an [`DOMEventHandler`](../../../aspose.html.dom.events/domeventhandler) to be called when the event occurs. |
| useCapture | Boolean | If true, useCapture indicates that the user wishes to initiate capture. After initiating capture, all events of the specified type will be dispatched to the registered [`IEventListener`](../../../aspose.html.dom.events/ieventlistener) before being dispatched to any Event Targets beneath them in the tree. Events which are bubbling upward through the tree will not trigger an [`IEventListener`](../../../aspose.html.dom.events/ieventlistener) designated to use capture. |

### Remarks

If an [`IEventListener`](../../../aspose.html.dom.events/ieventlistener) is added to an [`EventTarget`](../../eventtarget) while it is processing an event, it will not be triggered by the current actions but may be triggered during a later stage of event flow, such as the bubbling phase.

If multiple identical Event Listeners are registered on the same [`EventTarget`](../../eventtarget) with the same parameters the duplicate instances are discarded. They do not cause the [`IEventListener`](../../../aspose.html.dom.events/ieventlistener) to be called twice and since they are discarded they do not need to be removed with the [`RemoveEventListener`](../removeeventlistener) method.

### See Also

* delegate [DOMEventHandler](../../../aspose.html.dom.events/domeventhandler)
* class [EventTarget](../../eventtarget)
* namespace [Aspose.Html.Dom](../../eventtarget)
* assembly [Aspose.HTML](../../../)

---

## EventTarget.AddEventListener method (2 of 3)

This method allows the registration of event listeners on the event target.

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| Parameter | Type | Description |
| --- | --- | --- |
| type | String | The event type for which the user is registering |
| listener | IEventListener | Takes an interface implemented by the user which contains the methods to be called when the event occurs. |

### Remarks

If an [`IEventListener`](../../../aspose.html.dom.events/ieventlistener) is added to an [`EventTarget`](../../eventtarget) while it is processing an event, it will not be triggered by the current actions but may be triggered during a later stage of event flow, such as the bubbling phase.

If multiple identical Event Listeners are registered on the same [`EventTarget`](../../eventtarget) with the same parameters the duplicate instances are discarded. They do not cause the [`IEventListener`](../../../aspose.html.dom.events/ieventlistener) to be called twice and since they are discarded they do not need to be removed with the [`RemoveEventListener`](../removeeventlistener) method.

### See Also

* interface [IEventListener](../../../aspose.html.dom.events/ieventlistener)
* class [EventTarget](../../eventtarget)
* namespace [Aspose.Html.Dom](../../eventtarget)
* assembly [Aspose.HTML](../../../)

---

## EventTarget.AddEventListener method (3 of 3)

This method allows the registration of event listeners on the event target.

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| Parameter | Type | Description |
| --- | --- | --- |
| type | String | The event type for which the user is registering |
| listener | IEventListener | Takes an interface implemented by the user which contains the methods to be called when the event occurs. |
| useCapture | Boolean | If true, useCapture indicates that the user wishes to initiate capture. After initiating capture, all events of the specified type will be dispatched to the registered [`IEventListener`](../../../aspose.html.dom.events/ieventlistener) before being dispatched to any Event Targets beneath them in the tree. Events which are bubbling upward through the tree will not trigger an [`IEventListener`](../../../aspose.html.dom.events/ieventlistener) designated to use capture. |

### Remarks

If an [`IEventListener`](../../../aspose.html.dom.events/ieventlistener) is added to an [`EventTarget`](../../eventtarget) while it is processing an event, it will not be triggered by the current actions but may be triggered during a later stage of event flow, such as the bubbling phase.

If multiple identical Event Listeners are registered on the same [`EventTarget`](../../eventtarget) with the same parameters the duplicate instances are discarded. They do not cause the [`IEventListener`](../../../aspose.html.dom.events/ieventlistener) to be called twice and since they are discarded they do not need to be removed with the [`RemoveEventListener`](../removeeventlistener) method.

### See Also

* interface [IEventListener](../../../aspose.html.dom.events/ieventlistener)
* class [EventTarget](../../eventtarget)
* namespace [Aspose.Html.Dom](../../eventtarget)
* assembly [Aspose.HTML](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.HTML.dll -->
