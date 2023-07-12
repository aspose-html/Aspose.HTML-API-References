---
title: IEventTarget.AddEventListener
second_title: Aspose.HTML for .NET API Reference
description: IEventTarget method. The EventTarget method addEventListener sets up a function that will be called whenever the specified event is delivered to the target
type: docs
weight: 10
url: /net/aspose.html.dom.events/ieventtarget/addeventlistener/
---
## AddEventListener(string, IEventListener) {#addeventlistener}

The EventTarget method addEventListener() sets up a function that will be called whenever the specified event is delivered to the target.

Common targets are Element, Document, and Window, but the target may be any object that supports events (such as XMLHttpRequest).

```csharp
public void AddEventListener(string type, IEventListener listener)
```

| Parameter | Type | Description |
| --- | --- | --- |
| type | String | A case-sensitive string representing the event type to listen for. |
| listener | IEventListener | Takes an interface implemented by the user which contains the methods to be called when the event occurs. |

## Remarks

If an is added to an while it is processing an event, it will not be triggered by the current actions but may be triggered during a later stage of event flow, such as the bubbling phase. If multiple identical Event Listeners are registered on the same with the same parameters the duplicate instances are discarded. They do not cause the to be called twice and since they are discarded they do not need to be removed with the method.

### See Also

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namespace [Aspose.Html.Dom.Events](../../ieventtarget/)
* assembly [Aspose.HTML](../../../)

---

## AddEventListener(string, IEventListener, bool) {#addeventlistener_1}

The EventTarget method addEventListener() sets up a function that will be called whenever the specified event is delivered to the target.

Common targets are Element, Document, and Window, but the target may be any object that supports events (such as XMLHttpRequest).

```csharp
public void AddEventListener(string type, IEventListener listener, bool useCapture)
```

| Parameter | Type | Description |
| --- | --- | --- |
| type | String | A case-sensitive string representing the event type to listen for. |
| listener | IEventListener | Takes an interface implemented by the user which contains the methods to be called when the event occurs. |
| useCapture | Boolean | If true, useCapture indicates that the user wishes to initiate capture. After initiating capture, all events of the specified type will be dispatched to the registered before being dispatched to any Event Targets beneath them in the tree. Events which are bubbling upward through the tree will not trigger an designated to use capture. |

## Remarks

If an is added to an while it is processing an event, it will not be triggered by the current actions but may be triggered during a later stage of event flow, such as the bubbling phase. If multiple identical Event Listeners are registered on the same with the same parameters the duplicate instances are discarded. They do not cause the to be called twice and since they are discarded they do not need to be removed with the method.

### See Also

* interface [IEventListener](../../ieventlistener/)
* interface [IEventTarget](../)
* namespace [Aspose.Html.Dom.Events](../../ieventtarget/)
* assembly [Aspose.HTML](../../../)
