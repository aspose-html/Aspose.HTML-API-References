---
title: KeyboardEvent class
second_title: Aspose.HTML for Python via .NET API References
description: 
type: docs
weight: 100
url: /aspose.html.dom.events/keyboardevent/
is_root: false
---

## KeyboardEvent class

The KeyboardEvent interface provides specific contextual information associated with keyboard devices. Each keyboard event references a key using a value. Keyboard events are commonly directed at the element that has the focus.



**Inheritance:** [`KeyboardEvent`](/html/python-net/aspose.html.dom.events/keyboardevent) → 
[`UIEvent`](/html/python-net/aspose.html.dom.events/uievent) → 
[`Event`](/html/python-net/aspose.html.dom.events/event) → 
[`DOMObject`](/html/python-net/aspose.html.dom/domobject)



The KeyboardEvent type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/html/python-net/aspose.html.dom.events/keyboardevent/__init__/#str) | Initializes a new instance of the [`KeyboardEvent`](/html/python-net/aspose.html.dom.events/keyboardevent) class. |


### Properties
| Property | Description |
| :- | :- |
| [bubbles](/html/python-net/aspose.html.dom.events/keyboardevent/bubbles) | Used to indicate whether or not an event is a bubbling event. If the event can bubble the value is true, else the value is false. |
| [cancelable](/html/python-net/aspose.html.dom.events/keyboardevent/cancelable) | Used to indicate whether or not an event can have its default action prevented. If the default action can be prevented the value is true, else the value is false. |
| [current_target](/html/python-net/aspose.html.dom.events/keyboardevent/current_target) | Used to indicate the [`IEventTarget`](/html/python-net/aspose.html.dom.events/ieventtarget) whose [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener)s are currently being processed.<br/>This is particularly useful during capturing and bubbling. |
| [event_phase](/html/python-net/aspose.html.dom.events/keyboardevent/event_phase) | Used to indicate which phase of event flow is currently being evaluated. |
| [target](/html/python-net/aspose.html.dom.events/keyboardevent/target) | Used to indicate the [`IEventTarget`](/html/python-net/aspose.html.dom.events/ieventtarget) to which the event was originally dispatched. |
| [time_stamp](/html/python-net/aspose.html.dom.events/keyboardevent/time_stamp) | Used to specify the time (in milliseconds relative to the epoch) at which the event was created.<br/>Due to the fact that some systems may not provide this information the value of timeStamp may be not available for all events.<br/>When not available, a value of 0 will be returned.<br/>Examples of epoch time are the time of the system start or 0:0:0 UTC 1st January 1970. |
| [type](/html/python-net/aspose.html.dom.events/keyboardevent/type) | The name of the event (case-insensitive). The name must be an XML name. |
| [default_prevented](/html/python-net/aspose.html.dom.events/keyboardevent/default_prevented) | Returns true if preventDefault() was invoked while the cancelable attribute value is true, and false otherwise. |
| [is_trusted](/html/python-net/aspose.html.dom.events/keyboardevent/is_trusted) | The isTrusted attribute must return the value it was initialized to. When an event is created the attribute must be initialized to false. |
| [NONE_PHASE](/html/python-net/aspose.html.dom.events/keyboardevent/none_phase) | Events not currently dispatched are in this phase. |
| [CAPTURING_PHASE](/html/python-net/aspose.html.dom.events/keyboardevent/capturing_phase) | The event is currently being evaluated at the target [`IEventTarget`](/html/python-net/aspose.html.dom.events/ieventtarget). |
| [AT_TARGET_PHASE](/html/python-net/aspose.html.dom.events/keyboardevent/at_target_phase) | The current event phase is the capturing phase. |
| [BUBBLING_PHASE](/html/python-net/aspose.html.dom.events/keyboardevent/bubbling_phase) | The current event phase is the bubbling phase. |
| [view](/html/python-net/aspose.html.dom.events/keyboardevent/view) | The view attribute identifies the Window from which the event was generated.<br/>The un-initialized value of this attribute MUST be null. |
| [detail](/html/python-net/aspose.html.dom.events/keyboardevent/detail) | Specifies some detail information about the Event, depending on the type of event. |
| [key](/html/python-net/aspose.html.dom.events/keyboardevent/key) | The key holds the key value of the key pressed. If the value is has a printed representation, it MUST be a non-empty Unicode character string, conforming to the algorithm for determining the key value defined in this specification. If the value is a control key which has no printed representation, it MUST be one of the key values defined in the key values set, as determined by the algorithm for determining the key value. Implementations that are unable to identify a key MUST use the key value Unidentified. |
| [code](/html/python-net/aspose.html.dom.events/keyboardevent/code) | The code holds a string that identifies the physical key being pressed. The value is not affected by the current keyboard layout or modifier state, so a particular key will always return the same value. |
| [location](/html/python-net/aspose.html.dom.events/keyboardevent/location) | The location attribute contains an indication of the logical location of the key on the device. |
| [ctrl_key](/html/python-net/aspose.html.dom.events/keyboardevent/ctrl_key) | true if the Control (control) key modifier	was active.<br/>The un-initialized value of this attribute MUST be false. |
| [shift_key](/html/python-net/aspose.html.dom.events/keyboardevent/shift_key) | true if the shift (Shift) key modifier was	active. |
| [alt_key](/html/python-net/aspose.html.dom.events/keyboardevent/alt_key) | true if the Alt (alternative) (or "Option") key modifier was active. The un-initialized value of this attribute MUST be false. |
| [meta_key](/html/python-net/aspose.html.dom.events/keyboardevent/meta_key) | true if the meta (Meta) key modifier was active. |
| [repeat](/html/python-net/aspose.html.dom.events/keyboardevent/repeat) | true if the key has been pressed in a sustained manner. Holding down a key MUST result in the repeating the events keydown, beforeinput, input in this	order, at a rate determined by the system configuration. For mobile devices which have long-key-press behavior, the first key event with a repeat attribute value of true MUST serve as an indication of a long-key-press. The length of time that the key MUST be pressed in order to begin repeating is configuration-dependent. |
| [is_composing](/html/python-net/aspose.html.dom.events/keyboardevent/is_composing) | true if the key event occurs as part of a composition session, i.e., after a compositionstart event	and before the corresponding compositionend event. The un-initialized value of this attribute MUST be false. |
| [DOM_KEY_LOCATION_STANDARD](/html/python-net/aspose.html.dom.events/keyboardevent/dom_key_location_standard) | The key activation MUST NOT be distinguished as the left or right version of the key, and (other than the NumLock key) did not originate from the numeric keypad (or did not originate with a virtual key corresponding to the numeric keypad). |
| [DOM_KEY_LOCATION_LEFT](/html/python-net/aspose.html.dom.events/keyboardevent/dom_key_location_left) | The key activated originated from the left key location (when there is more than one possible location for this key). |
| [DOM_KEY_LOCATION_RIGHT](/html/python-net/aspose.html.dom.events/keyboardevent/dom_key_location_right) | The key activation originated from the right key location (when there is more than one possible location for this key). |
| [DOM_KEY_LOCATION_NUMPAD](/html/python-net/aspose.html.dom.events/keyboardevent/dom_key_location_numpad) | The key activation originated on the numeric keypad or with a virtual key corresponding to the numeric keypad (when there is more than one possible location for this key). Note that the NumLock key should always be encoded with a location of DOM_KEY_LOCATION_STANDARD. |


