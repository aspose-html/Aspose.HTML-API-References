---
title: EventTarget.RemoveEventListener
second_title: Aspose.HTML for .NET API Reference
description: EventTarget RemoveEventListener method. This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event it will not be triggered by the current actions. Event Listeners can never be invoked after being removed
type: docs
weight: 50
url: /net/aspose.html.dom/eventtarget/removeeventlistener/
---
## RemoveEventListener(*string, [DOMEventHandler](../../../aspose.html.dom.events/domeventhandler/), bool*) {#removeeventlistener}

This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed.

```csharp
public void RemoveEventListener(string type, DOMEventHandler handler, bool useCapture)
```

| Parameter | Type | Description |
| --- | --- | --- |
| type | String | Specifies the event type of the being removed. |
| handler | DOMEventHandler | The parameter indicates the to be removed. |
| useCapture | Boolean | Specifies whether the EventListener being removed was registered as a capturing listener or not. If a listener was registered twice, one with capture and one without, each must be removed separately. Removal of a capturing listener does not affect a non-capturing version of the same listener, and vice versa. |

### See Also

* delegate [DOMEventHandler](../../../aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* namespace [Aspose.Html.Dom](../../../aspose.html.dom/)
* assembly [Aspose.HTML](../../../)

---

## RemoveEventListener(*string, [IEventListener](../../../aspose.html.dom.events/ieventlistener/)*) {#removeeventlistener_1}

This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed.

```csharp
public void RemoveEventListener(string type, IEventListener listener)
```

| Parameter | Type | Description |
| --- | --- | --- |
| type | String | Specifies the event type of the being removed. |
| listener | IEventListener | The parameter indicates the to be removed. |

### See Also

* interface [IEventListener](../../../aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* namespace [Aspose.Html.Dom](../../../aspose.html.dom/)
* assembly [Aspose.HTML](../../../)

---

## RemoveEventListener(*string, [IEventListener](../../../aspose.html.dom.events/ieventlistener/), bool*) {#removeeventlistener_2}

This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed.

```csharp
public void RemoveEventListener(string type, IEventListener listener, bool useCapture)
```

| Parameter | Type | Description |
| --- | --- | --- |
| type | String | Specifies the event type of the being removed. |
| listener | IEventListener | The parameter indicates the to be removed. |
| useCapture | Boolean | Specifies whether the EventListener being removed was registered as a capturing listener or not. If a listener was registered twice, one with capture and one without, each must be removed separately. Removal of a capturing listener does not affect a non-capturing version of the same listener, and vice versa. |

### See Also

* interface [IEventListener](../../../aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* namespace [Aspose.Html.Dom](../../../aspose.html.dom/)
* assembly [Aspose.HTML](../../../)
