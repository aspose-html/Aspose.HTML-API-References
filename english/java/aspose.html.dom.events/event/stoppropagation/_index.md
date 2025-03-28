---
title: Event.StopPropagation
second_title: Aspose.HTML for Java API Reference
description: Event method. The StopPropagation method is used prevent further propagation of an event during event flow
type: docs

url: /java/com.aspose.html.dom.events/event/stoppropagation/
---
## Event.StopPropagation method

The `StopPropagation` method is used prevent further propagation of an event during event flow.

```java
public void StopPropagation()
```

## Remarks

If this method is called by any [`IEventListener`](../../ieventlistener/) the event will cease propagating through the tree. The event will complete dispatch to all listeners on the current [`IEventTarget`](../../ieventtarget/) before event flow stops. This method may be used during any stage of event flow.

### See Also

* class [Event](../)
* package [com.aspose.html.dom.events](../../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../../)
