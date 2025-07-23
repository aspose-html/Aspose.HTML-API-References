---
title: IEventTarget.AddEventListener
second_title: Aspose.HTML for .NET API Reference
description: IEventTarget AddEventListener method. This method allows the registration of event listeners on the event target
type: docs
weight: 10
url: /net/aspose.html.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(*string, [IEventListener](../../ieventlistener/)*) {#addeventlistener}

This method allows the registration of event listeners on the event target.

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| Parameter | Type | Description |
| --- | --- | --- |
| type | String | The event type for which the user is registering |
| listener | IEventListener | Takes an interface implemented by the user which contains the methods to be called when the event occurs. |

## Remarks

If an [`IEventListener`](../../ieventlistener/) is added to an [`EventTarget`](../../../aspose.html.dom/eventtarget/) while it is processing an event, it will not be triggered by the current actions but may be triggered during a later stage of event flow, such as the bubbling phase.

If multiple identical Event Listeners are registered on the same [`EventTarget`](../../../aspose.html.dom/eventtarget/) with the same parameters the duplicate instances are discarded. They do not cause the [`IEventListener`](../../ieventlistener/) to be called twice and since they are discarded they do not need to be removed with the [`RemoveEventListener`](../removeeventlistener/) method.

### See Also

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namespace [Aspose.Html.Dom.Events](../../../aspose.html.dom.events/)
* assembly [Aspose.HTML](../../../)

---

## AddEventListener(*string, [IEventListener](../../ieventlistener/), bool*) {#addeventlistener_1}

This method allows the registration of event listeners on the event target.

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| Parameter | Type | Description |
| --- | --- | --- |
| type | String | The event type for which the user is registering |
| listener | IEventListener | Takes an interface implemented by the user which contains the methods to be called when the event occurs. |
| useCapture | Boolean | If true, useCapture indicates that the user wishes to initiate capture. After initiating capture, all events of the specified type will be dispatched to the registered [`IEventListener`](../../ieventlistener/) before being dispatched to any Event Targets beneath them in the tree. Events which are bubbling upward through the tree will not trigger an [`IEventListener`](../../ieventlistener/) designated to use capture. |

## Remarks

If an [`IEventListener`](../../ieventlistener/) is added to an [`EventTarget`](../../../aspose.html.dom/eventtarget/) while it is processing an event, it will not be triggered by the current actions but may be triggered during a later stage of event flow, such as the bubbling phase.

If multiple identical Event Listeners are registered on the same [`EventTarget`](../../../aspose.html.dom/eventtarget/) with the same parameters the duplicate instances are discarded. They do not cause the [`IEventListener`](../../ieventlistener/) to be called twice and since they are discarded they do not need to be removed with the [`RemoveEventListener`](../removeeventlistener/) method.

### See Also

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namespace [Aspose.Html.Dom.Events](../../../aspose.html.dom.events/)
* assembly [Aspose.HTML](../../../)
