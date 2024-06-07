---
title: create_event method
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 70
url: /aspose.html.dom.svg/svgsvgelement/create_event/
is_root: false
---

## create_event {#str}

Creates an [`Event`](/html/python-net/aspose.html.dom.events/event) of a type supported by the implementation.


### Returns 


The newly created [`Event`](/html/python-net/aspose.html.dom.events/event)


```python
def create_event(self, event_type):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| event_type | str | The eventType parameter specifies the type of [`Event`](/html/python-net/aspose.html.dom.events/event) interface to be created.<br/><br/>If the [`Event`](/html/python-net/aspose.html.dom.events/event) interface specified is supported by the implementation this method will return a new<br/>[`Event`](/html/python-net/aspose.html.dom.events/event) of the interface type requested.<br/>If the [`Event`](/html/python-net/aspose.html.dom.events/event) is to be dispatched via the [`EventTarget.dispatch_event`](/html/python-net/aspose.html.dom/eventtarget/dispatch_event) method the appropriate<br/>[`Event.init_event`](/html/python-net/aspose.html.dom.events/event/init_event) method must be called after creation in order to initialize the [`Event`](/html/python-net/aspose.html.dom.events/event)'s values.<br/><br/><br/>The [`IDocumentEvent.create_event`](/html/python-net/aspose.html.dom.events/idocumentevent/create_event) method is used in creating [`Event`](/html/python-net/aspose.html.dom.events/event)s when it is either inconvenient<br/>or unnecessary for the user to create an [`Event`](/html/python-net/aspose.html.dom.events/event) themselves.<br/>In cases where the implementation provided [`Event`](/html/python-net/aspose.html.dom.events/event) is insufficient, users may supply their own<br/>[`Event`](/html/python-net/aspose.html.dom.events/event) implementations for use with the [`EventTarget.dispatch_event`](/html/python-net/aspose.html.dom/eventtarget/dispatch_event) method. |
### Exceptions
| Exception | Description |
| :- | :- |
| [`DOMException`](/html/python-net/aspose.html.dom/domexception) | NOT_SUPPORTED_ERR: Raised if the implementation does not support the type of [`Event`](/html/python-net/aspose.html.dom.events/event) interface requested |





### See Also
* module [`aspose.html.dom.svg`](../../)
* class [`DOMException`](/html/python-net/aspose.html.dom/domexception)
* class [`Event`](/html/python-net/aspose.html.dom.events/event)
* class [`SVGSVGElement`](/html/python-net/aspose.html.dom.svg/svgsvgelement)
