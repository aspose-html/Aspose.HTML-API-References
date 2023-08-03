---
title: EventTarget.RemoveEventListener
second_title: Aspose.HTML for Java API Reference
description: EventTarget method. This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event it will not be triggered by the current actions. Event Listeners can never be invoked after being removed
type: docs
weight: 40
url: /net/com.aspose.html.dom/eventtarget/removeeventlistener/
---
## RemoveEventListener(String, DOMEventHandler, bool) {#removeeventlistener}

This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed.

```java
public void RemoveEventListener(String type, DOMEventHandler handler, bool useCapture)
```

| Parameter | Type | Description |
| --- | --- | --- |
| type | String | Specifies the event type of the being removed. |
| handler | DOMEventHandler | The parameter indicates the to be removed. |
| useCapture | Boolean | Specifies whether the EventListener being removed was registered as a capturing listener or not. If a listener was registered twice, one with capture and one without, each must be removed separately. Removal of a capturing listener does not affect a non-capturing version of the same listener, and vice versa. |

### See Also

* delegate [DOMEventHandler](../../../com.aspose.html.dom.events/domeventhandler/)
* class [EventTarget](../)
* package [com.aspose.html.Dom](../../eventtarget/)
* package [Aspose.HTML](../../../)

---

## RemoveEventListener(String, IEventListener) {#removeeventlistener_1}

This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed.

```java
public void RemoveEventListener(String type, IEventListener listener)
```

| Parameter | Type | Description |
| --- | --- | --- |
| type | String | Specifies the event type of the being removed. |
| listener | IEventListener | The parameter indicates the to be removed. |

### See Also

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.Dom](../../eventtarget/)
* package [Aspose.HTML](../../../)

---

## RemoveEventListener(String, IEventListener, bool) {#removeeventlistener_2}

This method allows the removal of event listeners from the event target. If an is removed from an while it is processing an event, it will not be triggered by the current actions. Event Listeners can never be invoked after being removed.

```java
public void RemoveEventListener(String type, IEventListener listener, bool useCapture)
```

| Parameter | Type | Description |
| --- | --- | --- |
| type | String | Specifies the event type of the being removed. |
| listener | IEventListener | The parameter indicates the to be removed. |
| useCapture | Boolean | Specifies whether the EventListener being removed was registered as a capturing listener or not. If a listener was registered twice, one with capture and one without, each must be removed separately. Removal of a capturing listener does not affect a non-capturing version of the same listener, and vice versa. |

### See Also

* interface [IEventListener](../../../com.aspose.html.dom.events/ieventlistener/)
* class [EventTarget](../)
* package [com.aspose.html.Dom](../../eventtarget/)
* package [Aspose.HTML](../../../)
