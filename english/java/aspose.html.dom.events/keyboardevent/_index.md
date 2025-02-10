---
title: KeyboardEvent Class
second_title: Aspose.HTML for Java API Reference
description: com.aspose.html.dom.events.KeyboardEvent class. The KeyboardEvent interface provides specific contextual information associated with keyboard devices. Each keyboard event references a key using a value. Keyboard events are commonly directed at the element that has the focus
type: docs

url: /java/com.aspose.html.dom.events/keyboardevent/
---
## KeyboardEvent class

The KeyboardEvent interface provides specific contextual information associated with keyboard devices. Each keyboard event references a key using a value. Keyboard events are commonly directed at the element that has the focus.

```java
public class KeyboardEvent : UIEvent
```

## Constructors

| Name | Description |
| --- | --- |
| [KeyboardEvent](keyboardevent/#constructor)(String) | Initializes a new instance of the `KeyboardEvent` class. |
| [KeyboardEvent](keyboardevent/#constructor_1)(String, IDictionary&lt;String, object&gt;) |  |

## Properties

| Name | Description |
| --- | --- |
| [getAltKey](../../com.aspose.html.dom.events/keyboardevent/altkey/) true if the Alt (alternative) (or "Option") key modifier was active. The un-initialized value of this attribute MUST be false. |
| [getBubbles](../../com.aspose.html.dom.events/event/bubbles/) Used to indicate whether or not an event is a bubbling event. If the event can bubble the value is true, else the value is false. |
| [getCancelable](../../com.aspose.html.dom.events/event/cancelable/) Used to indicate whether or not an event can have its default action prevented. If the default action can be prevented the value is true, else the value is false. |
| [getCode](../../com.aspose.html.dom.events/keyboardevent/code/) The code holds a String that identifies the physical key being pressed. The value is not affected by the current keyboard layout or modifier state, so a particular key will always return the same value. |
| [getCtrlKey](../../com.aspose.html.dom.events/keyboardevent/ctrlkey/) true if the Control (control) key modifier was active. The un-initialized value of this attribute MUST be false. |
| [getCurrentTarget](../../com.aspose.html.dom.events/event/currenttarget/) Used to indicate the [`IEventTarget`](../ieventtarget/) whose [`IEventListener`](../ieventlistener/)s are currently being processed. This is particularly useful during capturing and bubbling. |
| [getDefaultPrevented](../../com.aspose.html.dom.events/event/defaultprevented/) Returns true if preventDefault() was invoked while the cancelable attribute value is true, and false otherwise. |
| [getDetail](../../com.aspose.html.dom.events/uievent/detail/) Specifies some detail information about the Event, depending on the type of event. |
| [getEventPhase](../../com.aspose.html.dom.events/event/eventphase/) Used to indicate which phase of event flow is currently being evaluated. |
| [getIsComposing](../../com.aspose.html.dom.events/keyboardevent/iscomposing/) true if the key event occurs as part of a composition session, i.e., after a compositionstart event and before the corresponding compositionend event. The un-initialized value of this attribute MUST be false. |
| [getIsTrusted](../../com.aspose.html.dom.events/event/istrusted/) The isTrusted attribute must return the value it was initialized to. When an event is created the attribute must be initialized to false. |
| [getKey](../../com.aspose.html.dom.events/keyboardevent/key/) The key holds the key value of the key pressed. If the value is has a printed representation, it MUST be a non-empty Unicode character String, conforming to the algorithm for determining the key value defined in this specification. If the value is a control key which has no printed representation, it MUST be one of the key values defined in the key values set, as determined by the algorithm for determining the key value. Implementations that are unable to identify a key MUST use the key value Unidentified. |
| [getLocation](../../com.aspose.html.dom.events/keyboardevent/location/) The location attribute contains an indication of the logical location of the key on the device. |
| [getMetaKey](../../com.aspose.html.dom.events/keyboardevent/metakey/) true if the meta (Meta) key modifier was active. |
| [getRepeat](../../com.aspose.html.dom.events/keyboardevent/repeat/) true if the key has been pressed in a sustained manner. Holding down a key MUST result in the repeating the events keydown, beforeinput, input in this order, at a rate determined by the system configuration. For mobile devices which have long-key-press behavior, the first key event with a repeat attribute value of true MUST serve as an indication of a long-key-press. The length of time that the key MUST be pressed in order to begin repeating is configuration-dependent. |
| [getShiftKey](../../com.aspose.html.dom.events/keyboardevent/shiftkey/) true if the shift (Shift) key modifier was active. |
| [getTarget](../../com.aspose.html.dom.events/event/target/) Used to indicate the [`IEventTarget`](../ieventtarget/) to which the event was originally dispatched. |
| [getTimeStamp](../../com.aspose.html.dom.events/event/timestamp/) Used to specify the time (in milliseconds relative to the epoch) at which the event was created. Due to the fact that some systems may not provide this information the value of timeStamp may be not available for all events. When not available, a value of 0 will be returned. Examples of epoch time are the time of the system start or 0:0:0 UTC 1st January 1970. |
| [getType](../../com.aspose.html.dom.events/event/type/) The name of the event (case-insensitive). The name must be an XML name. |
| [getView](../../com.aspose.html.dom.events/uievent/view/) The view attribute identifies the Window from which the event was generated. The un-initialized value of this attribute MUST be null. |

## Methods

| Name | Description |
| --- | --- |
| [getPlatformType](../../com.aspose.html.dom/domobject/getplatformtype/)() | This method is used to retrieve the ECMAScript object . |
| [initEvent](../../com.aspose.html.dom.events/event/initevent/)(String, bool, bool) | The [`InitEvent`](../event/initevent/) method is used to initialize the value of an [`Event`](../event/) created through the[`IDocumentEvent`](../idocumentevent/) interface. |
| [preventDefault](../../com.aspose.html.dom.events/event/preventdefault/)() | If an event is cancelable, the [`PreventDefault`](../event/preventdefault/) method is used to signify that the event is to be canceled, meaning any default action normally taken by the implementation as a result of the event will not occur. |
| [stopImmediatePropagation](../../com.aspose.html.dom.events/event/stopimmediatepropagation/)() | Invoking this method prevents event from reaching any event listeners registered after the current one and when dispatched in a tree also prevents event from reaching any other objects. |
| [stopPropagation](../../com.aspose.html.dom.events/event/stoppropagation/)() | The [`StopPropagation`](../event/stoppropagation/) method is used prevent further propagation of an event during event flow. |

## Fields

| Name | Description |
| --- | --- |
| const [DOM_KEY_LOCATION_LEFT](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_left/) | The key activated originated from the left key location (when there is more than one possible location for this key). |
| const [DOM_KEY_LOCATION_NUMPAD](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_numpad/) | The key activation originated on the numeric keypad or with a virtual key corresponding to the numeric keypad (when there is more than one possible location for this key). Note that the NumLock key should always be encoded with a location of DOM_KEY_LOCATION_STANDARD. |
| const [DOM_KEY_LOCATION_RIGHT](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_right/) | The key activation originated from the right key location (when there is more than one possible location for this key). |
| const [DOM_KEY_LOCATION_STANDARD](../../com.aspose.html.dom.events/keyboardevent/dom_key_location_standard/) | The key activation MUST NOT be distinguished as the left or right version of the key, and (other than the NumLock key) did not originate from the numeric keypad (or did not originate with a virtual key corresponding to the numeric keypad). |

### See Also

* class [UIEvent](../uievent/)
* package [com.aspose.html.dom.events](../../com.aspose.html.dom.events/)
* package [Aspose.HTML](../../)
