---
title: stop_propagation method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 60
url: /python-net/aspose.html.dom.events/keyboardevent/stop_propagation/
is_root: false
---

## stop_propagation {#}

The [`Event.stop_propagation`](/html/python-net/aspose.html.dom.events/event/stop_propagation) method is used prevent further propagation of an event during event flow.



```python
def stop_propagation(self):
    ...
```


### Remarks

If this method is called by any [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener) the event will cease propagating through the tree.
The event will complete dispatch to all listeners on the current [`IEventTarget`](/html/python-net/aspose.html.dom.events/ieventtarget) before event flow stops.
This method may be used during any stage of event flow.


### See Also
* module [`aspose.html.dom.events`](../../)
* class [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener)
* class [`IEventTarget`](/html/python-net/aspose.html.dom.events/ieventtarget)
* class [`KeyboardEvent`](/html/python-net/aspose.html.dom.events/keyboardevent)