### Methods
| Method | Description |
| :- | :- |
| [get_platform_type](/html/python-net/aspose.html.dom.events/keyboardevent/get_platform_type/#) | This method is used to retrieve ECMAScript object Type. |
| [init_event](/html/python-net/aspose.html.dom.events/keyboardevent/init_event/#str-bool-bool) | The [`Event.init_event`](/html/python-net/aspose.html.dom.events/event/init_event) method is used to initialize the value of an [`Event`](/html/python-net/aspose.html.dom.events/event) created through the<br/>[`IDocumentEvent`](/html/python-net/aspose.html.dom.events/idocumentevent) interface. |
| [prevent_default](/html/python-net/aspose.html.dom.events/keyboardevent/prevent_default/#) | If an event is cancelable, the [`Event.prevent_default`](/html/python-net/aspose.html.dom.events/event/prevent_default) method is used to signify that the event is to be canceled,<br/>meaning any default action normally taken by the implementation as a result of the event will not occur. |
| [stop_propagation](/html/python-net/aspose.html.dom.events/keyboardevent/stop_propagation/#) | The [`Event.stop_propagation`](/html/python-net/aspose.html.dom.events/event/stop_propagation) method is used prevent further propagation of an event during event flow. |
| [stop_immediate_propagation](/html/python-net/aspose.html.dom.events/keyboardevent/stop_immediate_propagation/#) | Invoking this method prevents event from reaching any event listeners registered after the current one and when dispatched in a tree also prevents event from reaching any other objects. |



### See Also
* module [`aspose.html.dom.events`](..)
* class [`DOMObject`](/html/python-net/aspose.html.dom/domobject)
* class [`Event`](/html/python-net/aspose.html.dom.events/event)
* class [`IDocumentEvent`](/html/python-net/aspose.html.dom.events/idocumentevent)
* class [`IEventListener`](/html/python-net/aspose.html.dom.events/ieventlistener)
* class [`IEventTarget`](/html/python-net/aspose.html.dom.events/ieventtarget)
* class [`KeyboardEvent`](/html/python-net/aspose.html.dom.events/keyboardevent)
* class [`UIEvent`](/html/python-net/aspose.html.dom.events/uievent)
