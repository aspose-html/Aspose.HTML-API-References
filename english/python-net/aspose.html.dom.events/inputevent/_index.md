﻿---
title: InputEvent class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 90
url: /python-net/aspose.html.dom.events/inputevent/
is_root: false
---

## InputEvent class

Input events are sent as notifications whenever the DOM is being updated.



**Inheritance:** [`InputEvent`](/html/python-net/aspose.html.dom.events/inputevent) → 
[`UIEvent`](/html/python-net/aspose.html.dom.events/uievent) → 
[`Event`](/html/python-net/aspose.html.dom.events/event) → 
[`DOMObject`](/html/python-net/aspose.html.dom/domobject)



The InputEvent type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/html/python-net/aspose.html.dom.events/inputevent/__init__/#str) | Initializes a new instance of the [`InputEvent`](/html/python-net/aspose.html.dom.events/inputevent) class. |


### Properties
| Property | Description |
| :- | :- |
| [bubbles](/html/python-net/aspose.html.dom.events/inputevent/bubbles) | Used to indicate whether or not an event is a bubbling event. If the event can bubble the value is true, else the value is false. |
| [cancelable](/html/python-net/aspose.html.dom.events/inputevent/cancelable) | Used to indicate whether or not an event can have its default action prevented. If the default action can be prevented the value is true, else the value is false. |
| [current_target](/html/python-net/aspose.html.dom.events/inputevent/current_target) | Used to indicate the [`IEventTarget`](/html/python-net/aspose.html.dom.events/ieventtarget) whose [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener)s are currently being processed.
| [event_phase](/html/python-net/aspose.html.dom.events/inputevent/event_phase) | Used to indicate which phase of event flow is currently being evaluated. |
| [target](/html/python-net/aspose.html.dom.events/inputevent/target) | Used to indicate the [`IEventTarget`](/html/python-net/aspose.html.dom.events/ieventtarget) to which the event was originally dispatched. |
| [time_stamp](/html/python-net/aspose.html.dom.events/inputevent/time_stamp) | Used to specify the time (in milliseconds relative to the epoch) at which the event was created.
| [type](/html/python-net/aspose.html.dom.events/inputevent/type) | The name of the event (case-insensitive). The name must be an XML name. |
| [default_prevented](/html/python-net/aspose.html.dom.events/inputevent/default_prevented) | Returns true if preventDefault() was invoked while the cancelable attribute value is true, and false otherwise. |
| [is_trusted](/html/python-net/aspose.html.dom.events/inputevent/is_trusted) | The isTrusted attribute must return the value it was initialized to. When an event is created the attribute must be initialized to false. |
| [NONE_PHASE](/html/python-net/aspose.html.dom.events/inputevent/none_phase) | Events not currently dispatched are in this phase. |
| [CAPTURING_PHASE](/html/python-net/aspose.html.dom.events/inputevent/capturing_phase) | The event is currently being evaluated at the target [`IEventTarget`](/html/python-net/aspose.html.dom.events/ieventtarget). |
| [AT_TARGET_PHASE](/html/python-net/aspose.html.dom.events/inputevent/at_target_phase) | The current event phase is the capturing phase. |
| [BUBBLING_PHASE](/html/python-net/aspose.html.dom.events/inputevent/bubbling_phase) | The current event phase is the bubbling phase. |
| [view](/html/python-net/aspose.html.dom.events/inputevent/view) | The view attribute identifies the Window from which the event was generated.
| [detail](/html/python-net/aspose.html.dom.events/inputevent/detail) | Specifies some detail information about the Event, depending on the type of event. |
| [data](/html/python-net/aspose.html.dom.events/inputevent/data) | The data holds the value of the characters generated by an input method. This MAY be a single Unicode character or a non-empty sequence of Unicode characters [Unicode]. Characters SHOULD be normalized as defined by the Unicode normalization form NFC, defined in [UAX15]. This attribute MAY contain the empty string. |
| [is_composing](/html/python-net/aspose.html.dom.events/inputevent/is_composing) | true if the input event occurs as part of a composition session, i.e., after a compositionstart event and before the corresponding compositionend event. The un-initialized value of this attribute MUST be false. |


### Methods
| Method | Description |
| :- | :- |
| [get_platform_type](/html/python-net/aspose.html.dom.events/inputevent/get_platform_type/#) | This method is used to retrieve ECMAScript object Type. |
| [init_event](/html/python-net/aspose.html.dom.events/inputevent/init_event/#str-bool-bool) | The [`Event.init_event`](/html/python-net/aspose.html.dom.events/event/init_event) method is used to initialize the value of an [`Event`](/html/python-net/aspose.html.dom.events/event) created through the
| [prevent_default](/html/python-net/aspose.html.dom.events/inputevent/prevent_default/#) | If an event is cancelable, the [`Event.prevent_default`](/html/python-net/aspose.html.dom.events/event/prevent_default) method is used to signify that the event is to be canceled,
| [stop_propagation](/html/python-net/aspose.html.dom.events/inputevent/stop_propagation/#) | The [`Event.stop_propagation`](/html/python-net/aspose.html.dom.events/event/stop_propagation) method is used prevent further propagation of an event during event flow. |
| [stop_immediate_propagation](/html/python-net/aspose.html.dom.events/inputevent/stop_immediate_propagation/#) | Invoking this method prevents event from reaching any event listeners registered after the current one and when dispatched in a tree also prevents event from reaching any other objects. |



### See Also
* module [`aspose.html.dom.events`](..)
* class [`DOMObject`](/html/python-net/aspose.html.dom/domobject)
* class [`Event`](/html/python-net/aspose.html.dom.events/event)
* class [`IDocumentEvent`](/html/python-net/aspose.html.dom.events/idocumentevent)
* class [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener)
* class [`IEventTarget`](/html/python-net/aspose.html.dom.events/ieventtarget)
* class [`InputEvent`](/html/python-net/aspose.html.dom.events/inputevent)
* class [`UIEvent`](/html/python-net/aspose.html.dom.events/uievent)